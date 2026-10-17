<!-- Source: Notion page [003_Metadata_Standard](https://app.notion.com/p/3a8dff1c1f74803085fbf289fe89e2db?pvs=204). Page ID: 3a8dff1c-1f74-8030-85fb-f289fe89e2db. Path: My Travel - RoRo / 100 📖 Foundation / 110 Documentation. Last edited: 2026-07-25T07:05:04.428Z. -->

# 003_Metadata_Standard

---
document_id: DOC-003
title: Metadata Standard
book: Book I - Foundation
category: Documentation Standards
version: 1.0.0
status: Approved
owner: Product Owner
created: 2026-07-25
updated: 2026-07-25
author: RoRo Product Genome
related_documents:
- DOC-001
- DOC-002
related_adr:
- ADR-031
tags:
- metadata
- documentation
- standard
- knowledge
---
# Book I – Foundation
# 003 Metadata Standard
Version 1.0
Status: Approved
---
# Purpose
본 문서는 RoRo Product Genome에서 사용되는 모든 공식 문서의 Metadata 표준을 정의한다.
Metadata는 문서의 부가 정보가 아니다.
Metadata는 사람과 AI가 동일한 방식으로 문서를 식별하고, 연결하고, 검색하고, 관리하기 위한 공식 인터페이스이다.
모든 공식 문서는 본 표준을 준수해야 한다.
---
# Part I
# Metadata Philosophy
---
# Chapter 1
# What is Metadata
## Definition
Metadata는 Document를 설명하는 구조화된 데이터이다.
Document의 본문(Content)이 "무엇을 설명하는가"를 나타낸다면,
Metadata는 "이 문서가 무엇이며, 어떻게 관리되어야 하는가"를 설명한다.
Metadata는 다음 목적을 가진다.
- 문서 식별
- 문서 관리
- 검색
- 참조
- AI Context 구성
- 변경 추적
- Governance 지원
Metadata는 Document와 분리될 수 없는 공식 구성 요소이다.
---
## Constitution Rules
Rule 1-1
모든 공식 문서는 Metadata를 가진다.
Rule 1-2
Metadata는 문서보다 먼저 해석된다.
Rule 1-3
Metadata는 사람이 읽을 수 있어야 하며 AI도 해석 가능해야 한다.
---
## Architecture Decision
ADR-031
Metadata를 Documentation의 필수 구성 요소로 정의한다.
---
# Chapter 2
# Metadata Objectives
Metadata는 다음 목표를 달성하기 위해 존재한다.
## Identity
문서를 유일하게 식별한다.
---
## Discoverability
문서를 검색할 수 있도록 한다.
---
## Traceability
문서 변경 이력을 추적한다.
---
## Relationship
문서 간 관계를 표현한다.
---
## Governance
문서 상태와 책임자를 관리한다.
---
## AI Readability
AI Agent가 Context를 자동으로 구성할 수 있도록 한다.
---
## Constitution Rules
Rule 2-1
Metadata는 Document의 Identity를 제공해야 한다.
Rule 2-2
Metadata는 검색 가능한 구조를 제공해야 한다.
---
## Architecture Decision
ADR-032
Metadata의 6대 목적을 공식 채택한다.
---
# Chapter 3
# Metadata Principles
모든 Metadata는 다음 원칙을 따른다.
## Single Source of Truth
동일한 Metadata는 하나만 존재한다.
---
## Consistency
모든 문서는 동일한 Metadata 구조를 사용한다.
---
## Machine Readable
Metadata는 AI가 쉽게 파싱할 수 있어야 한다.
---
## Human Readable
사람도 쉽게 이해할 수 있어야 한다.
---
## Tool Independent
Metadata는 Notion, GitHub, Markdown 등 특정 도구에 종속되지 않는다.
---
## Extensible
필요 시 새로운 필드를 추가할 수 있다.
기존 필드의 의미는 변경하지 않는다.
---
## Constitution Rules
Rule 3-1
Metadata는 Tool Independent 해야 한다.
Rule 3-2
Metadata는 Backward Compatibility를 유지해야 한다.
---
## Architecture Decision
ADR-033
Metadata Design Principles를 채택한다.
---
# Chapter 4
# Metadata Categories
RoRo는 Metadata를 다음 네 가지 범주로 구분한다.
## Identity Metadata
문서를 식별한다.
예)
- Document ID
- Title
---
## Governance Metadata
문서를 관리한다.
예)
- Owner
- Status
- Version
---
## Relationship Metadata
문서를 연결한다.
예)
- Related Documents
- Related ADR
- Dependencies
---
## AI Metadata
AI Context를 구성한다.
예)
- Tags
- Context Scope
- Retrieval Priority
---
Metadata Category는 논리적 구분이며,
Workspace의 구현 방식은 자유롭게 선택할 수 있다.
---
## Architecture Decision
ADR-034
Metadata를 네 개의 Category로 분류한다.
---
# Chapter 5
# Metadata Lifecycle
Metadata는 Document의 생명주기 전체를 따라 변경된다.
새로운 문서가 생성될 때 Metadata도 생성된다.
문서가 수정되면 Metadata도 함께 수정된다.
문서가 Archived 상태가 되어도 Metadata는 유지된다.
Metadata를 삭제하는 것은 Document Identity를 삭제하는 것과 동일하게 간주한다.
---
## Constitution Rules
Rule 5-1
Metadata는 Document와 함께 생성된다.
Rule 5-2
Metadata는 Document보다 먼저 삭제되어서는 안 된다.
Rule 5-3
Metadata 변경은 Revision History에 기록한다.
---
## Architecture Decision
ADR-035
Metadata Lifecycle Policy를 채택한다.
---
## Next Part
Part II
Metadata Schema
# Part II
# Metadata Schema Specification
---
# Chapter 6
# Metadata Schema Overview
## 6.1 Purpose
Metadata Schema는 모든 공식 Document가 따라야 하는 표준 구조(Standard Structure)를 정의한다.
Schema는 Metadata Field의 집합이며, 각 Field는 명확한 의미(Semantics)와 책임(Responsibility)을 가진다.
모든 구현(Notion, GitHub, Markdown Front Matter 등)은 본 Schema를 기준으로 Mapping되어야 한다.
---
## 6.2 Design Goals
Metadata Schema는 다음 목표를 가진다.
- Tool Independent
- Human Readable
- Machine Readable
- AI Readable
- Extensible
- Backward Compatible
---
## 6.3 Schema Layers
Metadata는 다음 네 개의 계층으로 구성된다.
Layer 1
Identity
↓
Layer 2
Governance
↓
Layer 3
Relationship
↓
Layer 4
AI Context
각 Layer는 독립적으로 확장 가능하다.
---
## 6.4 Schema Stability
필수(Field Required) Metadata는 Version 1.x 동안 의미를 변경하지 않는다.
새로운 Field는 추가할 수 있으나 기존 Field의 의미를 변경하거나 삭제해서는 안 된다.
---
## Constitution Rules
Rule 6-1
Metadata Schema는 Product Genome의 공식 표준이다.
Rule 6-2
모든 구현은 Schema를 준수해야 한다.
---
## Architecture Decision
ADR-036
Metadata Schema Layer를 공식 채택한다.
---
# Chapter 7
# Identity Metadata
## 7.1 Purpose
Identity Metadata는 문서를 유일하게 식별하기 위한 최소 정보 집합이다.
Identity는 저장 위치와 관계없이 동일해야 한다.
---
## 7.2 Required Fields
다음 항목은 필수이다.
- Document ID
- Title
- Book
- Domain
- Category
---
## 7.3 Identity Rules
Document ID는 변경하지 않는다.
Title은 변경될 수 있다.
Book과 Domain은 문서의 책임 범위를 나타낸다.
Category는 문서의 기능적 분류를 나타낸다.
---
## 7.4 Constraints
동일한 Document ID를 가진 두 개의 문서는 존재할 수 없다.
삭제된 Document ID도 재사용하지 않는다.
---
## Constitution Rules
Rule 7-1
Identity는 영구적이다.
Rule 7-2
Document ID는 프로젝트 전체에서 유일해야 한다.
---
## Architecture Decision
ADR-037
Persistent Identity Model을 채택한다.
---
# Chapter 8
# Governance Metadata
## 8.1 Purpose
Governance Metadata는 문서의 관리 상태와 책임을 정의한다.
---
## 8.2 Required Fields
- Version
- Status
- Owner
- Created Date
- Last Updated
---
## 8.3 Responsibilities
Version은 변경 이력을 관리한다.
Status는 문서의 현재 상태를 나타낸다.
Owner는 문서의 최종 책임자를 나타낸다.
Created Date와 Last Updated는 변경 추적을 지원한다.
---
## 8.4 Constraints
Owner가 없는 공식 문서는 허용하지 않는다.
Status가 정의되지 않은 문서는 Draft로 간주한다.
---
## Constitution Rules
Rule 8-1
Governance Metadata는 항상 최신 상태를 유지해야 한다.
Rule 8-2
Owner는 최종 승인 책임을 가진다.
---
## Architecture Decision
ADR-038
Governance Metadata Standard를 채택한다.
---
# Chapter 9
# Relationship Metadata
## 9.1 Purpose
Relationship Metadata는 문서 간의 연결 관계를 정의한다.
Knowledge는 개별 문서가 아니라 연결된 네트워크로 관리된다.
---
## 9.2 Required Fields
- Related Documents
- Related ADR
- Dependencies
---
## 9.3 Relationship Principles
모든 Reference는 실제 존재하는 Document를 가리켜야 한다.
순환 참조(Circular Reference)는 허용하지 않는다.
Source of Truth는 항상 하나만 존재해야 한다.
---
## 9.4 Dependency Rules
Dependency는 다음으로 구분한다.
- Required Dependency
- Optional Dependency
- Informational Dependency
---
## Constitution Rules
Rule 9-1
Reference는 검증 가능해야 한다.
Rule 9-2
Broken Reference는 Documentation Error이다.
---
## Architecture Decision
ADR-039
Relationship Metadata Model을 채택한다.
---
# Chapter 10
# AI Metadata
## 10.1 Purpose
AI Metadata는 AI Agent가 문서를 검색하고 이해하며 Context를 구성하기 위한 정보를 제공한다.
AI Metadata는 문서의 의미를 변경하지 않는다.
AI가 문서를 효율적으로 활용할 수 있도록 지원한다.
---
## 10.2 Required Fields
- Tags
- Keywords
- Summary
- Context Scope
---
## 10.3 Optional Fields
필요한 경우 다음 정보를 추가할 수 있다.
- Retrieval Priority
- Embedding Scope
- AI Notes
- Recommended Context Documents
---
## 10.4 AI Principles
AI Metadata는 사람 중심 Documentation을 대체하지 않는다.
AI Metadata는 사람과 AI가 동일한 Source of Truth를 공유하도록 지원한다.
---
## Constitution Rules
Rule 10-1
AI Metadata는 문서 내용과 모순되어서는 안 된다.
Rule 10-2
AI Metadata는 검색 품질 향상을 위한 보조 정보이다.
---
## Architecture Decision
ADR-040
AI Metadata Layer를 Product Genome 표준으로 채택한다.
---
## Part II Summary
Metadata Schema는 네 개의 계층으로 구성된다.
1. Identity
2. Governance
3. Relationship
4. AI Context
각 계층은 독립적으로 확장 가능하며, 모든 Workspace는 동일한 의미를 유지해야 한다.
---
## Next Part
Part III
Metadata Field Specification
# Part III
# Metadata Field Specification
---
# Chapter 11
# Identity Metadata Specification
## 11.1 Document ID
### Definition
Document ID는 RoRo Knowledge Base 내에서 Document를 유일하게 식별하는 영구 식별자(Persistent Identifier)이다.
---
### Schema
| Attribute | Value |
| --- | --- |
| Field Name | document_id |
| Display Name | Document ID |
| Type | String |
| Required | Yes |
| Cardinality | 1 |
| Editable | No |
| Category | Identity |
| Example | DOC-003 |
---
### Format
```plain text
DOC-{Number}
```
Example:
```plain text
DOC-001
DOC-002
DOC-003
```
---
### Rules
Rule 11-1
Document ID는 프로젝트 전체에서 유일해야 한다.
Rule 11-2
삭제된 Document ID는 재사용하지 않는다.
Rule 11-3
Document 이동(Migration) 시에도 ID는 유지한다.
---
## 11.2 Title
### Definition
Title은 Document가 표현하는 Knowledge의 공식 명칭이다.
---
### Schema
| Attribute | Value |
| --- | --- |
| Field Name | title |
| Display Name | Title |
| Type | String |
| Required | Yes |
| Cardinality | 1 |
| Editable | Yes |
| Category | Identity |
---
### Rules
Title은 다음 조건을 만족해야 한다.
- 의미가 명확해야 한다.
- 중복 Title을 피해야 한다.
- Document ID를 대체하지 않는다.
---
## 11.3 Book
### Definition
Book은 Document가 속한 최상위 Knowledge 영역이다.
---
### Schema
| Attribute | Value |
| --- | --- |
| Field Name | book |
| Type | Enum |
| Required | Yes |
| Editable | Limited |
---
### Allowed Values
```plain text
Foundation
Product
Design
Engineering
AI
Operations
Research
Business
```
---
## 11.4 Domain
### Definition
Domain은 Document가 책임지는 Knowledge 영역이다.
---
### Schema
| Attribute | Value |
| --- | --- |
| Field Name | domain |
| Type | String |
| Required | Yes |
---
### Rules
하나의 Document는 하나의 Primary Domain만 가진다.
---
## 11.5 Category
### Definition
Category는 Domain 내부에서 Document를 분류하는 중간 구조이다.
---
### Schema
| Attribute | Value |
| --- | --- |
| Field Name | category |
| Type | String |
| Required | Yes |
---
# Chapter 12
# Governance Metadata Specification
---
## 12.1 Version
### Definition
Version은 Document 변경 상태를 관리하는 번호이다.
---
### Schema
| Attribute | Value |
| --- | --- |
| Field Name | version |
| Type | Semantic Version |
| Required | Yes |
| Example | 1.0.0 |
---
### Format
```plain text
Major.Minor.Patch
```
Example:
```plain text
1.0.0
1.1.0
2.0.0
```
---
### Version Rules
Major
구조 또는 의미 변경
Minor
내용 추가
Patch
오류 수정
---
## 12.2 Status
### Definition
Status는 Document의 현재 Lifecycle 상태를 나타낸다.
---
### Schema
| Attribute | Value |
| --- | --- |
| Field Name | status |
| Type | Enum |
| Required | Yes |
---
### Values
```plain text
Draft

Review

Approved

Published

Deprecated

Archived
```
---
## 12.3 Owner
### Definition
Owner는 Document의 최종 책임자를 의미한다.
---
### Schema
| Attribute | Value |
| --- | --- |
| Field Name | owner |
| Type | Person / Role |
| Required | Yes |
---
### Rules
작성자(Author)와 Owner는 다를 수 있다.
Owner는 품질 책임을 가진다.
---
## 12.4 Created Date
### Definition
Document 최초 생성 날짜.
---
### Schema
| Attribute | Value |
| --- | --- |
| Field Name | created_date |
| Type | Date |
| Required | Yes |
---
## 12.5 Last Updated
### Definition
마지막 변경 날짜.
---
### Schema
| Attribute | Value |
| --- | --- |
| Field Name | updated_date |
| Type | Date |
| Required | Yes |
---
# Chapter 13
# Relationship Metadata Specification
---
## 13.1 Related Documents
### Definition
현재 Document와 직접 연결되는 다른 Document 목록.
---
### Schema
| Attribute | Value |
| --- | --- |
| Field Name | related_documents |
| Type | Relation Array |
| Required | Yes |
---
### Example
```plain text
[
 DOC-001,
 DOC-002,
 DOC-004
]
```
---
## 13.2 Related ADR
### Definition
Document와 관련된 Architecture Decision Record 목록.
---
### Schema
| Attribute | Value |
| --- | --- |
| Field Name | related_adr |
| Type | Relation Array |
---
## 13.3 Dependencies
### Definition
Document 이해 또는 구현에 필요한 선행 Knowledge.
---
### Schema
| Attribute | Value |
| --- | --- |
| Field Name | dependencies |
| Type | Relation Array |
---
# Chapter 14
# AI Metadata Specification
---
## 14.1 Tags
### Definition
Document의 의미 검색을 지원하는 Keyword 집합.
---
### Schema
| Attribute | Value |
| --- | --- |
| Field Name | tags |
| Type | Array |
| Required | Yes |
---
### Example
```plain text
[
metadata,
documentation,
knowledge
]
```
---
## 14.2 Summary
### Definition
AI와 사용자가 빠르게 Document 목적을 이해하기 위한 요약 정보.
---
### Schema
| Attribute | Value |
| --- | --- |
| Field Name | summary |
| Type | Text |
| Required | Recommended |
---
## 14.3 Context Scope
### Definition
AI Retrieval 시 해당 Document가 제공하는 Context 범위를 정의한다.
---
### Schema
| Attribute | Value |
| --- | --- |
| Field Name | context_scope |
| Type | Enum |
---
### Example
```plain text
Global

Domain

Feature

Implementation

Reference
```
---
# Chapter 15
# Metadata Extension Model
---
## 15.1 Purpose
RoRo는 미래 요구사항에 대응하기 위해 Metadata Extension을 허용한다.
---
## 15.2 Extension Rules
새로운 Field 추가는 가능하다.
단,
다음 조건을 만족해야 한다.
- 목적이 명확해야 한다.
- 기존 Field와 중복되지 않아야 한다.
- Version 기록이 필요하다.
---
## 15.3 Forbidden Changes
다음은 금지한다.
- 기존 Field 의미 변경
- 필수 Field 삭제
- 동일 목적 Field 추가
---
## Architecture Decision
ADR-041
Metadata Extension Policy를 채택한다.
---
## Part III Summary
RoRo Metadata는 다음 Schema를 가진다.
```plain text
Identity

- document_id
- title
- book
- domain
- category


Governance

- version
- status
- owner
- created_date
- updated_date


Relationship

- related_documents
- related_adr
- dependencies


AI Context

- tags
- summary
- context_scope
```
---
## Next Part
Part IV
Workspace Mapping Specification
(Notion / GitHub / AI System Mapping)
# Part IV
# Workspace Mapping Specification
---
# Chapter 16
# Workspace Mapping Principles
## 16.1 Purpose
Workspace Mapping은 Metadata Standard를 실제 저장 환경에 적용하기 위한 규칙을 정의한다.
현재 RoRo의 Primary Workspace는 Notion이다.
그러나 Metadata의 의미와 구조는 Notion 기능에 종속되지 않는다.
---
## 16.2 Mapping Model
Metadata Standard
↓
Workspace Property
↓
User Interface
↓
AI Retrieval Layer
---
## 16.3 Mapping Responsibility
Workspace는 다음 역할을 수행한다.
- Metadata 입력
- Metadata 표시
- Relationship 관리
- 검색 지원
- 협업 지원
Workspace는 다음 역할을 수행하지 않는다.
- Knowledge 정의
- Business Rule 결정
- Source of Truth 변경
---
## 16.4 Implementation Principle
모든 Workspace 구현은 다음 조건을 만족해야 한다.
### Semantic Compatibility
동일한 의미를 유지해야 한다.
---
### Data Integrity
필수 Metadata가 누락되지 않아야 한다.
---
### Migration Capability
다른 Workspace로 이동 가능해야 한다.
---
## Constitution Rules
Rule 16-1
Workspace Property는 Metadata Field와 1:1 Mapping한다.
Rule 16-2
Workspace 기능 부족으로 Metadata 의미를 제거해서는 안 된다.
---
## Architecture Decision
ADR-042
Workspace Mapping Layer를 공식 채택한다.
---
# Chapter 17
# Notion Database Mapping
## 17.1 Purpose
Notion은 RoRo Product Knowledge Base의 현재 운영 Workspace이다.
본 Chapter는 Metadata Standard를 Notion Database Property로 Mapping하는 방법을 정의한다.
---
## 17.2 Master Document Database
RoRo Notion에서는 하나의 Master Document Database를 운영한다.
모든 공식 Document는 해당 Database의 Item(Page)이다.
---
## 17.3 Required Properties
| Metadata Field | Notion Property | Type |
| --- | --- | --- |
| document_id | Document ID | Text |
| title | Title | Title |
| book | Book | Select |
| domain | Domain | Select |
| category | Category | Select |
| version | Version | Text |
| status | Status | Status |
| owner | Owner | Person |
| created_date | Created Date | Created Time |
| updated_date | Updated Date | Last Edited Time |
---
## 17.4 Relationship Properties
| Metadata Field | Notion Property | Type |
| --- | --- | --- |
| related_documents | Related Docs | Relation |
| related_adr | Related ADR | Relation |
| dependencies | Dependencies | Relation |
---
## 17.5 AI Properties
| Metadata Field | Notion Property | Type |
| --- | --- | --- |
| tags | Tags | Multi-select |
| summary | AI Summary | Text |
| context_scope | Context Scope | Select |
---
# Chapter 18
# Notion Database Architecture
## 18.1 Database Structure
RoRo Notion은 다음 Database 구조를 가진다.
---
## Document Database
역할:
모든 공식 문서 관리
---
## ADR Database
역할:
Architecture Decision 관리
---
## Glossary Database
역할:
용어 관리
---
## Roadmap Database
역할:
Product Evolution 관리
---
## Asset Database
역할:
이미지, 디자인, 자료 관리
---
## 18.2 Relation Model
Document
↓
Related ADR
↓
Decision History
Document
↓
Glossary
↓
Terminology
Document
↓
Asset
↓
Supporting Material
---
## 18.3 Database Rule
동일한 정보를 여러 Database에서 관리하지 않는다.
Source Database를 하나만 가진다.
---
## Constitution Rules
Rule 18-1
Database는 Source of Truth를 명확히 가져야 한다.
Rule 18-2
Relation은 Copy 대신 사용한다.
---
## Architecture Decision
ADR-043
Notion Multi Database Architecture를 채택한다.
---
# Chapter 19
# Notion Template Specification
## 19.1 Purpose
Template은 모든 Document가 동일한 구조로 생성되도록 지원한다.
---
## 19.2 Standard Document Template
모든 Document는 다음 구조를 가진다.
```plain text
Metadata

↓

Purpose

↓

Definition

↓

Principles

↓

Specification

↓

Rules

↓

Examples

↓

References
```
---
## 19.3 Template Types
RoRo는 문서 유형별 Template을 가진다.
---
### Philosophy Template
사용 목적:
Vision, Principle, Constitution
---
### Specification Template
사용 목적:
Standard, Policy, Architecture
---
### Product Template
사용 목적:
PRD, Feature Definition
---
### Design Template
사용 목적:
UX, UI, Design System
---
### Decision Template
사용 목적:
ADR
---
## 19.4 Template Rule
Template은 강제 형식이 아니라 품질 보증 장치이다.
필요한 경우 확장 가능하다.
---
## Architecture Decision
ADR-044
Document Template System을 채택한다.
---
# Chapter 20
# AI Workspace Mapping
## 20.1 Purpose
AI Agent가 RoRo Knowledge Base를 활용하기 위한 Metadata Mapping을 정의한다.
---
## 20.2 AI Retrieval Priority
AI는 다음 순서로 Context를 탐색한다.
```plain text
Document ID

↓

Metadata

↓

Related Documents

↓

References

↓

Content
```
---
## 20.3 AI Context Construction
AI는 다음 요소를 조합한다.
Required Context
- Current Document
- Parent Domain
- Related Documents
Optional Context
- ADR
- Glossary
- Examples
---
## 20.4 AI Safety Rule
AI는 Metadata만으로 Knowledge를 생성하지 않는다.
항상 Source Document를 확인한다.
---
## Constitution Rules
Rule 20-1
AI는 Metadata를 Navigation Layer로 사용한다.
Rule 20-2
Metadata는 Content를 대체하지 않는다.
---
## Architecture Decision
ADR-045
AI Metadata Retrieval Model을 채택한다.
---
## Part IV Summary
Metadata Standard Implementation
```plain text
Standard

↓

Metadata Schema

↓

Notion Properties

↓

Database Relations

↓

AI Retrieval
```
Notion은 현재 RoRo Knowledge Base의 Primary Implementation이다.
그러나 Metadata Standard는 Workspace Independent하다.
---
## Next Part
Part V
Metadata Governance & Validation
# Part V
# Metadata Governance & Validation
---
# Chapter 21
# Metadata Governance Model
## 21.1 Purpose
Metadata Governance는 Metadata의 정확성, 일관성, 지속성을 유지하기 위한 관리 체계이다.
Metadata는 단순 입력 정보가 아니라 Knowledge Base 운영의 핵심 데이터이다.
따라서 생성, 변경, 승인 과정이 관리되어야 한다.
---
## 21.2 Governance Principles
RoRo Metadata Governance는 다음 원칙을 따른다.
---
## Ownership
모든 Metadata는 책임자를 가진다.
---
## Transparency
변경 이력은 추적 가능해야 한다.
---
## Consistency
동일한 규칙을 모든 Document에 적용한다.
---
## Controlled Change
중요 Metadata 변경은 승인 절차를 거친다.
---
## 21.3 Governance Scope
Governance 대상:
- Document ID
- Status
- Version
- Owner
- Domain
- Category
- Relations
- AI Metadata
---
## Constitution Rules
Rule 21-1
Metadata 변경은 추적 가능해야 한다.
Rule 21-2
중요 Identity Metadata는 임의 변경할 수 없다.
---
## Architecture Decision
ADR-046
Metadata Governance Model을 채택한다.
---
# Chapter 22
# Metadata Ownership
## 22.1 Purpose
Metadata Ownership은 각 Field의 책임 주체를 정의한다.
---
## 22.2 Ownership Model
| Category | Owner |
| --- | --- |
| Identity | System / Product Owner |
| Governance | Document Owner |
| Relationship | Author + Reviewer |
| AI Metadata | AI Owner / Document Owner |
---
## 22.3 Field Ownership
### Document ID
System Managed
변경 불가
---
### Title
Document Owner 관리
---
### Status
Reviewer 승인 필요
---
### Owner
Document Owner 지정
---
### Related Documents
Author 관리
---
### AI Metadata
AI 생성 가능
Human Review 필요
---
## Constitution Rules
Rule 22-1
모든 Metadata Field는 Owner를 가진다.
Rule 22-2
Owner 없는 Metadata는 Invalid 상태이다.
---
## Architecture Decision
ADR-047
Metadata Ownership Model을 채택한다.
---
# Chapter 23
# Metadata Change Management
## 23.1 Purpose
Metadata 변경은 Knowledge 구조에 영향을 줄 수 있다.
따라서 변경 유형별 관리 기준을 정의한다.
---
## 23.2 Change Classification
### Level 1
Cosmetic Change
예:
Tag 추가
설명 수정
---
### Level 2
Structural Change
예:
Category 변경
Relation 변경
---
### Level 3
Identity Change
예:
Document ID 변경
Domain 변경
---
## 23.3 Change Rules
Level 1
Owner 승인
---
Level 2
Reviewer 확인
---
Level 3
ADR 필요
---
## 23.4 Forbidden Change
다음 변경은 금지한다.
- Document ID 재사용
- History 삭제
- Reference 관계 삭제 후 기록 없음
---
## Constitution Rules
Rule 23-1
Metadata 변경은 영향도를 고려해야 한다.
Rule 23-2
Identity 변경은 최후의 수단이다.
---
## Architecture Decision
ADR-048
Metadata Change Control Policy를 채택한다.
---
# Chapter 24
# Metadata Validation
## 24.1 Purpose
Metadata Validation은 모든 Document가 Standard를 준수하는지 검증하는 과정이다.
---
## 24.2 Validation Levels
### Level 1
Schema Validation
필수 Field 존재 여부 확인
---
### Level 2
Semantic Validation
값의 의미 검증
예:
Book과 Domain 일치 여부
---
### Level 3
Relationship Validation
Reference 유효성 검증
---
### Level 4
AI Validation
AI Context 품질 검증
---
## 24.3 Validation Checklist
모든 Document는 다음을 확인한다.
□ Document ID 존재
□ Title 존재
□ Owner 지정
□ Status 지정
□ Version 존재
□ Related Documents 확인
□ Broken Reference 없음
□ Tags 존재
---
## Constitution Rules
Rule 24-1
Validation 실패 문서는 Approved 상태가 될 수 없다.
Rule 24-2
Validation 결과는 기록되어야 한다.
---
## Architecture Decision
ADR-049
Metadata Validation Framework를 채택한다.
---
# Chapter 25
# Compliance Model
## 25.1 Purpose
Compliance Model은 Metadata Standard 준수 수준을 평가한다.
---
## 25.2 Compliance Levels
### Level 0
Unmanaged
Metadata 없음
---
### Level 1
Basic
필수 Metadata 존재
---
### Level 2
Structured
Relationship과 Version 관리
---
### Level 3
Governed
Validation 완료
Owner 관리
---
### Level 4
AI Ready
AI Metadata 완성
Context 검색 가능
---
### Level 5
Genome Certified
전체 Architecture 준수
---
## 25.3 Certification Criteria
Genome Certified 문서는:
- Metadata 완성
- Reference 정상
- Validation 통과
- Owner 지정
- AI Context 준비 완료
상태여야 한다.
---
## Architecture Decision
ADR-050
Knowledge Compliance Model을 채택한다.
---
## Part V Summary
Metadata 운영 구조
```plain text
Ownership

↓

Change Control

↓

Validation

↓

Compliance

↓

Certification
```
Metadata는 작성 정보가 아니라
RoRo Knowledge System의 Governance Layer이다.
---
## Next Part
Part VI
Metadata Examples & Implementation Reference
# Part VI
# Metadata Implementation Reference
---
# Chapter 26
# Markdown Metadata Reference
## 26.1 Purpose
RoRo 공식 Markdown Document는 Metadata Header를 통해 문서 Identity와 Governance 정보를 표현한다.
---
## 26.2 Standard Format
Example:
```yaml
---
document_id: DOC-003
title: Metadata Standard

book: Foundation
domain: Documentation
category: Standard

version: 1.0.0
status: Approved

owner: Product Owner

created_date: 2026-07-25
updated_date: 2026-07-25

related_documents:
  - DOC-001
  - DOC-002

related_adr:
  - ADR-031

tags:
  - metadata
  - documentation
  - knowledge

summary:
  Defines the official metadata specification for RoRo Product Genome.

context_scope:
  Global
---
```
---
## 26.3 Required Metadata
다음 Field는 모든 공식 문서에서 필수이다.
```plain text
document_id

title

book

domain

category

version

status

owner
```
---
## 26.4 Optional Metadata
다음 Field는 문서 유형에 따라 선택 가능하다.
```plain text
related_documents

related_adr

dependencies

tags

summary

context_scope
```
---
# Chapter 27
# Notion Implementation Reference
## 27.1 Purpose
Notion은 RoRo Knowledge Base의 Primary Workspace이다.
본 Chapter는 Metadata를 Notion Database로 구현하는 예시를 정의한다.
---
# Master Document Database
## Properties
| Property | Type | Required |
| --- | --- | --- |
| Document ID | Text | Yes |
| Name | Title | Yes |
| Book | Select | Yes |
| Domain | Select | Yes |
| Category | Select | Yes |
| Version | Text | Yes |
| Status | Status | Yes |
| Owner | Person | Yes |
| Created | Created Time | Yes |
| Updated | Last Edited | Yes |
| Related Docs | Relation | Recommended |
| Related ADR | Relation | Recommended |
| Tags | Multi-select | Recommended |
| Summary | Text | Recommended |
| Context Scope | Select | Recommended |
---
## Database Views
RoRo는 다음 View를 운영한다.
---
## All Documents
전체 Knowledge View
---
## By Status
Draft
Review
Approved
Archived
---
## By Domain
Product
Design
Engineering
AI
Business
---
## AI Ready Documents
Context Scope 기준 검색
---
# Chapter 28
# Document Creation Template
## 28.1 Purpose
모든 신규 Document는 아래 Template을 기반으로 생성한다.
---
```plain text
[Metadata]

↓

# Purpose

문서 목적

↓

# Definition

핵심 정의

↓

# Principles

설계 원칙

↓

# Specification

상세 내용

↓

# Rules

강제 규칙

↓

# Examples

사용 사례

↓

# References

관련 문서
```
---
## 28.2 Template Rules
Document 작성자는:
- Metadata 입력
- Purpose 작성
- Reference 연결
- Status 지정
을 완료해야 한다.
---
# Chapter 29
# AI Context Reference
## 29.1 Purpose
AI Agent가 RoRo Knowledge Base를 활용하기 위한 Context 구조를 정의한다.
---
## 29.2 Context Object Example
```json
{
  "document_id": "DOC-003",
  "title": "Metadata Standard",
  "domain": "Documentation",
  "status": "Approved",
  "context_scope": "Global",
  "related_documents": [
    "DOC-001",
    "DOC-002"
  ],
  "priority": "High"
}
```
---
## 29.3 AI Retrieval Rule
AI는 다음 순서로 Context를 구성한다.
```plain text
Current Document

↓

Parent Domain

↓

Related Documents

↓

ADR

↓

Glossary

↓

Examples
```
---
## 29.4 AI Restriction
AI는 Metadata만으로 새로운 사실을 생성하지 않는다.
Metadata는 Navigation 정보이다.
---
# Chapter 30
# Metadata Compliance Checklist
## 30.1 Purpose
모든 공식 Document 승인 전에 Metadata Compliance를 확인한다.
---
# Metadata Checklist
## Identity
□ Document ID 존재
□ Title 존재
□ Book 지정
□ Domain 지정
□ Category 지정
---
## Governance
□ Version 존재
□ Status 지정
□ Owner 지정
□ Created Date 존재
□ Updated Date 존재
---
## Relationship
□ Related Document 검토
□ ADR 연결 확인
□ Broken Reference 없음
---
## AI Readiness
□ Tags 존재
□ Summary 존재
□ Context Scope 지정
---
## Final Approval
□ Validation 완료
□ Reviewer 확인
□ Status Approved 변경
---
# Metadata Standard Final Declaration
RoRo Metadata Standard는
모든 Product Knowledge의 공통 식별 체계이다.
Metadata는 단순한 관리 정보가 아니다.
Metadata는:
- Human Navigation Layer
- AI Context Layer
- Governance Layer
- Knowledge Relationship Layer
를 연결하는 Product Genome의 핵심 구조이다.
모든 RoRo Document는 본 Standard를 따른다.
---
# Document Information
Document ID:
DOC-003
Title:
Metadata Standard
Version:
1.0.0
Status:
Approved
Next Document:
DOC-004 Document Template Standard
