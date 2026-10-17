<!-- Source: Notion page [032 AI Design Patterns Catalog](https://app.notion.com/p/3aadff1c1f74802d8884dfbfd0eee158?pvs=204). Last edited 2026-08-07T01:53:23.126Z. Extracted as an archival segment from one combined page. -->

---
document_id: DOC-032-PART-I
parent_document:
- DOC-032
title: AI Design Pattern Catalog - Introduction & Pattern Philosophy
book: Product Bible
domain: Artificial Intelligence
category: Design Patterns
version: 1.0.0
status: Draft
owner: Chief AI Product Officer
created_date: 2026-07-27
related_documents:
- DOC-031
tags:
- ai
- architecture
- design-pattern
- engineering
- product-bible
context_scope: Global
## summary:
Defines the philosophy, objectives, taxonomy, lifecycle, governance,
and engineering principles of reusable AI Design Patterns used
throughout the RoRo platform.
# DOC-032
# AI Design Pattern Catalog
## Part I
# Introduction & Pattern Philosophy
Version 1.0.0
Status : Draft
---
archive_source: Notion
source_page_id: 3aadff1c-1f74-802d-8884-dfbfd0eee158
source_page_url: https://app.notion.com/p/3aadff1c1f74802d8884dfbfd0eee158?pvs=204

# 1. Purpose
본 문서는 AI Product를 구축하기 위한 **AI Design Pattern**의 철학과 설계 원칙을 정의한다.
본 문서는 다음 목적을 가진다.
- AI 시스템의 재사용성 향상
- 설계 일관성 확보
- 개발 생산성 향상
- 유지보수 비용 절감
- AI Engineering Standard 확립
---
# 2. Why Design Patterns?
초기의 AI 서비스는 대부분 하나의 Prompt와 하나의 Model만으로도 구현할 수 있다.
그러나 제품이 성장하면 다음과 같은 문제가 발생한다.
- Prompt의 복잡도 증가
- Context 관리 어려움
- Agent 간 의존성 증가
- 테스트 어려움
- 품질 일관성 저하
- 유지보수 비용 증가
이러한 문제를 해결하기 위해 AI Design Pattern이 필요하다.
---
# 3. Design Pattern Definition
AI Design Pattern은 반복적으로 발생하는 AI 시스템 설계 문제에 대해 검증된 해결 방법을 정의한 재사용 가능한 설계 표준이다.
Pattern은 코드가 아니다.
Pattern은
- 구조(Structure)
- 역할(Role)
- 책임(Responsibility)
- 흐름(Flow)
- 적용 기준(When to Use)
을 정의하는 설계 규칙이다.
---
# 4. Vision
RoRo는 기능(Function)을 만드는 것이 아니라
**Pattern을 조합하여 AI Product를 구축한다.**
즉,
```plain text
Requirement

↓

Pattern Selection

↓

Pattern Composition

↓

Implementation

↓

Evaluation

↓

Improvement
```
---
# 5. Design Philosophy
## Principle 1
Reuse Before Reinvent
새로운 구조를 만들기보다 검증된 Pattern을 우선 활용한다.
---
## Principle 2
Composition Over Complexity
복잡한 하나의 Prompt보다
단순한 여러 Pattern의 조합을 선호한다.
---
## Principle 3
Single Responsibility
하나의 Pattern은 하나의 문제만 해결한다.
---
## Principle 4
Replaceability
Pattern은 언제든 다른 Pattern으로 교체 가능해야 한다.
---
## Principle 5
Observability
모든 Pattern은
관찰 가능해야 한다.
---
## Principle 6
Scalability
제품 성장 시에도
Pattern 변경 없이 확장 가능해야 한다.
---
# 6. Pattern Taxonomy
RoRo는 모든 Pattern을 다음 8개의 영역으로 분류한다.
| Category | Description |
| --- | --- |
| Interaction | 사용자와 AI의 상호작용 |
| Prompt | Prompt Engineering |
| Context | Context Engineering |
| Agent | Multi-Agent Architecture |
| Knowledge | Knowledge & RAG |
| Workflow | AI Process Flow |
| Safety | Trust & Safety |
| Evaluation | Quality Evaluation |
---
# 7. Pattern Lifecycle
모든 Pattern은 동일한 Lifecycle을 가진다.
```plain text
Identify Problem

↓

Analyze

↓

Design Pattern

↓

Validate

↓

Standardize

↓

Reuse

↓

Improve
```
---
# 8. Pattern Classification
모든 Pattern은 다음 중 하나로 분류된다.
## Structural Pattern
구조를 정의한다.
예)
- Layered Context
- Memory Architecture
---
## Behavioral Pattern
행동을 정의한다.
예)
- Retry
- Approval
- Reflection
---
## Coordination Pattern
협업을 정의한다.
예)
- Orchestrator
- Planner
- Reviewer
---
## Operational Pattern
운영을 정의한다.
예)
- A/B Test
- Monitoring
- Rollback
---
# 9. Pattern Metadata Standard
모든 Pattern은 반드시 아래 Metadata를 포함한다.
| Field | Description |
| --- | --- |
| Pattern ID | 고유 식별자 |
| Pattern Name | 이름 |
| Category | 분류 |
| Version | 버전 |
| Status | Draft / Approved |
| Owner | 담당자 |
| Related Patterns | 관련 Pattern |
---
# 10. Standard Pattern Template
모든 Pattern은 동일한 구조를 따른다.
```plain text
Purpose

Problem

Context

Architecture

Sequence

Implementation

Advantages

Disadvantages

Trade-offs

Metrics

Checklist

Anti-pattern

RoRo Example

Related Patterns
```
---
# 11. Pattern Selection Strategy
새로운 기능을 설계할 때는 다음 순서를 따른다.
```plain text
Business Goal

↓

Problem Analysis

↓

Pattern Selection

↓

Pattern Combination

↓

Implementation

↓

Evaluation
```
새로운 Pattern은 기존 Pattern으로 해결이 불가능할 경우에만 생성한다.
---
# 12. Pattern Relationships
Pattern은 독립적으로 존재하지 않는다.
예시
```plain text
Layered Context

↓

Planner

↓

Orchestrator

↓

Reviewer

↓

Human Approval

↓

Evaluation
```
Pattern은 서로 조합되어 하나의 AI Workflow를 구성한다.
---
# 13. Pattern Governance
새로운 Pattern은 다음 절차를 따른다.
```plain text
Proposal

↓

Architecture Review

↓

Prototype

↓

Validation

↓

Approval

↓

Catalog Registration

↓

Production Use
```
---
# 14. Best Practices
권장 사항
- Pattern 재사용을 우선한다.
- 하나의 Pattern은 하나의 책임만 가진다.
- Pattern 간 결합도를 최소화한다.
- Pattern은 독립적으로 테스트 가능해야 한다.
- Pattern 변경 시 영향 범위를 명확히 분석한다.
---
# 15. Anti-patterns
다음 사례는 금지한다.
## Mega Pattern
모든 문제를 하나의 Pattern으로 해결하려는 구조
---
## Hidden Dependency
Pattern 간 숨겨진 의존성
---
## Pattern Duplication
동일한 역할의 Pattern을 여러 개 생성
---
## Tight Coupling
Pattern 간 강한 결합
---
## Unverified Pattern
검증 없이 운영 환경에 적용
---
# 16. RoRo Design Philosophy
RoRo는 AI 기능을 직접 구현하지 않는다.
RoRo는
- Design Pattern
- Prompt Pattern
- Agent Pattern
- Context Pattern
을 조합하여 새로운 기능을 만든다.
예)
Memory Book 생성
↓
Orchestrator Pattern
-
Layered Context Pattern
-
Reviewer Pattern
-
Human Approval Pattern
-
Evaluation Pattern
↓
Memory Book Feature
---
# 17. Required Artifacts
본 Part에서 정의하는 필수 산출물
- AI Pattern Catalog
- Pattern Registry
- Pattern Review Checklist
- Pattern Dependency Map
- Pattern Governance Policy
---
# 18. References
- DOC-031 AI Product Framework
- DOC-031 Part V AI Agent Framework
- DOC-031 Part VIII AI Evaluation Framework
- DOC-031 Part X AI Governance & Ethics Framework
---
# Document Information
Document ID
DOC-032-PART-I
Document
AI Design Pattern Catalog
Part
I
Title
Introduction & Pattern Philosophy
Version
1.0.0
Status
Draft
Next
DOC-032 Part II
Pattern Specification Standard
