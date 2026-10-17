---
document_id: RORO-ENG-MVP-001
title: MVP Implementation Readiness
document_type: Engineering Planning Note
version: 0.1.0
status: Draft
language: ko-KR
last_updated: 2026-10-17
sources:
  - docs/product/mvp-scope-definition.md
  - docs/product/prds/prd-001-trip-creation.md
  - docs/product/prds/prd-002-moment-logging.md
  - docs/product/prds/prd-003-photo-upload.md
  - docs/product/prds/prd-004-ai-travel-diary-generation.md
  - docs/product/prds/prd-005-highlight-video-generation.md
  - docs/product/product-decision-log.md
  - docs/ux/screen-specification-v1-0.md
  - docs/ux/screen-inventory-v1-0.md
  - docs/ux/ui-specifications/user-flow.md
  - docs/ux/user-flow-specification-v1-0.md
  - docs/project/user-flow-specification-v1-0.md
  - docs/project/08-qa.md
---

# RoRo MVP Implementation Readiness

> **Draft.** This note connects existing product and UX documents to a build sequence. It does not replace the PRDs or select a technical stack. The repository currently contains documentation only. The product target is a shared iOS and Android app (direct user conversation decision, 2026-10-17); framework (Flutter vs React Native), app repository, backend, authentication design, and photo-storage implementation remain undecided.

## 1. What Is Already Decided

The following are documented product decisions, subject to their source documents' existing status:

- MVP scope includes Trip, Timeline, Moment, AI Diary, and basic Expense; SNS, Community, Card Integration, Advanced OCR, and Calendar Sync are excluded. The stated principle is launchability over feature volume. ([MVP Scope](../product/mvp-scope-definition.md))
- Moment is the core memory unit; AI produces a draft for user review; the product is private by default; expense tracking stays simple. ([Product Decision Log](../product/product-decision-log.md))
- A Trip precedes and organizes Moments; PRD-001 calls for trip creation, dates, destination, and traveler information. ([PRD-001](../product/prds/prd-001-trip-creation.md))
- Moment capture includes photo, time/location, and note concepts, and should feed the Timeline. ([PRD-002](../product/prds/prd-002-moment-logging.md))
- AI Diary follows **AI Draft → User Review → Final Memory** and is editable. ([PRD-004](../product/prds/prd-004-ai-travel-diary-generation.md))

These decisions define product intent, but do not yet settle the technical or privacy choices needed to implement them.

## 2. Build Sequence and Acceptance Gates

| Step | Build focus | Gate before moving on |
| --- | --- | --- |
| 0. Resolve launch blockers | Target platform is decided: one app for iOS and Android. Choose framework (Flutter or React Native), app repository/setup, backend and authentication approach, and photo storage/data ownership. | Framework and core services are selected; a minimal architecture/environment plan exists; secrets and user data have an approved handling path. |
| 1. Trip foundation | Implement the smallest data path for creating, listing, and opening a Trip. Start with PRD-001 fields and mark optional fields explicitly. | A user can create a Trip, retrieve it after restart, and reach its workspace; validation and empty/error states are defined. |
| 2. Moment and Timeline | Add a Moment to one Trip, allow a note and time, and show persisted Moments in chronological order. | A Moment remains linked to its Trip and appears in Timeline after reload; duplicate submission and failure behavior are addressed. |
| 3. Photo capture/upload | Support user-selected photos, upload/storage, Moment attachment, and permission/metadata handling. Treat AI recommendations/analysis as a gated decision below. | User can choose, attach, view, and remove or replace a photo as specified; denied permission or upload failure does not silently lose the Moment. |
| 4. AI Diary | Generate a daily draft from the explicitly selected/authorized Trip data, then let the user edit and save it. | Draft is visibly distinct from saved memory; user review/edit is possible; no unsupported photo inference is presented as fact; save result is verified. |
| 5. Basic Expense and release QA | Implement only the simple expense scope once its minimum fields/flows are confirmed; run end-to-end QA across Trip → Moment/Photo → Diary and core failure paths. | QA has linked cases, expected results, bug triage, and a release decision. The existing QA note is only a placeholder and needs an executable plan. |

The sequence is a proposal based on documented dependencies, not a committed sprint plan. Map and Highlight are not prerequisites for this core path.

## 3. Conflicts and Decisions Still Needed

### Photo AI versus launchability and privacy

PRD-003 lists AI Recommended Photo Selection, upload before approval, and AI analysis as MVP requirements/acceptance criteria. PRD-004 also lists recommended photos. The MVP scope prioritizes launchability, while the product decision log says private by default. The documents do not define what photo analysis runs, where photos/metadata go, whether processing is on-device or server-side, or what consent and retention apply.

