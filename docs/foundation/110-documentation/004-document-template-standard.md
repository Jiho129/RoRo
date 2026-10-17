<!-- Source: Notion page [004_Document_Template_Standard](https://app.notion.com/p/3a8dff1c1f748090978ac0b80c5ab3b8?pvs=204). Page ID: 3a8dff1c-1f74-8090-978a-c0b80c5ab3b8. Path: My Travel - RoRo / 100 📖 Foundation / 110 Documentation. Last edited: 2026-07-25T09:13:48.289Z. -->

# 004_Document_Template_Standard

- template
- documentation
- standard
- writing
---
document_id: DOC-004
title: Document Template Standard
book: Book I - Foundation
domain: Documentation
category: Standard
version: 1.0.0
status: Draft
owner: Product Owner
related_documents:
- DOC-001
- DOC-002
- DOC-003
tags:
- template
- documentation
- standard
- writing
tags:
---
---
# Book I – Foundation
# 004 Document Template Standard
Version 1.0
Status: Draft
---
# Purpose
본 문서는 RoRo Product Genome에서 생성되는 모든 Document의 표준 작성 구조(Document Template)를 정의한다.
Template은 단순한 문서 형식이 아니다.
Template은 Knowledge 생성 품질을 일정하게 유지하기 위한 Architecture이다.
---
# Part I
# Document Template Philosophy
---
# Chapter 1
# Purpose of Template
## 1.1 Definition
Document Template은 Knowledge를 생성하는 표준 방법이다.
동일한 목적의 문서는 동일한 구조를 가져야 한다.
이를 통해:
- 이해 가능성 향상
- 검색 효율 향상
- AI Context 품질 향상
- 유지보수성 향상
을 달성한다.
---
## 1.2 Why Template Exists
문서 작성에서 발생하는 주요 문제:
### Problem 1
작성자마다 구조가 다름
결과:
Knowledge 검색 어려움
---
### Problem 2
중요 내용 누락
결과:
불완전한 Decision 발생
---
### Problem 3
AI Context 불규칙
결과:
AI 활용 품질 저하
---
Template은 이러한 문제를 해결한다.
---
## Constitution Rules
Rule 1-1
공식 Document는 반드시 정의된 Template을 따른다.
Rule 1-2
Template은 품질 보증 장치이다.
---
# Chapter 2
# Template Principles
## 2.1 Structure Before Content
좋은 Document는 좋은 구조에서 시작한다.
내용보다 먼저:
- 목적
- 범위
- 책임
- 관계
를 정의한다.
---
## 2.2 Progressive Disclosure
문서는 단계적으로 이해 가능해야 한다.
구조:
```javascript
Summary
↓
Definition
↓
Principles
↓
Specification
↓
Details
```
---
## 2.3 Separation of Concern
하나의 Document는 하나의 책임만 가진다.
예:
좋지 않은 구조:
```javascript
PRD + UX + Architecture + Marketing
```
좋은 구조:
```javascript
PRD
↓
UX Spec
↓
Architecture Spec
↓
Marketing Plan
```
---
## 2.4 Reference First
같은 내용을 반복 작성하지 않는다.
기존 Knowledge를 Reference한다.
---
## Constitution Rules
Rule 2-1
Document는 하나의 Primary Purpose를 가진다.
Rule 2-2
중복 Content 생성보다 Reference를 우선한다.
---
# Chapter 3
# Standard Document Anatomy
## 3.1 Common Structure
모든 RoRo Document는 기본적으로 다음 구조를 가진다.
```javascript
Metadata
↓
Purpose
↓
Scope
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
## 3.2 Section Responsibility
### Metadata
문서 Identity
---
### Purpose
왜 존재하는가
---
### Scope
무엇을 포함하고 제외하는가
---
### Definition
핵심 개념 정의
---
### Principles
판단 기준
---
### Specification
구체적 요구사항
---
### Rules
강제 조건
---
### Examples
실제 적용 사례
---
### References
관련 Knowledge 연결
---
# Chapter 4
# Document Type Classification
RoRo는 Document를 목적 기준으로 분류한다.
---
## 4.1 Philosophy Document
목적:
Vision과 Principle 정의
Examples:
- Product Philosophy
- Design Philosophy
---
## 4.2 Specification Document
목적:
표준과 요구사항 정의
Examples:
- Metadata Standard
- API Specification
---
## 4.3 Decision Document
목적:
의사결정 기록
Example:
ADR
---
## 4.4 Product Document
목적:
제품 정의
Examples:
- PRD
- Feature Spec
---
## 4.5 Design Document
목적:
Experience 정의
Examples:
- UX Specification
- Design System
---
## 4.6 Research Document
목적:
조사와 분석 기록
Examples:
- Market Research
- User Research
---
# Chapter 5
# Template Governance
## 5.1 Template Ownership
Template은 Foundation 영역에서 관리한다.
변경은 Governance 절차를 따른다.
---
## 5.2 Template Versioning
Template도 Version 관리 대상이다.
Example:
```javascript
Template v1.0
↓
Template v1.1
↓
Template v2.0
```
---
## 5.3 Template Evolution
Template 변경은 다음 조건을 만족해야 한다.
- 새로운 요구사항 발생
- 기존 Template 한계 확인
- Impact Review 완료
---
## Constitution Rules
Rule 5-1
Template 변경은 문서 품질에 영향을 주므로 관리 대상이다.
Rule 5-2
기존 Document와의 Compatibility를 고려한다.
---
## Architecture Decision
ADR-051
Document Template Governance Model을 채택한다.
---
# Part I Summary
Template은 단순한 Formatting Rule이 아니다.
Template은:
- Knowledge 생성 구조
- Quality Control Mechanism
- AI Understanding Framework
이다.
---
# Next Part
Part II
Standard Template Architecture
```javascript
---
#
## Part II
# Standard Template Architecture
### Chapter 6 \~ Chapter 10
```
# Part II
# Standard Template Architecture
---
# Chapter 6
# Common Document Template
## 6.1 Purpose
Common Template은 모든 RoRo Document가 공유하는 기본 구조이다.
모든 Document Type은 Common Template을 기반으로 확장된다.
---
## 6.2 Common Template Structure
모든 공식 문서는 다음 순서를 따른다.
```javascript
1. Metadata
2. Purpose
3. Scope
4. Background
5. Definition
6. Principles
7. Specification
8. Rules
9. Examples
10. References
```
---
# 6.3 Section Specification
---
## Metadata
역할:
Document Identity와 Governance 정보 제공
Reference:
003_Metadata_Standard.md
---
## Purpose
질문:
"왜 이 문서가 존재하는가?"
작성 내용:
- 문제 정의
- 목표
- 기대 결과
---
## Scope
질문:
"이 문서가 다루는 범위는 어디까지인가?"
반드시 포함:
- Included
- Excluded
---
## Background
질문:
"왜 이 결정 또는 정의가 필요한가?"
포함:
- Context
- Previous State
- Problem
---
## Definition
핵심 용어와 개념 정의
주의:
Definition과 Example을 혼합하지 않는다.
---
## Principles
판단 기준 정의
Example:
- User First
- Simplicity
- Scalability
---
## Specification
실제 구현 또는 운영 기준
---
## Rules
반드시 지켜야 하는 조건
---
## Examples
이해를 돕는 실제 사례
---
## References
관련 Document 연결
---
## Constitution Rules
Rule 6-1
모든 Template은 Common Structure를 상속한다.
Rule 6-2
Document Type별 추가 구조는 Common Structure를 삭제할 수 없다.
---
## Architecture Decision
ADR-052
Common Document Template Model을 채택한다.
---
# Chapter 7
# Philosophy Document Template
## 7.1 Purpose
Philosophy Document는 방향성과 원칙을 정의한다.
---
## 7.2 Usage
사용 사례:
- Product Philosophy
- Design Philosophy
- AI Philosophy
- Brand Philosophy
---
## 7.3 Structure
```javascript
Metadata
↓
Purpose
↓
Vision
↓
Core Beliefs
↓
Principles
↓
Decision Criteria
↓
Examples
↓
Anti Patterns
↓
References
```
---
## 7.4 Required Sections
### Vision
우리가 추구하는 미래
---
### Core Beliefs
변하지 않는 믿음
---
### Principles
판단 기준
---
### Decision Criteria
실제 선택 기준
---
### Anti Patterns
하지 않는 것
---
## Example
RoRo Product Philosophy
Question:
"RoRo는 왜 존재하는가?"
---
## Constitution Rules
Rule 7-1
Philosophy는 기능 목록이 아니다.
Rule 7-2
Philosophy는 장기 방향성을 정의한다.
---
## Architecture Decision
ADR-053
Philosophy Template을 채택한다.
---
# Chapter 8
# Specification Document Template
## 8.1 Purpose
Specification Document는 요구사항과 기준을 명확히 정의한다.
---
## 8.2 Usage
Examples:
- Metadata Standard
- API Specification
- Design System Rule
---
## 8.3 Structure
```javascript
Metadata
↓
Purpose
↓
Scope
↓
Definition
↓
Requirements
↓
Specification
↓
Constraints
↓
Validation
↓
Examples
↓
References
```
---
## 8.4 Required Sections
### Requirements
무엇이 필요한가
---
### Specification
어떻게 동작해야 하는가
---
### Constraints
제약 조건
---
### Validation
어떻게 검증하는가
---
## Constitution Rules
Rule 8-1
Specification은 구현 가능한 수준으로 작성한다.
Rule 8-2
모호한 표현을 금지한다.
---
## Architecture Decision
ADR-054
Specification Template을 채택한다.
---
# Chapter 9
# Decision Document Template
## 9.1 Purpose
Decision Document는 중요한 선택과 근거를 기록한다.
대표 문서:
ADR
---
## 9.2 Structure
```javascript
Metadata
↓
Decision Title
↓
Context
↓
Problem
↓
Options
↓
Decision
↓
Rationale
↓
Consequences
↓
Alternatives Considered
↓
References
```
---
## 9.3 Required Sections
### Context
왜 결정이 필요한가
---
### Options
어떤 선택지가 있었는가
---
### Decision
무엇을 선택했는가
---
### Rationale
왜 선택했는가
---
### Consequences
어떤 영향이 발생하는가
---
## Constitution Rules
Rule 9-1
중요 Decision은 반드시 기록한다.
Rule 9-2
결과가 실패해도 Decision History는 유지한다.
---
## Architecture Decision
ADR-055
Decision Document Template을 채택한다.
---
# Chapter 10
# Product Document Template
## 10.1 Purpose
Product Document는 제품 방향과 기능 요구사항을 정의한다.
---
## 10.2 Usage
Examples:
- Product Bible
- PRD
- Feature Specification
---
## 10.3 Structure
```javascript
Metadata
↓
Product Context
↓
Problem
↓
User
↓
Goal
↓
Solution
↓
Feature Specification
↓
User Flow
↓
Success Metrics
↓
Risks
↓
References
```
---
## 10.4 Required Sections
### Problem
사용자 문제가 무엇인가
---
### User
누구를 위한 것인가
---
### Goal
어떤 결과를 원하는가
---
### Solution
어떻게 해결하는가
---
### Metrics
성공 여부 판단 기준
---
## Constitution Rules
Rule 10-1
Feature부터 시작하지 않는다.
Problem에서 시작한다.
---
## Architecture Decision
ADR-056
Product Document Template을 채택한다.
---
# Part II Summary
RoRo Template Architecture:
```javascript
Common Template
↓
Philosophy
↓
Specification
↓
Decision
↓
Product
```
모든 Document Type은 Common Structure를 기반으로 한다.
---
# Next Part
Part III
Design / Research / AI Template Library
```javascript

```
---
document_id: DOC-004-PART-III
parent_document:
	- DOC-004
title: Document Type Template Library
book: Foundation
domain: Documentation
category: Template Standard
version: 1.0.0
status: Draft
owner: Product Owner
created_date: 2026-07-25
related_documents:
	- DOC-001
	- DOC-002
	- DOC-003
	- DOC-004-PART-I
	- DOC-004-PART-II
tags:
	- template
	- document-type
	- prd
	- adr
	- research
	- specification
context_scope:
	Global
summary:
	Defines standard templates for different document types used in RoRo Product Genome.
---
# 004 Document Template Standard
# Part III - Document Type Template Library
Version 1.0.0
Status: Draft
---
# 1. Purpose
본 문서는 RoRo Product Genome에서 사용하는 주요 Document Type별 표준 Template을 정의한다.
모든 Document는 Common Template을 기반으로 하지만, 목적과 책임에 따라 요구되는 사고 구조가 다르다.
예:
- Philosophy Document는 방향성을 정의한다.
- Specification Document는 기준과 요구사항을 정의한다.
- Decision Document는 선택 과정과 근거를 기록한다.
- Product Document는 제품 가치를 정의한다.
- Research Document는 발견과 분석 결과를 저장한다.
따라서 Document 목적에 맞는 Template을 사용해야 한다.
---
# 2. Document Type Classification
RoRo Document는 목적 기준으로 다음 유형으로 분류한다.
| Type | Purpose |
| --- | --- |
| Philosophy Document | 방향성과 원칙 정의 |
| Specification Document | 요구사항과 기준 정의 |
| Decision Document | 의사결정 기록 |
| Product Document | 제품 정의 |
| Design Document | 사용자 경험과 설계 정의 |
| Research Document | 조사와 분석 기록 |
| Operational Document | 운영 기준 정의 |
---
# 3. Philosophy Document Template
## 3.1 Purpose
Philosophy Document는 장기적인 방향성과 판단 기준을 정의한다.
---
## 3.2 Usage
Examples:
- Product Philosophy
- Brand Philosophy
- Design Philosophy
- AI Philosophy
---
## 3.3 Structure
```javascript
Metadata
↓
Purpose
↓
Vision
↓
Beliefs
↓
Principles
↓
Decision Criteria
↓
Anti Patterns
↓
Examples
↓
References
```
---
## 3.4 Required Sections
### Vision
우리가 추구하는 미래 상태를 정의한다.
질문:
"궁극적으로 무엇을 만들고 싶은가?"
---
### Beliefs
변하지 않는 핵심 믿음을 정의한다.
---
### Principles
의사결정 기준을 정의한다.
---
### Decision Criteria
실제 선택 상황에서 적용할 판단 기준을 정의한다.
---
### Anti Patterns
하지 않는 방향을 정의한다.
---
## 3.5 Quality Rules
Rule P-01
Philosophy는 기능 목록이 아니다.
Rule P-02
Philosophy는 단기 목표보다 장기 방향성을 우선한다.
Rule P-03
모든 Principle은 실제 Decision에 적용 가능해야 한다.
---
# 4. Specification Document Template
## 4.1 Purpose
Specification Document는 구현 가능한 기준과 요구사항을 정의한다.
---
## 4.2 Usage
Examples:
- Metadata Standard
- API Specification
- Design System Rule
- Feature Specification
---
## 4.3 Structure
```javascript
Metadata
↓
Purpose
↓
Scope
↓
Definition
↓
Requirements
↓
Specification
↓
Constraints
↓
Validation
↓
Examples
↓
References
```
---
## 4.4 Required Sections
### Requirements
무엇이 필요한지 정의한다.
---
### Specification
어떻게 동작해야 하는지 정의한다.
---
### Constraints
제약 조건을 정의한다.
---
### Validation
검증 방법을 정의한다.
---
## 4.5 Quality Rules
Rule S-01
Specification은 구현 가능한 수준이어야 한다.
Rule S-02
모호한 표현을 최소화한다.
Rule S-03
검증 방법이 존재해야 한다.
---
# 5. Decision Document Template
## 5.1 Purpose
Decision Document는 중요한 선택 과정과 결과를 기록한다.
대표:
ADR
(Architecture Decision Record)
---
## 5.2 Structure
```javascript
Metadata
↓
Context
↓
Problem
↓
Options
↓
Decision
↓
Rationale
↓
Consequences
↓
Alternatives
↓
References
```
---
## 5.3 Required Sections
## Context
왜 결정이 필요한지 설명한다.
---
## Options
검토한 선택지를 기록한다.
---
## Decision
최종 선택을 기록한다.
---
## Rationale
선택 이유를 기록한다.
---
## Consequences
결과와 영향을 기록한다.
---
## Quality Rules
Rule D-01
중요 Decision은 반드시 기록한다.
Rule D-02
선택하지 않은 대안도 기록한다.
Rule D-03
실패한 Decision도 삭제하지 않는다.
---
# 6. Product Document Template
## 6.1 Purpose
Product Document는 제품 가치와 기능 방향을 정의한다.
---
## 6.2 Usage
Examples:
- Product Bible
- PRD
- Feature Requirement
---
## 6.3 Structure
```javascript
Metadata
↓
Product Context
↓
User Problem
↓
Target User
↓
Goal
↓
Solution
↓
Feature Specification
↓
User Flow
↓
Success Metrics
↓
Risks
↓
References
```
---
## 6.4 Required Sections
### User Problem
사용자가 해결해야 하는 문제
---
### Target User
누구를 위한 제품인지
---
### Goal
달성하려는 결과
---
### Solution
해결 방식
---
### Metrics
성공 판단 기준
---
## Quality Rules
Rule PR-01
Feature에서 시작하지 않는다.
Problem에서 시작한다.
Rule PR-02
모든 Feature는 User Value와 연결되어야 한다.
---
# 7. Research Document Template
## 7.1 Purpose
Research Document는 발견 과정과 분석 결과를 저장한다.
---
## 7.2 Structure
```javascript
Metadata
↓
Research Objective
↓
Background
↓
Methodology
↓
Data
↓
Analysis
↓
Insight
↓
Implication
↓
References
```
---
## 7.3 Required Sections
### Objective
무엇을 알아내려 하는가
---
### Methodology
어떻게 조사했는가
---
### Insight
무엇을 발견했는가
---
### Implication
어떤 행동으로 연결되는가
---
## Quality Rules
Rule R-01
Data와 Opinion을 구분한다.
Rule R-02
Insight는 Evidence와 연결한다.
---
# 8. Operational Document Template
## 8.1 Purpose
운영 기준과 반복 업무 방식을 정의한다.
---
## 8.2 Structure
```javascript
Purpose
↓
Scope
↓
Process
↓
Roles
↓
Rules
↓
Checklist
↓
Metrics
↓
References
```
---
## Quality Rules
Rule O-01
운영 문서는 실행 가능해야 한다.
Rule O-02
책임 주체가 명확해야 한다.
---
# 9. Template Selection Rules
Document 작성자는 작성 전에 다음 질문을 확인한다.
---
## Question 1
이 문서는 무엇을 정의하는가?
- 방향성 → Philosophy
- 기준 → Specification
- 결정 → Decision
- 제품 → Product
- 조사 → Research
- 운영 → Operational
---
## Question 2
기존 Document로 대체 가능한가?
가능하다면 신규 Document를 만들지 않는다.
---
## Question 3
Reference 관계가 필요한가?
필요하면 Related Document를 연결한다.
---
# 10. Rules
Rule 10-01
모든 Document는 하나의 Primary Type을 가진다.
Rule 10-02
하나의 Document에서 여러 목적을 혼합하지 않는다.
Rule 10-03
Document Type 변경 시 Version을 증가시킨다.
Rule 10-04
새로운 Type 추가는 Template Governance 절차를 따른다.
---
# 11. References
Related Documents:
- DOC-001 Document Philosophy
- DOC-002 Document Structure
- DOC-003 Metadata Standard
- DOC-004 Part I Template Philosophy
- DOC-004 Part II Standard Template Architecture
---
# Document Information
Document ID:
DOC-004-PART-III
Title:
Document Type Template Library
Version:
1.0.0
Status:
Draft
Next:
DOC-004-PART-IV Product / Design / AI Template
```plain text

```
---
document_id: DOC-004-PART-IV
parent_document:
	- DOC-004
title: Product Design AI Template Standard
book: Foundation
domain: Documentation
category: Template Standard
version: 1.0.0
status: Draft
owner: Product Owner
created_date: 2026-07-25
related_documents:
	- DOC-003
	- DOC-004-PART-II
	- DOC-004-PART-III
tags:
	- product
	- design
	- ai
	- engineering
	- template
context_scope:
	Global
summary:
	Defines templates for product development, design, AI features, and engineering documentation.
---
# 004 Document Template Standard
# Part IV - Product / Design / AI Template
Version 1.0.0
Status: Draft
---
# 1. Purpose
본 문서는 RoRo Product Genome에서 제품 개발 과정에 사용되는 핵심 Document Template을 정의한다.
Product 개발은 하나의 문서로 완성되지 않는다.
하나의 Product는 다음 Knowledge Chain으로 구성된다.
```javascript
Vision
↓
Product Strategy
↓
PRD
↓
UX Design
↓
UI Design
↓
Engineering
↓
Operation
```
각 단계는 서로 다른 목적을 가지며, 목적에 맞는 Document Structure가 필요하다.
---
# 2. Product Development Document System
RoRo Product Development Document는 다음 Layer로 구성한다.
| Layer | Document |
| --- | --- |
| Strategy | Product Philosophy |
| Definition | Product Bible |
| Requirement | PRD |
| Experience | UX Specification |
| Interface | UI Specification |
| Intelligence | AI Feature Specification |
| Implementation | Engineering Specification |
| Operation | Operation Document |
---
# 3. Product Bible Template
## 3.1 Purpose
Product Bible은 Product 전체의 기준이 되는 Single Source of Truth이다.
PRD보다 상위 개념이며, Product의 존재 이유와 방향성을 정의한다.
---
## 3.2 Structure
```javascript
Metadata
↓
Product Vision
↓
Mission
↓
Target User
↓
User Problem
↓
Value Proposition
↓
Core Experience
↓
Product Principle
↓
Feature Map
↓
Roadmap
↓
Success Metric
↓
Reference
```
---
## 3.3 Required Sections
## Product Vision
질문:
"왜 이 제품이 존재하는가?"
---
## Target User
제품이 해결하는 사용자를 정의한다.
포함:
- User Segment
- User Context
- User Need
---
## Value Proposition
사용자가 얻는 핵심 가치를 정의한다.
---
## Product Principle
제품 판단 기준을 정의한다.
예:
- Simple
- Personal
- AI Assisted
- Privacy First
---
## Feature Map
전체 기능 구조를 정의한다.
---
## Roadmap
Product Evolution 방향을 정의한다.
---
## Quality Rules
Rule PB-01
Product Bible은 Feature 목록이 아니다.
Rule PB-02
모든 Feature는 Product Value와 연결되어야 한다.
---
# 4. PRD Template
## 4.1 Purpose
PRD(Product Requirement Document)는 특정 Product Feature의 요구사항을 정의한다.
---
## 4.2 Structure
```javascript
Metadata
↓
Background
↓
Problem Statement
↓
User Definition
↓
Goal
↓
Requirement
↓
User Story
↓
User Flow
↓
Acceptance Criteria
↓
Success Metrics
↓
Risk
↓
Reference
```
---
# 4.3 Required Sections
## Problem Statement
해결하려는 문제를 정의한다.
---
## User Story
사용자 관점 행동을 정의한다.
Format:
```javascript
As a User
I want
So that
```
---
## Requirement
필요 기능을 정의한다.
---
## Acceptance Criteria
완료 기준을 정의한다.
---
## Success Metrics
성과 판단 기준을 정의한다.
---
## Quality Rules
Rule PRD-01
PRD는 Solution보다 Problem에서 시작한다.
Rule PRD-02
Requirement는 검증 가능해야 한다.
---
# 5. Feature Specification Template
## 5.1 Purpose
Feature 단위 상세 설계를 정의한다.
---
## Structure
```javascript
Metadata
↓
Feature Overview
↓
Purpose
↓
User Scenario
↓
Functional Requirement
↓
Non Functional Requirement
↓
Interaction
↓
Edge Case
↓
Validation
```
---
## Required Sections
### Functional Requirement
기능 동작 정의
---
### Non Functional Requirement
성능, 보안, 안정성 정의
---
### Edge Case
예외 상황 정의
---
## Quality Rules
Rule FS-01
Feature는 User Value와 연결되어야 한다.
---
# 6. UX Specification Template
## 6.1 Purpose
사용자 경험 설계 기준을 정의한다.
---
## Structure
```javascript
Metadata
↓
UX Goal
↓
User Journey
↓
User Flow
↓
Information Architecture
↓
Interaction Design
↓
Usability Rule
↓
Validation
```
---
## Required Sections
## User Journey
사용자의 전체 경험 흐름
---
## User Flow
Task 수행 과정
---
## Information Architecture
정보 구조
---
## Interaction Design
사용자 행동과 시스템 반응
---
## Quality Rules
Rule UX-01
UX는 기능 Flow가 아니라 Experience Flow를 정의한다.
---
# 7. UI Specification Template
## 7.1 Purpose
화면과 Component 기준을 정의한다.
---
## Structure
```javascript
Metadata
↓
Screen Purpose
↓
Layout
↓
Component
↓
Interaction
↓
State
↓
Responsive Rule
↓
Design Reference
```
---
## Required Sections
### Component
UI 구성 요소 정의
---
### State
상태 변화 정의
예:
- Empty
- Loading
- Error
- Complete
---
### Design Reference
Figma 연결
---
## Quality Rules
Rule UI-01
UI Specification은 Figma와 연결 가능해야 한다.
---
# 8. AI Feature Specification Template
## 8.1 Purpose
AI 기능의 목적과 동작 기준을 정의한다.
---
## Structure
```javascript
Metadata
↓
AI Goal
↓
User Problem
↓
AI Capability
↓
Input
↓
Processing Logic
↓
Output
↓
Evaluation
↓
Safety Rule
```
---
## Required Sections
## AI Goal
AI가 해결해야 하는 문제
---
## Input
AI가 사용하는 데이터
---
## Output
사용자가 받는 결과
---
## Evaluation
품질 평가 기준
---
## Safety Rule
제한 조건
---
## Quality Rules
Rule AI-01
AI Feature는 AI 기술보다 User Value 중심으로 정의한다.
Rule AI-02
AI 결과는 평가 기준을 가져야 한다.
---
# 9. Engineering Specification Template
## 9.1 Purpose
구현 구조와 기술 기준을 정의한다.
---
## Structure
```javascript
Metadata
↓
Architecture Overview
↓
Component
↓
Data Flow
↓
API
↓
Technology
↓
Security
↓
Performance
↓
Testing
```
---
## Required Sections
### Architecture Overview
전체 구조
---
### Data Flow
데이터 흐름
---
### API
Interface 정의
---
### Testing
검증 방법
---
## Quality Rules
Rule ENG-01
Architecture Decision은 ADR과 연결한다.
Rule ENG-02
Implementation은 Specification을 따라야 한다.
---
# 10. Template Relationship Model
Product 개발 문서 관계:
```javascript
Product Bible
↓
PRD
↓
Feature Specification
↓
UX Specification
↓
UI Specification
↓
Engineering Specification
↓
Operation Document
```
AI Feature:
```javascript
PRD
↓
AI Feature Specification
↓
Engineering Specification
```
---
# 11. Rules
Rule 11-01
Product Document는 Product Bible 방향성을 준수한다.
Rule 11-02
PRD는 User Problem 기반으로 작성한다.
Rule 11-03
Design Document는 Figma Reference를 가진다.
Rule 11-04
AI Document는 Evaluation 기준을 가진다.
Rule 11-05
Engineering Document는 ADR과 연결한다.
---
# 12. References
Related Documents:
- DOC-003 Metadata Standard
- DOC-004-PART-II Standard Template Architecture
- DOC-004-PART-III Document Type Template Library
---
# Document Information
Document ID:
DOC-004-PART-IV
Title:
Product / Design / AI Template Standard
Version:
1.0.0
Status:
Draft
Next:
DOC-004-PART-V Template Governance
```javascript

```
---
document_id: DOC-004-PART-V
parent_document:
	- DOC-004
title: Template Governance Standard
book: Foundation
domain: Documentation
category: Template Standard
version: 1.0.0
status: Draft
owner: Product Owner
created_date: 2026-07-25
related_documents:
	- DOC-001
	- DOC-002
	- DOC-003
	- DOC-004-PART-I
	- DOC-004-PART-II
	- DOC-004-PART-III
	- DOC-004-PART-IV
tags:
	- governance
	- template-management
	- version-control
	- quality
context_scope:
	Global
summary:
	Defines governance rules for maintaining, evolving, and controlling RoRo document templates.
---
# 004 Document Template Standard
# Part V - Template Governance
Version 1.0.0
Status: Draft
---
# 1. Purpose
본 문서는 RoRo Document Template을 지속적으로 관리하기 위한 Governance 기준을 정의한다.
Template은 한번 만들어지고 끝나는 정적 문서가 아니다.
Product와 Organization이 변화함에 따라 Template도 지속적으로 발전해야 한다.
그러나 무분별한 변경은:
- 기존 Document 호환성 문제
- Knowledge 구조 혼란
- AI Context 품질 저하
를 발생시킬 수 있다.
따라서 Template 변경은 명확한 Ownership과 Version Control을 기반으로 관리한다.
---
# 2. Template Governance Philosophy
## 2.1 Template Is Product Infrastructure
RoRo에서 Template은 단순 문서 양식이 아니다.
Template은 다음 역할을 수행한다.
```javascript
Knowledge Infrastructure
-
AI Context Infrastructure
-
Product Development Infrastructure
```
따라서 Template 변경은 Product Architecture 변경과 동일한 수준으로 관리한다.
---
# 2.2 Stability Before Change
Template은 자주 변경하지 않는다.
변경 목적은:
- 더 좋은 Knowledge 생성
- 명확한 Communication
- AI 활용 개선
이어야 한다.
단순한 개인 선호나 작성 편의를 위한 변경은 제한한다.
---
# 2.3 Evolution Over Replacement
기존 Template을 무조건 폐기하지 않는다.
변경 시:
```javascript
Current Version
↓
Improvement Proposal
↓
Impact Review
↓
New Version
↓
Migration
```
절차를 따른다.
---
# 3. Template Ownership
## 3.1 Owner Responsibility
모든 Template은 Owner를 가진다.
Owner의 책임:
- Template 품질 관리
- 변경 요청 검토
- Version 관리
- 사용자 Feedback 반영
- Compliance 확인
---
## 3.2 Ownership Model
| Area | Owner |
| --- | --- |
| Foundation Template | Documentation Owner |
| Product Template | Product Owner |
| Design Template | Design Owner |
| Engineering Template | Engineering Owner |
| AI Template | AI Product Owner |
---
# 4. Template Version Management
## 4.1 Version Rule
Template은 Semantic Versioning을 따른다.
Format:
```javascript
Major.Minor.Patch
```
Example:
```javascript
1.0.0
```
---
# 4.2 Major Version
Major 변경:
구조 자체가 변경되는 경우
Example:
Before:
```javascript
Problem
↓
Solution
```
After:
```javascript
Context
↓
Problem
↓
Decision
↓
Solution
```
Impact:
기존 Document Migration 필요
---
# 4.3 Minor Version
Minor 변경:
Section 추가 또는 개선
Example:
추가:
```javascript
Risk Assessment
```
기존 구조 유지
---
# 4.4 Patch Version
Patch 변경:
오류 수정
Example:
- Typo 수정
- 설명 명확화
- Example 추가
---
# 5. Template Change Process
## 5.1 Change Request
Template 변경은 Change Request로 시작한다.
필수 정보:
```javascript
Change Reason
↓
Problem
↓
Expected Benefit
↓
Impact
↓
Migration Plan
```
---
# 5.2 Review Process
변경 검토 단계:
```javascript
Request
↓
Owner Review
↓
Impact Analysis
↓
Approval
↓
Version Update
↓
Release
```
---
# 5.3 Impact Analysis
검토 항목:
## Existing Documents
기존 문서 영향
---
## Users
작성자 영향
---
## AI System
Retrieval 영향
---
## Related Templates
연관 Template 영향
---
# 6. Template Lifecycle
Template Life Cycle:
```javascript
Idea
↓
Draft
↓
Review
↓
Approved
↓
Active
↓
Deprecated
↓
Archived
```
---
# 6.1 Draft
아직 공식 사용하지 않는 상태
---
# 6.2 Approved
공식 Template
사용 가능
---
# 6.3 Active
현재 권장 Version
---
# 6.4 Deprecated
새 문서 사용 금지
기존 문서 유지 목적
---
# 6.5 Archived
역사 기록용
---
# 7. Template Compliance
## 7.1 Purpose
Document가 적절한 Template을 사용하는지 검증한다.
---
## 7.2 Compliance Checklist
### Structure
□ Required Section 존재
□ 순서 준수
□ Metadata 포함
---
### Content
□ Purpose 명확
□ Reference 연결
□ Validation 존재
---
### Governance
□ Version 확인
□ Status 확인
□ Owner 지정
---
# 8. Legacy Document Migration
## 8.1 Purpose
기존 Document를 신규 Template 구조로 전환한다.
---
## 8.2 Migration Principle
모든 Legacy Document를 즉시 변환하지 않는다.
Priority:
```javascript
High Value Document
↓
Frequently Used Document
↓
Reference Document
↓
Archive
```
---
# 8.3 Migration Process
```javascript
Identify
↓
Classify
↓
Map Section
↓
Update Metadata
↓
Review
↓
Approve
```
---
# 9. Template Metrics
Template 품질은 다음 Metric으로 관리한다.
---
## Adoption Rate
Template 사용 비율
---
## Completion Rate
필수 Section 작성률
---
## Reuse Rate
Reference 활용률
---
## Quality Feedback
사용자 만족도
---
## AI Retrieval Quality
AI Context 활용 정확도
---
# 10. Rules
## Rule TG-01
모든 Template은 Owner를 가진다.
---
## Rule TG-02
Template 변경은 Version 관리한다.
---
## Rule TG-03
Major 변경은 Impact Review를 수행한다.
---
## Rule TG-04
Deprecated Template은 신규 Document에 사용하지 않는다.
---
## Rule TG-05
Template Governance는 Knowledge Governance의 일부이다.
---
# 11. References
Related Documents:
- DOC-003 Metadata Standard
- DOC-004-PART-I Template Philosophy
- DOC-004-PART-II Standard Template Architecture
- DOC-004-PART-III Document Type Template Library
- DOC-004-PART-IV Product / Design / AI Template
---
# Document Information
Document ID:
DOC-004-PART-V
Title:
Template Governance Standard
Version:
1.0.0
Status:
Draft
Next:
DOC-004-PART-VI Template Examples & Validation
```javascript

```
---
document_id: DOC-004-PART-VI
parent_document:
	- DOC-004
title: Template Examples & Validation
book: Foundation
domain: Documentation
category: Template Standard
version: 1.0.0
status: Draft
owner: Product Owner
created_date: 2026-07-25
related_documents:
	- DOC-004-PART-I
	- DOC-004-PART-II
	- DOC-004-PART-III
	- DOC-004-PART-IV
	- DOC-004-PART-V
tags:
	- template
	- validation
	- example
	- quality
context_scope:
	Global
summary:
	Defines practical examples and validation methods for RoRo document templates.
---
# 004 Document Template Standard
# Part VI - Template Examples & Validation
Version 1.0.0
Status: Draft
---
# 1. Purpose
본 문서는 RoRo Document Template이 실제 Product Development 과정에서 어떻게 적용되는지 Example과 Validation 기준을 정의한다.
Template은 이론적인 구조가 아니라 실제 업무에서 사용되어야 한다.
따라서 다음을 검증한다.
- Template 구조가 실제 문제 해결에 적합한가
- 필요한 정보가 누락되지 않는가
- Human과 AI 모두 이해 가능한가
- Knowledge 연결이 가능한가
---
# 2. Template Application Model
RoRo Document 생성 과정은 다음 Flow를 따른다.
```javascript
Problem
↓
Document Type Selection
↓
Template Selection
↓
Content Creation
↓
Review
↓
Approval
↓
Knowledge Connection
```
---
# 3. Product Bible Example
## 3.1 Scenario
Example:
RoRo Travel Memory Platform 정의
---
## 3.2 Applied Template
Document Type:
Product Document
Template:
Product Bible
---
## 3.3 Structure Example
```javascript
Product Vision
↓
User Problem
↓
Target User
↓
Value Proposition
↓
Core Experience
↓
Feature Map
↓
Roadmap
↓
Success Metric
```
---
## 3.4 Quality Validation
Check:
□ Product 존재 이유가 명확한가
□ Target User가 정의되어 있는가
□ Feature가 Value와 연결되어 있는가
□ 장기 방향성이 존재하는가
---
# 4. PRD Example
## 4.1 Scenario
Feature:
AI Travel Diary Generation
---
## 4.2 Applied Template
Document Type:
Product Document
Sub Type:
PRD
---
## 4.3 Structure Example
```javascript
Problem
↓
User
↓
Goal
↓
Requirement
↓
User Story
↓
Acceptance Criteria
↓
Metric
```
---
## 4.4 Example User Story
```javascript
As a traveler,
I want AI to organize my travel photos,
So that I can preserve meaningful memories without manual effort.
```
---
## 4.5 Validation
Check:
□ User Problem 존재
□ User Value 설명 가능
□ Requirement 검증 가능
□ Success Metric 존재
---
# 5. ADR Example
## 5.1 Scenario
Decision:
Photo Auto Upload 방식 결정
---
## 5.2 Applied Template
Document Type:
Decision Document
---
## 5.3 Structure
```javascript
Context
↓
Problem
↓
Options
↓
Decision
↓
Rationale
↓
Consequences
```
---
## 5.4 Example
Options:
Option A:
Automatic Background Upload
Option B:
User Selected Upload
Option C:
Hybrid Recommendation
Decision:
Hybrid Model 선택
---
## Validation
Check:
□ Alternative 존재
□ Decision Reason 존재
□ Impact 기록
---
# 6. UX Specification Example
## 6.1 Scenario
Travel Dashboard Design
---
## 6.2 Applied Template
Document Type:
Design Document
---
## 6.3 Structure
```javascript
UX Goal
↓
User Journey
↓
Flow
↓
Interaction
↓
State
↓
Validation
```
---
## 6.4 Validation
Check:
□ User Goal 연결
□ Flow Complete
□ Error State 정의
□ Empty State 정의
---
# 7. AI Feature Specification Example
## 7.1 Scenario
AI Highlight Video Generation
---
## 7.2 Applied Template
Document Type:
AI Feature Specification
---
## 7.3 Structure
```javascript
AI Goal
↓
Input
↓
Processing
↓
Output
↓
Evaluation
↓
Safety Rule
```
---
## 7.4 Example
Input:
- Photos
- Location
- Timeline
- User Preference
Processing:
- Image Understanding
- Scene Classification
- Story Generation
Output:
- 1 minute Highlight Video
---
## Validation
Check:
□ Input 정의
□ Output 정의
□ Quality Metric 존재
□ Safety Rule 존재
---
# 8. Engineering Specification Example
## 8.1 Scenario
AI Diary Backend Architecture
---
## Structure
```javascript
Architecture
↓
Component
↓
Data Flow
↓
API
↓
Security
↓
Testing
```
---
## Validation
Check:
□ Architecture 설명 가능
□ Data Flow 존재
□ Security 고려
□ Test 방법 존재
---
# 9. Template Validation Framework
## 9.1 Purpose
모든 Document는 승인 전에 Validation을 수행한다.
---
# 9.2 Structural Validation
검증 항목:
```javascript
Metadata Exists
Required Section Exists
Reference Connected
Version Defined
```
---
# 9.3 Content Validation
검증 항목:
```javascript
Purpose Clear
Problem Defined
Decision Explained
Example Included
```
---
# 9.4 Knowledge Validation
검증 항목:
```javascript
Related Document Connected
Duplicate Content Avoided
AI Context Ready
```
---
# 10. Document Quality Score
RoRo Document Quality는 다음 기준으로 평가한다.
---
## Level 1 - Basic
조건:
- Template 사용
- Metadata 존재
---
## Level 2 - Structured
조건:
- Required Section 작성
- Reference 연결
---
## Level 3 - Knowledge Ready
조건:
- Decision Context 존재
- Example 존재
- AI Retrieval 가능
---
## Level 4 - Product Genome Ready
조건:
- Related Knowledge 연결
- Continuous Update
- Reusable Knowledge 생성
---
# 11. Final Template Declaration
RoRo Document Template Standard는 다음 원칙을 선언한다.
---
## Principle 1
Document는 기록이 아니라 Knowledge Asset이다.
---
## Principle 2
Template은 작성 형식이 아니라 사고 구조이다.
---
## Principle 3
모든 Document는 Purpose와 Context를 가진다.
---
## Principle 4
모든 Knowledge는 Relationship을 가진다.
---
## Principle 5
Human과 AI가 함께 사용할 수 있는 구조를 유지한다.
---
# 12. Rules
Rule TV-01
모든 공식 Document는 Template Validation을 통과해야 한다.
---
Rule TV-02
Example 없는 Template은 개선 대상이다.
---
Rule TV-03
Template은 실제 Product Development와 연결되어야 한다.
---
Rule TV-04
Knowledge Quality가 Template Design의 최우선 기준이다.
---
# 13. References
Related Documents:
- DOC-001 Document Philosophy
- DOC-002 Document Structure
- DOC-003 Metadata Standard
- DOC-004-PART-I Template Philosophy
- DOC-004-PART-II Standard Template Architecture
- DOC-004-PART-III Document Type Template Library
- DOC-004-PART-IV Product / Design / AI Template
- DOC-004-PART-V Template Governance
---
# Document Information
Document ID:
DOC-004-PART-VI
Title:
Template Examples & Validation
Version:
1.0.0
Status:
Draft
---
# DOC-004 Document Template Standard
Status:
Completed
Next:
DOC-005 Knowledge Management Standard