**Owner decision required:** Is AI photo recommendation/analysis a launch requirement, or can the first launch ship manual photo selection/upload and add AI analysis later? If retained, define explicit consent, processing location/provider, metadata handling, retention/deletion, and user-visible controls before implementation. Until decided, treat AI analysis and recommendations as blocked scope, not an implicit default.

### GPS and location permission

PRD-002 expects automatic GPS and timestamp collection, but no permission behavior, fallback, or location privacy rule is specified. ([PRD-002](../product/prds/prd-002-moment-logging.md))

**Owner decision required:** Is location optional, user-triggered, or required? Define behavior when permission is denied, whether EXIF location is read, and whether location may be removed before saving. Coding location capture is unblocked only after this policy is stated. Timestamp handling can proceed independently if its source and timezone behavior are defined.

### Screen inventory and MVP scope

The screen inventory lists Map and Highlight; the screen specification lists Map and Trip Summary. The UX user flow includes Highlight Video and Share / Archive, and PRD-005 defines Highlight Video and family sharing. These are not all included in the concise MVP scope list. The detailed user-flow spec explicitly excludes Google Calendar integration, consistent with the scope exclusion, while leaving manual schedule entry. Map also depends on the unresolved location policy. The product decision log says private by default, so family sharing needs a specific owner decision and cannot be inferred from the flow. ([MVP Scope](../product/mvp-scope-definition.md), [Screen Inventory](../ux/screen-inventory-v1-0.md), [Screen Specification](../ux/screen-specification-v1-0.md), [User Flow](../ux/ui-specifications/user-flow.md), [Detailed User Flow Specification](../project/user-flow-specification-v1-0.md), [PRD-005](../product/prds/prd-005-highlight-video-generation.md), [Product Decision Log](../product/product-decision-log.md))

**Owner decision required:** Confirm Map, Highlight Video, Trip Summary, and any family sharing as launch scope or later scope. Do not infer launch priority from their presence in a screen inventory or flow list. Keep Google Calendar Sync, card integration, and social/community features excluded unless the scope decision changes; manual schedule entry is distinct from calendar integration.

### Engineering and QA readiness

The repository contains PRDs and planning documents but no application code. The shared iOS/Android target is decided; framework, app repository, backend, authentication, and photo storage are not. The QA document says “Test Plan, Quality Checklist, Bug Management” but gives no cases or release criteria. ([QA](../project/08-qa.md))

**Owner decisions required:** Choose the mobile framework and technical owner; approve authentication and data ownership; choose photo storage and access-control approach; name who owns privacy/security review. Before release work, turn the QA placeholder into test cases mapped to PRD acceptance criteria, including permission denial, upload interruption, duplicate requests, diary generation failure, and verified save.

## 4. What Unblocks Coding

Coding can begin after the owner supplies or approves:

1. **Technical baseline:** choose the cross-platform framework (Flutter or React Native), create/select the app repository and toolchain, and decide backend/API and authentication. Target platforms are iOS and Android.
2. **Data and photo boundary:** where Trip/Moment/Diary data and photos live, who can access them, and deletion/export expectations.
3. **Location policy:** whether location is collected, how permission and denial work, and whether photo EXIF is read.
4. **Launch scope:** explicit yes/no for AI photo analysis/recommendations, Map, Highlight Video, Trip Summary, and family sharing.
5. **MVP quality owner:** named person responsible for QA cases and release acceptance.

Until these are decided, product-independent UI exploration and non-sensitive scaffolding may proceed, but photo, location, authentication, and AI integrations should not be hard-coded around assumptions.

## 5. Source Documents

- [MVP Scope Definition](../product/mvp-scope-definition.md)
- [PRD-001 — Trip Creation](../product/prds/prd-001-trip-creation.md)
- [PRD-002 — Moment Logging](../product/prds/prd-002-moment-logging.md)
- [PRD-003 — Photo Upload](../product/prds/prd-003-photo-upload.md)
- [PRD-004 — AI Travel Diary Generation](../product/prds/prd-004-ai-travel-diary-generation.md)
- [PRD-005 — Highlight Video Generation](../product/prds/prd-005-highlight-video-generation.md)
- [Product Decision Log](../product/product-decision-log.md)
- [Screen Inventory](../ux/screen-inventory-v1-0.md)
- [Screen Specification](../ux/screen-specification-v1-0.md)
- [User Flow Specification](../ux/user-flow-specification-v1-0.md)
- [Detailed User Flow Specification](../project/user-flow-specification-v1-0.md)
- [UX User Flow](../ux/ui-specifications/user-flow.md)
- [QA](../project/08-qa.md)


