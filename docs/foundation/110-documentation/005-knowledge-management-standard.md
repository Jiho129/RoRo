<!-- Source: Notion page [005 Knowledge Management Standard](https://app.notion.com/p/3a8dff1c1f7480adb26febb6b0c1c7b8?pvs=204). Page ID: 3a8dff1c-1f74-80ad-b26f-ebb6b0c1c7b8. Path: My Travel - RoRo / 100 📖 Foundation / 110 Documentation. Last edited: 2026-07-26T05:54:00.231Z. -->

# 005 Knowledge Management Standard

---
document_id: DOC-005-PART-I
parent_document:
- DOC-005
title: Knowledge Management Philosophy
book: Foundation
domain: Knowledge Management
category: Standard
version: 1.0.0
status: Draft
owner: Product Owner
created_date: 2026-07-25
related_documents:
- DOC-001
- DOC-002
- DOC-003
- DOC-004
tags:
- knowledge-management
- product-genome
- knowledge-system
- philosophy
context_scope:
Global
## summary:
Defines the philosophy and fundamental principles of RoRo Knowledge Management System.
# 005 Knowledge Management Standard
# Part I - Knowledge Management Philosophy
Version 1.0.0
Status: Draft
---
# 1. Purpose
본 문서는 RoRo Product Genome에서 Knowledge를 어떻게 정의하고 관리하는지에 대한 근본 철학을 정의한다.
RoRo에서 Knowledge는 단순한 정보 저장물이 아니다.
Knowledge는 Product가 성장하는 과정에서 생성되는 사고와 경험의 집합이며, 다음 요소를 포함한다.
- Product 방향성
- User Understanding
- Business Decision
- Design Intent
- Technical Solution
- Operational Experience
따라서 Knowledge Management의 목적은 정보를 보관하는 것이 아니다.
목적은 다음과 같다.
```plain text
Information

↓

Context

↓

Understanding

↓

Decision

↓

Reusable Knowledge
```
즉, 조직과 AI가 반복적으로 활용 가능한 Knowledge System을 구축하는 것이다.
---
# 2. Knowledge Definition
## 2.1 Definition of Knowledge
RoRo에서는 다음 조건을 만족하는 정보를 Knowledge라고 정의한다.
```plain text
Information

+

Context

+

Relationship

+

Experience

=

Knowledge
```
---
## Information
관찰된 사실이나 데이터이다.
Example:
```plain text
User uploaded 100 photos during travel.
```
---
## Context
왜 해당 정보가 중요한지 설명하는 배경이다.
Example:
```plain text
User wants to preserve meaningful memories
but does not want manual organization effort.
```
---
## Relationship
다른 Knowledge와 연결되는 구조이다.
Example:
```plain text
User Research

↓

PRD

↓

UX Design

↓

Feature Implementation
```
---
## Experience
실제 실행 과정에서 축적된 경험이다.
Example:
- 성공 사례
- 실패 사례
- Decision History
- Operational Learning
---
# 3. Why Knowledge Management Exists
## 3.1 Information Explosion Problem
Product 개발 과정에서는 지속적으로 많은 정보가 생성된다.
Examples:
- Meeting Notes
- Customer Feedback
- Research Data
- Design Files
- Requirements
- Technical Documents
- Code Repository
하지만 정보의 양이 증가한다고 Knowledge가 증가하는 것은 아니다.
---
## Problem
```plain text
많은 정보

↓

낮은 연결성

↓

검색 어려움

↓

동일한 문제 반복 해결
```
---
## Solution
Knowledge Management는 정보를 구조화하고 연결하여 재사용 가능한 자산으로 만든다.
---
# 4. Knowledge Loss Problem
## 4.1 Decision Context Loss
조직에서 가장 중요한 Knowledge는 결과가 아니라 Decision Context이다.
시간이 지나면 다음 질문에 답하기 어려워진다.
```plain text
왜 이 Feature를 만들었는가?

왜 이 방향을 선택했는가?

왜 다른 방법을 버렸는가?

어떤 가정을 기반으로 결정했는가?
```
---
RoRo Knowledge Management는 결과뿐 아니라 판단 과정을 보존한다.
---
# 5. RoRo Knowledge Management Philosophy
---
# Principle 1
# Knowledge Is A Product Asset
Knowledge는 Product의 핵심 자산이다.
Product Asset:
```plain text
Code

+

Design

+

Data

+

Knowledge
```
---
좋은 Product는 좋은 Code만으로 만들어지지 않는다.
좋은 Product는 축적된 Knowledge를 기반으로 Evolution한다.
---
# Principle 2
# Context Is More Valuable Than Data
Data 자체보다 Context가 중요하다.
Example:
## Data
```plain text
10,000 travel photos uploaded
```
---
## Context
```plain text
Family travelers want to preserve emotional memories,
but organizing photos requires too much effort.
```
---
Data는 현상을 보여준다.
Context는 문제와 방향을 설명한다.
---
# Principle 3
# Knowledge Must Be Connected
Knowledge는 독립적인 문서가 아니다.
하나의 Knowledge Graph를 구성하는 Node이다.
Structure:
```plain text
Knowledge Node

↓

Relationship

↓

Knowledge Graph
```
---
Example:
```plain text
User Interview

↓

User Insight

↓

Product Requirement

↓

Feature

↓

Design

↓

Implementation
```
---
# Principle 4
# Knowledge Must Be Reusable
한 번 생성된 Knowledge는 반복 활용되어야 한다.
Example:
```plain text
User Research

↓

Product Strategy

↓

PRD

↓

UX Design

↓

Marketing Message
```
---
Knowledge의 가치는 저장 횟수가 아니라 활용 횟수로 판단한다.
---
# Principle 5
# Knowledge Must Be AI Ready
RoRo Product Genome은 Human과 AI가 함께 사용하는 Knowledge System이다.
따라서 Knowledge는 다음 조건을 만족해야 한다.
- Structured
- Searchable
- Connected
- Contextual
---
# 6. Knowledge Management Model
RoRo Knowledge Management는 다음 Layer로 구성된다.
```plain text
Knowledge Philosophy

↓

Knowledge Architecture

↓

Knowledge Repository

↓

Knowledge Relationship

↓

Knowledge Governance

↓

AI Utilization
```
---
# 6.1 Philosophy Layer
질문:
```plain text
Why do we manage Knowledge?
```
정의:
DOC-005 Part I
---
# 6.2 Architecture Layer
질문:
```plain text
How is Knowledge structured?
```
정의:
DOC-005 Part II
---
# 6.3 Repository Layer
질문:
```plain text
Where is Knowledge stored?
```
Examples:
- Notion
- GitHub
- Figma
- Cloud Storage
---
# 6.4 Relationship Layer
질문:
```plain text
How is Knowledge connected?
```
Example:
```plain text
PRD

↓

UX Specification

↓

Figma

↓

Engineering
```
---
# 6.5 Governance Layer
질문:
```plain text
How is Knowledge maintained?
```
---
# 7. Knowledge vs Document
## 7.1 Document
Document는 Knowledge를 표현하는 형태이다.
---
## 7.2 Knowledge
Knowledge는 Document 안에 존재하는 의미이다.
---
Relationship:
```plain text
Knowledge

↓

expressed through

↓

Document
```
---
따라서:
모든 Document는 Knowledge를 포함한다.
하지만 모든 Knowledge가 하나의 Document에 제한되는 것은 아니다.
---
# 8. Knowledge Creation Principle
Knowledge 생성 과정:
```plain text
Experience

↓

Observation

↓

Information

↓

Analysis

↓

Insight

↓

Decision

↓

Knowledge
```
---
좋은 Knowledge는 단순 기록이 아니다.
사고 과정과 판단 결과가 포함되어야 한다.
---
# 9. Knowledge Anti Pattern
## 9.1 Storage First
문제:
"일단 저장한다."
결과:
Data Dump 발생
---
## 9.2 Document Island
문제:
문서가 서로 연결되지 않는다.
결과:
Knowledge Graph 형성 실패
---
## 9.3 Context Loss
문제:
결과만 기록한다.
결과:
Decision 재현 불가능
---
## 9.4 Duplicate Knowledge
문제:
동일한 Knowledge가 여러 위치에 존재한다.
결과:
Single Source of Truth 실패
---
# 10. Knowledge Management Rules
## Rule KM-01
Knowledge는 Context를 포함해야 한다.
---
## Rule KM-02
공식 Knowledge는 Relationship을 가져야 한다.
---
## Rule KM-03
Duplicate보다 Reference를 우선한다.
---
## Rule KM-04
Knowledge는 Human과 AI 모두 사용할 수 있어야 한다.
---
## Rule KM-05
Knowledge는 지속적으로 Evolution해야 한다.
---
# 11. References
Related Documents:
- DOC-001 Document Philosophy
- DOC-002 Document Structure
- DOC-003 Metadata Standard
- DOC-004 Document Template Standard
---
# Document Information
Document ID:
DOC-005-PART-I
Title:
Knowledge Management Philosophy
Version:
1.0.0
Status:
Draft
Next:
DOC-005-PART-II Knowledge Architecture
---
document_id: DOC-005-PART-II
parent_document:
- DOC-005
title: Knowledge Architecture
book: Foundation
domain: Knowledge Management
category: Standard
version: 1.0.0
status: Draft
owner: Product Owner
created_date: 2026-07-25
related_documents:
- DOC-001
- DOC-002
- DOC-003
- DOC-004
- DOC-005-PART-I
tags:
- knowledge-architecture
- repository
- notion
- github
- figma
- ai
context_scope:
Global
## summary:
Defines the architecture, layers, repositories and storage principles of the RoRo Knowledge Management System.
# 005 Knowledge Management Standard
# Part II - Knowledge Architecture
Version 1.0.0
Status: Draft
---
# 1. Purpose
본 문서는 RoRo Product Genome을 구성하는 Knowledge Architecture를 정의한다.
Knowledge Architecture는 단순한 폴더 구조나 파일 관리 규칙이 아니다.
Knowledge가 생성되고, 저장되고, 연결되고, 활용되는 전체 구조를 정의하는 시스템이다.
RoRo에서는 모든 Product Development 활동을 하나의 Knowledge Network로 관리한다.
---
# 2. Architecture Philosophy
Knowledge Architecture는 다음 목표를 가진다.
- Knowledge를 잃지 않는다.
- 같은 내용을 두 번 작성하지 않는다.
- 필요한 정보를 1분 이내에 찾을 수 있다.
- Human과 AI가 동일한 Knowledge를 활용한다.
- Product가 성장할수록 Knowledge도 함께 성장한다.
---
# 3. Architecture Overview
RoRo Knowledge Architecture는 6개의 Layer로 구성된다.
```plain text
Knowledge Layer

↓

Document Layer

↓

Asset Layer

↓

Repository Layer

↓

Relationship Layer

↓

Retrieval Layer
```
각 Layer는 독립적으로 존재하지 않는다.
모든 Layer는 상호 연결되어 하나의 Product Genome을 형성한다.
---
# 4. Knowledge Layer
## 4.1 Definition
Knowledge Layer는 Product에서 가장 상위 개념이다.
이 Layer에는 사고와 의사결정이 존재한다.
예시
- Product Vision
- Product Philosophy
- User Insight
- Business Strategy
- Design Principle
- Engineering Principle
- AI Principle
---
## 4.2 Characteristics
Knowledge Layer는 다음 특징을 가진다.
- 가장 오래 유지된다.
- 가장 자주 참조된다.
- 다른 모든 Layer의 기준이 된다.
- 변경 빈도가 가장 낮다.
---
# 5. Document Layer
## 5.1 Definition
Knowledge를 표현하는 문서 계층이다.
Knowledge는 반드시 Document를 통해 표현된다.
Examples
- Product Bible
- PRD
- UX Specification
- Architecture Decision Record
- Research Report
- Technical Specification
---
## 5.2 Principle
Knowledge는 Document를 통해 관리하지만,
Knowledge ≠ Document
Document는 Knowledge를 담는 Container이다.
---
# 6. Asset Layer
## 6.1 Definition
실제 산출물을 저장하는 계층이다.
Examples
- Figma Design
- Source Code
- Images
- Videos
- Meeting Recording
- PDF
- Presentation
- Spreadsheet
---
## 6.2 Asset Characteristics
Asset는 Document의 근거(Evidence)이다.
예시
```plain text
PRD

↓

UX Specification

↓

Figma File

↓

Prototype

↓

Implementation
```
Document는 Asset를 설명하고,
Asset는 Document를 증명한다.
---
# 7. Repository Layer
Repository는 Knowledge가 저장되는 물리적 공간이다.
RoRo는 Repository를 역할에 따라 구분한다.
---
## 7.1 Notion
Purpose
Knowledge Repository
저장 대상
- Philosophy
- Product Bible
- PRD
- Research
- Decision
- Meeting
- Roadmap
Notion은 Product Brain이다.
---
## 7.2 GitHub
Purpose
Engineering Repository
저장 대상
- Source Code
- API
- ADR
- Release Note
- Technical Documentation
GitHub는 Product Implementation Repository이다.
---
## 7.3 Figma
Purpose
Design Repository
저장 대상
- Wireframe
- User Flow
- UI Design
- Component
- Prototype
- Design System
Figma는 Product Experience Repository이다.
---
## 7.4 Cloud Storage
Purpose
Large Asset Repository
Examples
- Original Images
- Videos
- Backup Files
- Dataset
---
# 8. Relationship Layer
Repository가 분리되어 있어도 Knowledge는 하나여야 한다.
Relationship Layer는 이를 연결한다.
Example
```plain text
Product Bible

↓

PRD

↓

UX Specification

↓

Figma Frame

↓

Engineering Task

↓

Release
```
모든 연결은 Reference 기반으로 관리한다.
---
# 9. Knowledge Object
RoRo에서는 모든 Knowledge를 Object로 정의한다.
Knowledge Object는 다음 속성을 가진다.
```plain text
Identifier

Title

Type

Owner

Status

Version

Reference

Lifecycle
```
Knowledge Object는 사람이 읽는 문서이면서 AI가 이해하는 Node이다.
---
# 10. Knowledge Hierarchy
RoRo Product Genome의 기본 계층 구조는 다음과 같다.
```plain text
Foundation

↓

Product

↓

Feature

↓

Task

↓

Asset
```
---
## Foundation
모든 프로젝트가 공유하는 원칙
Examples
- Philosophy
- Standard
- Governance
---
## Product
제품 단위 Knowledge
Examples
- Product Bible
- Roadmap
- Strategy
---
## Feature
기능 단위 Knowledge
Examples
- PRD
- UX
- UI
- AI Spec
---
## Task
실행 단위
Examples
- Sprint
- Issue
- Ticket
---
## Asset
실제 결과물
Examples
- Design
- Source Code
- Image
- Video
---
# 11. Repository Mapping
| Knowledge Type | Primary Repository | Secondary Repository |
| --- | --- | --- |
| Philosophy | Notion | GitHub |
| Product Bible | Notion | GitHub |
| PRD | Notion | GitHub |
| UX Specification | Notion | Figma |
| UI Specification | Notion | Figma |
| Design System | Figma | Notion |
| Engineering Specification | GitHub | Notion |
| Source Code | GitHub | - |
| Prototype | Figma | Notion |
| Research | Notion | Cloud Storage |
| AI Prompt | Notion | GitHub |
| Dataset | Cloud Storage | GitHub |
---
# 12. Repository Selection Rules
## Rule KA-01
하나의 Knowledge는 Primary Repository를 가진다.
---
## Rule KA-02
동일한 Knowledge를 여러 Repository에 복사하지 않는다.
---
## Rule KA-03
Repository 간 연결은 Reference를 사용한다.
---
## Rule KA-04
Asset보다 Knowledge가 우선이다.
---
## Rule KA-05
Repository 구조보다 Knowledge 구조를 우선 설계한다.
---
# 13. Architecture Anti Pattern
## Anti Pattern 1
Repository 중심 설계
잘못된 질문
```plain text
GitHub에 저장할까?
```
올바른 질문
```plain text
이 Knowledge는 무엇인가?
```
---
## Anti Pattern 2
Document와 Asset 혼동
잘못된 예
```plain text
Figma 파일이 곧 UX 문서이다.
```
올바른 예
```plain text
UX 문서는 Notion에 존재한다.

Figma는 UX를 구현한 Design Asset이다.
```
---
## Anti Pattern 3
Knowledge Duplication
같은 PRD를
- Notion
- Word
- PPT
에 각각 수정하는 행위는 금지한다.
Single Source of Truth를 유지한다.
---
# 14. Architecture Principles
Principle KA-01
Knowledge는 Repository보다 상위 개념이다.
---
Principle KA-02
Repository는 역할에 따라 분리한다.
---
Principle KA-03
Knowledge는 Reference로 연결한다.
---
Principle KA-04
모든 Repository는 하나의 Product Genome을 구성한다.
---
Principle KA-05
Human과 AI는 동일한 Knowledge Network를 사용한다.
---
# 15. References
Related Documents
- DOC-001 Document Philosophy
- DOC-002 Document Structure
- DOC-003 Metadata Standard
- DOC-004 Document Template Standard
- DOC-005-PART-I Knowledge Management Philosophy
---
# Document Information
Document ID
DOC-005-PART-II
Title
Knowledge Architecture
Version
1.0.0
Status
Draft
Next
DOC-005-PART-III Knowledge Relationship Model
---
document_id: DOC-005-PART-III
parent_document:
- DOC-005
title: Knowledge Relationship Model
book: Foundation
domain: Knowledge Management
category: Standard
version: 1.0.0
status: Draft
owner: Product Owner
created_date: 2026-07-25
related_documents:
- DOC-002
- DOC-003
- DOC-004
- DOC-005-PART-I
- DOC-005-PART-II
tags:
- relationship
- graph
- reference
- traceability
- product-genome
context_scope:
Global
## summary:
Defines how every Knowledge Object is connected to build the RoRo Product Genome.
# 005 Knowledge Management Standard
# Part III - Knowledge Relationship Model
Version 1.0.0
Status: Draft
---
# 1. Purpose
본 문서는 RoRo Product Genome에서 모든 Knowledge가 서로 연결되는 방식을 정의한다.
RoRo는 Document Management System이 아니다.
RoRo는 Knowledge Network이다.
따라서 문서를 잘 작성하는 것보다 더 중요한 것은 문서를 올바르게 연결하는 것이다.
Relationship가 없는 Document는 단순한 파일에 불과하다.
Relationship가 형성되는 순간 Document는 Knowledge Network의 Node가 된다.
---
# 2. Philosophy
RoRo에서는 다음 원칙을 따른다.
```plain text
Knowledge

↓

Relationship

↓

Knowledge Graph

↓

Product Intelligence
```
Knowledge는 Relationship을 통해 새로운 의미를 만든다.
따라서 연결이 끊어진 Knowledge는 시간이 지날수록 가치가 감소한다.
---
# 3. Relationship Definition
Relationship란 하나의 Knowledge Object가 다른 Knowledge Object와 가지는 의미 있는 연결이다.
Relationship는 단순한 링크가 아니다.
Relationship는
- 의존성
- 근거
- 흐름
- 진화 과정
을 표현한다.
---
# 4. Knowledge Graph
RoRo는 모든 Knowledge를 Graph 형태로 관리한다.
Graph의 구성 요소
```plain text
Node

↓

Relationship

↓

Knowledge Graph
```
---
## Node
Node는 하나의 Knowledge Object이다.
Examples
- Product Bible
- PRD
- UX Specification
- ADR
- User Research
- AI Prompt
- Sprint
- Release Note
---
## Edge
Edge는 Node 사이의 연결이다.
Example
```plain text
PRD

↓

implements

↓

Feature
```
---
# 5. Relationship Types
RoRo는 Relationship를 의미에 따라 분류한다.
---
## 5.1 Parent Of
상위 구조
Example
```plain text
Product

↓

Parent Of

↓

Feature
```
---
## 5.2 Child Of
하위 구조
Example
```plain text
Feature

↓

Child Of

↓

Product
```
---
## 5.3 References
참조 관계
Example
```plain text
PRD

↓

References

↓

User Research
```
---
## 5.4 Depends On
의존 관계
Example
```plain text
AI Diary

↓

Depends On

↓

Photo Analysis Engine
```
---
## 5.5 Implements
구현 관계
Example
```plain text
Engineering

↓

Implements

↓

PRD
```
---
## 5.6 Validates
검증 관계
Example
```plain text
QA

↓

Validates

↓

Requirement
```
---
## 5.7 Generates
생성 관계
Example
```plain text
AI Prompt

↓

Generates

↓

Travel Diary
```
---
## 5.8 Evolves To
진화 관계
Example
```plain text
PRD v1

↓

Evolves To

↓

PRD v2
```
---
## 5.9 Replaces
대체 관계
Example
```plain text
Old UX

↓

Replaces

↓

New UX
```
---
## 5.10 Derived From
파생 관계
Example
```plain text
Marketing Copy

↓

Derived From

↓

Product Bible
```
---
# 6. Relationship Direction
Relationship는 항상 방향(Direction)을 가진다.
잘못된 예
```plain text
PRD

—

UX
```
올바른 예
```plain text
PRD

↓

Defines

↓

UX Specification
```
Direction은 AI 추론과 Traceability를 위해 필수이다.
---
# 7. Relationship Strength
Relationship는 중요도(Level)를 가진다.
## Strong
반드시 연결되어야 하는 관계
Examples
- Product Bible → PRD
- PRD → Feature
- Feature → UX
---
## Medium
권장 연결
Examples
- PRD → Meeting
- Research → Roadmap
---
## Weak
참고용 연결
Examples
- Blog
- External Article
---
# 8. Traceability
RoRo는 모든 중요한 Decision을 추적 가능해야 한다.
Traceability Example
```plain text
User Interview

↓

User Insight

↓

Problem Statement

↓

PRD

↓

Feature

↓

UX Design

↓

Figma

↓

Implementation

↓

Release

↓

Customer Feedback
```
이 흐름이 끊기지 않아야 한다.
---
# 9. Reference Rule
Reference는 Copy보다 우선한다.
잘못된 예
```plain text
Research 내용 복사

↓

PRD

↓

Design

↓

Wiki
```
동일한 내용을 여러 문서에서 수정해야 한다.
---
올바른 예
```plain text
Research

↓

Reference

↓

PRD

↓

Reference

↓

Design
```
Single Source of Truth를 유지한다.
---
# 10. Bidirectional Navigation
모든 주요 Document는 양방향 탐색이 가능해야 한다.
Example
```plain text
Product Bible

↓

PRD

↓

Feature

↓

Engineering
```
Engineering에서도
```plain text
Engineering

↑

Feature

↑

PRD

↑

Product Bible
```
역방향 탐색이 가능해야 한다.
---
# 11. Relationship Anti Pattern
## Anti Pattern 1
Orphan Document
어떤 문서와도 연결되지 않은 Document
---
## Anti Pattern 2
Circular Dependency
불필요한 순환 참조
Example
```plain text
A

↓

B

↓

C

↓

A
```
---
## Anti Pattern 3
Broken Reference
삭제된 문서를 계속 참조하는 경우
---
## Anti Pattern 4
Duplicate Relationship
동일한 의미의 Relationship를 여러 번 생성하는 경우
---
## Anti Pattern 5
Meaningless Link
"관련 있음"처럼 의미가 불명확한 연결
Relationship는 반드시 의미를 가져야 한다.
---
# 12. Relationship Lifecycle
Relationship도 Lifecycle을 가진다.
```plain text
Created

↓

Verified

↓

Active

↓

Deprecated

↓

Archived
```
더 이상 유효하지 않은 연결은 Deprecated 상태로 관리한다.
---
# 13. AI Relationship Model
AI는 Relationship를 기반으로 Context를 확장한다.
Example
```plain text
User asks

↓

AI retrieves PRD

↓

AI retrieves User Research

↓

AI retrieves UX

↓

AI retrieves Decision History

↓

AI generates answer
```
따라서 AI 품질은 Relationship 품질에 비례한다.
---
# 14. Relationship Quality Checklist
모든 공식 Document는 다음을 확인한다.
□ Parent 연결
□ Child 연결
□ Reference 연결
□ Related Decision 연결
□ Related Asset 연결
□ Version 연결
□ Status 확인
□ Broken Link 없음
---
# 15. Relationship Rules
## Rule KR-01
모든 공식 Document는 최소 1개의 Relationship를 가진다.
---
## Rule KR-02
Relationship는 의미를 가져야 한다.
---
## Rule KR-03
Reference는 Copy보다 우선한다.
---
## Rule KR-04
Relationship는 Direction을 가진다.
---
## Rule KR-05
Relationship는 Traceability를 지원해야 한다.
---
## Rule KR-06
Knowledge Graph는 지속적으로 Evolution한다.
---
# 16. References
Related Documents
- DOC-002 Document Structure
- DOC-003 Metadata Standard
- DOC-004 Document Template Standard
- DOC-005-PART-I Knowledge Management Philosophy
- DOC-005-PART-II Knowledge Architecture
---
# Document Information
Document ID
DOC-005-PART-III
Title
Knowledge Relationship Model
Version
1.0.0
Status
Draft
Next
DOC-005-PART-IV Knowledge Lifecycle Management
---
document_id: DOC-005-PART-IV
parent_document:
- DOC-005
title: Knowledge Lifecycle Management
book: Foundation
domain: Knowledge Management
category: Standard
version: 1.0.0
status: Draft
owner: Product Owner
created_date: 2026-07-25
related_documents:
- DOC-003
- DOC-004
- DOC-005-PART-I
- DOC-005-PART-II
- DOC-005-PART-III
tags:
- lifecycle
- governance
- evolution
- maintenance
- product-genome
context_scope:
Global
## summary:
Defines the lifecycle of every Knowledge Object from creation to retirement and establishes the operating principles for continuous knowledge evolution.
# 005 Knowledge Management Standard
# Part IV - Knowledge Lifecycle Management
Version 1.0.0
Status: Draft
---
# 1. Purpose
본 문서는 RoRo Product Genome에서 생성되는 모든 Knowledge Object의 생애주기(Lifecycle)를 정의한다.
Knowledge는 작성되는 순간 끝나는 문서가 아니다.
Knowledge는 Product와 함께 성장하고, 수정되고, 검증되고, 연결되며, 때로는 폐기된다.
RoRo에서는 모든 Knowledge가 Lifecycle을 가진다고 정의한다.
Lifecycle을 명확하게 정의하는 목적은 다음과 같다.
- Knowledge의 최신성을 유지한다.
- 오래된 정보를 식별한다.
- 변경 이력을 추적한다.
- AI가 신뢰할 수 있는 정보를 우선 활용하도록 한다.
- Product Evolution과 Knowledge Evolution을 동기화한다.
---
# 2. Knowledge Evolution Philosophy
RoRo는 다음 원칙을 따른다.
```plain text
Knowledge Never Ends

Knowledge Evolves
```
좋은 Knowledge는 계속 수정된다.
나쁜 Knowledge는 방치된다.
Knowledge Management의 목적은 문서를 많이 만드는 것이 아니라 지속적으로 발전시키는 것이다.
---
# 3. Knowledge Lifecycle Overview
모든 Knowledge Object는 아래 Lifecycle을 따른다.
```plain text
Idea

↓

Draft

↓

Review

↓

Approved

↓

Published

↓

Active

↓

Improved

↓

Deprecated

↓

Archived
```
모든 상태는 명확한 의미를 가진다.
---
# 4. Stage 1 - Idea
## Purpose
새로운 Knowledge의 필요성이 발견된 단계이다.
Examples
- 새로운 Feature 아이디어
- 새로운 Product 방향
- 새로운 AI 기능
- 신규 Design Rule
---
## Characteristics
- 공식 문서 아님
- 자유로운 기록 가능
- Reference 선택 사항
- Version 없음
---
## Exit Criteria
다음 조건을 만족하면 Draft로 이동한다.
- 목적이 정의됨
- Owner 지정
- Document Type 결정
---
# 5. Stage 2 - Draft
## Purpose
초안 작성 단계
Document Template를 기반으로 첫 번째 문서를 작성한다.
---
## Characteristics
- Metadata 작성
- 구조 정의
- 내용 작성
- Reference 연결 시작
---
## Validation
□ Document Type 선택
□ Metadata 존재
□ Template 준수
□ Purpose 정의
---
# 6. Stage 3 - Review
## Purpose
품질 검토 단계
Review 대상
- Structure
- Context
- Relationship
- Completeness
- Accuracy
---
## Review Checklist
□ Required Section 존재
□ Broken Reference 없음
□ Duplicate Knowledge 없음
□ Context 충분
□ Version 확인
---
# 7. Stage 4 - Approved
## Purpose
공식 Knowledge로 승인된 상태
이 시점부터 Product Team의 공식 Reference가 된다.
---
## Characteristics
- Version 고정
- 공식 참조 가능
- AI Retrieval 대상
- Single Source of Truth
---
# 8. Stage 5 - Published
## Purpose
Repository에 게시된 상태
Examples
- Notion
- GitHub
- Figma
Published는 저장 위치를 의미한다.
Approved는 품질 상태를 의미한다.
둘은 동일하지 않다.
---
# 9. Stage 6 - Active
## Purpose
현재 사용 중인 최신 Version
Example
```plain text
Product Bible

Version 2.4

Status

Active
```
AI는 Active Version을 우선 사용한다.
---
# 10. Stage 7 - Improved
## Purpose
기존 Knowledge를 개선하는 단계
Examples
- 내용 추가
- 구조 개선
- Relationship 확장
- Example 추가
---
## Improvement Rule
개선은 기존 Knowledge를 삭제하지 않는다.
Evolution History를 유지한다.
---
# 11. Stage 8 - Deprecated
## Purpose
더 이상 신규 사용을 권장하지 않는 상태
Examples
- Legacy API
- Old UX
- 이전 Architecture
---
## Rule
Deprecated Document는 삭제하지 않는다.
Reference는 유지한다.
---
# 12. Stage 9 - Archived
## Purpose
역사 기록 보관
Archived Knowledge는 검색 가능하지만 기본 검색 결과에서는 우선순위를 낮춘다.
---
## Characteristics
- Read Only
- No Update
- Historical Value
---
# 13. Version Evolution
Knowledge Evolution은 Version으로 관리한다.
```plain text
Major

↓

Minor

↓

Patch
```
---
## Major
구조 변경
Examples
- 새로운 Template
- Architecture 변경
---
## Minor
내용 확장
Examples
- 새로운 Example
- Section 추가
---
## Patch
오류 수정
Examples
- 오탈자
- 잘못된 Reference
- 설명 보완
---
# 14. Knowledge Refresh Policy
모든 Active Knowledge는 주기적으로 검토한다.
Priority
| Knowledge Type | Recommended Review Cycle |
| --- | --- |
| Product Bible | Quarterly |
| PRD | Sprint 종료 시 |
| UX Specification | Design 변경 시 |
| Engineering Specification | Release 전 |
| AI Prompt | Prompt 변경 시 |
| Research | 신규 데이터 확보 시 |
| Foundation Documents | 반기 1회 |
Review는 형식적인 절차가 아니라 Product 변화와 동기화되어야 한다.
---
# 15. Knowledge Retirement Policy
Knowledge는 다음 조건에서 Retirement를 검토한다.
- Product 종료
- Feature 제거
- Architecture 폐기
- Business 종료
- 새로운 Knowledge로 완전히 대체
Retirement는 삭제가 아니다.
Archive 상태로 유지한다.
---
# 16. Lifecycle Anti Pattern
## Anti Pattern 1
Never Updated
작성 후 한 번도 수정되지 않는 문서
---
## Anti Pattern 2
Always Draft
영원히 Draft 상태인 문서
---
## Anti Pattern 3
Delete Instead Of Archive
삭제를 통해 History를 잃는 경우
---
## Anti Pattern 4
Unknown Version
Version 없는 공식 문서
---
## Anti Pattern 5
Multiple Active Versions
동시에 여러 Active Version 존재
Single Source of Truth를 위반한다.
---
# 17. Lifecycle Metrics
Knowledge Lifecycle 품질은 다음 지표로 관리한다.
- Active Knowledge Ratio
- Deprecated Ratio
- Average Review Interval
- Reference Growth Rate
- Version Stability
- Knowledge Reuse Rate
- Broken Reference Count
- Average Document Age
---
# 18. Lifecycle Rules
## Rule KL-01
모든 Knowledge는 Lifecycle Status를 가진다.
---
## Rule KL-02
Draft는 공식 Reference가 될 수 없다.
---
## Rule KL-03
Approved 상태만 공식 Knowledge로 사용한다.
---
## Rule KL-04
Deprecated Knowledge는 삭제하지 않는다.
---
## Rule KL-05
Archive는 History를 보존하기 위한 상태이다.
---
## Rule KL-06
모든 Active Knowledge는 정기적으로 Review한다.
---
## Rule KL-07
Version History는 Product History의 일부이다.
---
# 19. References
Related Documents
- DOC-003 Metadata Standard
- DOC-004 Document Template Standard
- DOC-005-PART-I Knowledge Management Philosophy
- DOC-005-PART-II Knowledge Architecture
- DOC-005-PART-III Knowledge Relationship Model
---
# Document Information
Document ID
DOC-005-PART-IV
Title
Knowledge Lifecycle Management
Version
1.0.0
Status
Draft
Next
DOC-005-PART-V Notion Knowledge Base Architecture
---
document_id: DOC-005-PART-V
parent_document:
- DOC-005
title: Notion Knowledge Base Architecture
book: Foundation
domain: Knowledge Management
category: Standard
version: 1.0.0
status: Draft
owner: Product Owner
created_date: 2026-07-25
related_documents:
- DOC-003
- DOC-004
- DOC-005-PART-I
- DOC-005-PART-II
- DOC-005-PART-III
- DOC-005-PART-IV
tags:
- notion
- knowledge-base
- database
- workspace
- architecture
context_scope:
Global
## summary:
Defines the architecture, database model, page hierarchy, and operational principles of the RoRo Notion Knowledge Base.
# 005 Knowledge Management Standard
# Part V - Notion Knowledge Base Architecture
Version 1.0.0
Status: Draft
---
# 1. Purpose
본 문서는 RoRo Product Genome을 운영하기 위한 Notion Workspace Architecture를 정의한다.
Notion은 단순한 문서 저장소가 아니다.
RoRo에서 Notion은 다음 역할을 수행한다.
- Product Brain
- Knowledge Repository
- Decision Repository
- Collaboration Platform
- AI Context Source
모든 공식 Product Knowledge는 Notion을 중심으로 관리한다.
---
# 2. Design Philosophy
RoRo Notion은 다음 원칙을 따른다.
```plain text
One Workspace

↓

Multiple Databases

↓

Connected Knowledge

↓

Single Product Genome
```
Workspace는 하나이지만 Knowledge는 Database 단위로 관리한다.
---
# 3. Workspace Structure
```plain text
RoRo Project

├── Foundation
├── Product
├── Research
├── Design
├── Engineering
├── AI
├── Operations
├── Release
├── Archive
└── Assets
```
각 영역은 독립적으로 관리되지만 하나의 Knowledge Network를 구성한다.
---
# 4. Core Database Architecture
RoRo는 다음 Database를 기본으로 사용한다.
| Database | Purpose |
| --- | --- |
| Documents | 모든 공식 문서 |
| Product Bible | Product 정의 |
| PRD | Product Requirement |
| Features | Feature 관리 |
| User Research | 사용자 조사 |
| Decisions | ADR 및 의사결정 |
| Design | UX/UI 문서 |
| Engineering | 기술 문서 |
| AI | Prompt 및 AI Feature |
| Sprint | 개발 일정 |
| Release | Release History |
| Glossary | 용어 사전 |
각 Database는 독립적인 Primary Key를 가진다.
---
# 5. Documents Database
모든 공식 문서는 Documents Database에 등록된다.
필수 Property
| Property | Type |
| --- | --- |
| Document ID | Title |
| Title | Text |
| Document Type | Select |
| Status | Status |
| Version | Text |
| Owner | Person |
| Parent | Relation |
| References | Relation |
| Tags | Multi-select |
| Created Date | Date |
| Updated Date | Date |
Documents Database는 Product Genome의 중심 Database이다.
---
# 6. Product Bible Database
Purpose
Product의 최상위 Knowledge 관리
Property
- Product Name
- Vision
- Mission
- Target User
- Value Proposition
- Strategy
- Roadmap
- Related PRD
Relationship
```plain text
Product Bible

↓

PRD

↓

Feature

↓

Sprint
```
---
# 7. PRD Database
Purpose
모든 Product Requirement 관리
Property
- PRD ID
- Feature
- Status
- Priority
- Owner
- Related Research
- Related Design
- Related Engineering
- Related Release
PRD는 Feature 개발의 중심이다.
---
# 8. Feature Database
Feature 단위의 Product 관리
Property
- Feature ID
- Name
- Category
- Product
- Priority
- Sprint
- Release
- Status
Relationship
```plain text
Feature

↓

UX

↓

Engineering

↓

QA

↓

Release
```
---
# 9. Decision Database
Purpose
Architecture Decision Record 관리
Property
- Decision ID
- Decision
- Context
- Alternatives
- Final Decision
- Impact
- Related Documents
Decision는 Product Memory를 구성한다.
---
# 10. Research Database
Purpose
모든 User Research 관리
Property
- Research ID
- Research Type
- User Segment
- Insight
- Evidence
- Related PRD
Research는 Product Decision의 근거이다.
---
# 11. Design Database
Purpose
UX/UI Knowledge 관리
Property
- Design ID
- UX Flow
- Wireframe
- Figma Link
- Component
- Related PRD
Design Database는 Figma Asset과 연결된다.
---
# 12. Engineering Database
Purpose
Technical Knowledge 관리
Property
- Engineering ID
- Architecture
- API
- Module
- GitHub Repository
- Related PRD
Engineering Database는 GitHub와 연결된다.
---
# 13. AI Database
Purpose
AI Feature Knowledge 관리
Property
- Prompt
- AI Workflow
- Input
- Output
- Evaluation
- Model
- Related Feature
AI Prompt도 공식 Knowledge로 관리한다.
---
# 14. Cross Database Relationship
모든 Database는 Relation으로 연결한다.
Example
```plain text
User Research

↓

PRD

↓

Feature

↓

Design

↓

Engineering

↓

Release
```
Duplicate Page를 만들지 않는다.
Reference를 사용한다.
---
# 15. Dashboard Architecture
Workspace에는 다음 Dashboard를 제공한다.
## Executive Dashboard
- Product Status
- Release
- KPI
---
## Product Dashboard
- Product Bible
- PRD
- Feature
---
## Design Dashboard
- UX
- UI
- Prototype
---
## Engineering Dashboard
- Sprint
- Issue
- ADR
- Release
---
## AI Dashboard
- Prompt
- Evaluation
- AI Feature
---
## Knowledge Dashboard
- Recent Documents
- Recently Updated
- Missing Metadata
- Broken Relations
- Deprecated Documents
---
# 16. Naming Convention
Document
```plain text
001 Document Philosophy
```
PRD
```plain text
PRD-001 AI Diary
```
Feature
```plain text
FEAT-001 Timeline
```
Decision
```plain text
ADR-001 Hybrid Upload Strategy
```
Research
```plain text
RES-001 Family Travel Interview
```
Version은 모든 Database에서 동일한 규칙을 따른다.
---
# 17. Search Strategy
검색은 다음 우선순위를 따른다.
1. Document ID
2. Title
3. Tag
4. Document Type
5. Related Product
6. Owner
7. Status
8. Full Text
Document ID 검색을 가장 우선한다.
---
# 18. Operational Principles
## Principle NK-01
하나의 Knowledge는 하나의 Primary Page를 가진다.
---
## Principle NK-02
모든 Database는 Relation으로 연결한다.
---
## Principle NK-03
Template 없는 Page 생성은 금지한다.
---
## Principle NK-04
Duplicate Page를 생성하지 않는다.
---
## Principle NK-05
Metadata 없는 문서는 공식 Document가 아니다.
---
## Principle NK-06
모든 공식 Document는 Documents Database에 등록한다.
---
## Principle NK-07
Notion은 Product Brain이며 GitHub와 Figma는 전문 Repository이다.
---
# 19. Anti Pattern
## Anti Pattern 1
폴더처럼 Page를 중첩하여 사용하는 구조
---
## Anti Pattern 2
같은 PRD를 여러 Page에 복사
---
## Anti Pattern 3
Database 없이 일반 Page만 사용하는 Workspace
---
## Anti Pattern 4
Document ID 없는 문서
---
## Anti Pattern 5
Relation 없이 Tag만 사용하는 구조
Tag는 분류이고,
Relation은 Knowledge이다.
---
# 20. References
Related Documents
- DOC-003 Metadata Standard
- DOC-004 Document Template Standard
- DOC-005-PART-I Knowledge Management Philosophy
- DOC-005-PART-II Knowledge Architecture
- DOC-005-PART-III Knowledge Relationship Model
- DOC-005-PART-IV Knowledge Lifecycle Management
---
# Document Information
Document ID
DOC-005-PART-V
Title
Notion Knowledge Base Architecture
Version
1.0.0
Status
Draft
Next
DOC-005-PART-VI AI Knowledge Retrieval Framework
---
document_id: DOC-005-PART-VI
parent_document:
- DOC-005
title: AI Knowledge Retrieval Framework
book: Foundation
domain: Knowledge Management
category: Standard
version: 1.0.0
status: Draft
owner: Product Owner
created_date: 2026-07-25
related_documents:
- DOC-001
- DOC-002
- DOC-003
- DOC-004
- DOC-005-PART-I
- DOC-005-PART-II
- DOC-005-PART-III
- DOC-005-PART-IV
- DOC-005-PART-V
tags:
- ai
- retrieval
- rag
- knowledge
- context
- product-genome
context_scope:
Global
## summary:
Defines how AI Agents retrieve, prioritize, reason over, and generate outputs from the RoRo Product Genome Knowledge Base.
# 005 Knowledge Management Standard
# Part VI - AI Knowledge Retrieval Framework
Version 1.0.0
Status: Draft
---
# 1. Purpose
본 문서는 AI Agent가 RoRo Product Genome의 Knowledge를 검색(Retrieve), 이해(Understand), 추론(Reason), 생성(Generate)하는 전체 Framework를 정의한다.
RoRo에서 AI는 단순한 Chat Assistant가 아니다.
AI는 Product Team의 구성원이며 Knowledge Worker이다.
따라서 AI는 사람과 동일한 Product Context를 공유해야 한다.
본 Framework의 목적은 다음과 같다.
- AI가 항상 최신 Knowledge를 참조하도록 한다.
- Product Context를 유지한다.
- Hallucination을 최소화한다.
- Knowledge 기반의 의사결정을 지원한다.
- Human과 AI가 동일한 Product Memory를 사용하도록 한다.
---
# 2. AI Knowledge Philosophy
RoRo는 다음 철학을 따른다.
```plain text
Question

↓

Knowledge Retrieval

↓

Context Assembly

↓

Reasoning

↓

Answer

↓

Knowledge Update
```
AI는 먼저 검색하고, 그 후 추론한다.
사전 지식보다 Product Knowledge를 우선한다.
---
# 3. Retrieval Hierarchy
Knowledge 검색은 아래 우선순위를 따른다.
```plain text
Foundation

↓

Product Bible

↓

Strategy

↓

Research

↓

PRD

↓

Decision

↓

Design

↓

Engineering

↓

Sprint

↓

Release

↓

Archive
```
Foundation은 항상 최우선 Context이다.
---
# 4. Context Assembly
검색된 Document는 하나의 Context로 조합된다.
예시
```plain text
User Question

↓

Product Bible

+

Related PRD

+

Related Research

+

Related ADR

+

Related UX

↓

Context Package
```
AI는 단일 문서가 아니라 Context Package를 기반으로 응답한다.
---
# 5. Retrieval Strategy
## Strategy 1
Metadata Search
검색 대상
- Document ID
- Type
- Owner
- Version
- Status
---
## Strategy 2
Semantic Search
의미 기반 검색
예시
```plain text
Family Travel

↓

Travel Memory

↓

Diary

↓

Highlight Video
```
---
## Strategy 3
Relationship Expansion
검색된 문서와 연결된 Knowledge를 자동으로 확장한다.
```plain text
PRD

↓

Related Research

↓

Related UX

↓

Related ADR
```
---
## Strategy 4
Hierarchy Expansion
상위와 하위 Knowledge를 모두 조회한다.
```plain text
Feature

↑

Product

↓

Task

↓

Release
```
---
# 6. Context Priority
AI는 모든 Knowledge를 동일하게 취급하지 않는다.
우선순위를 가진다.
| Priority | Knowledge |
| --- | --- |
| P0 | Foundation |
| P1 | Product Bible |
| P2 | ADR |
| P3 | PRD |
| P4 | User Research |
| P5 | UX |
| P6 | Engineering |
| P7 | Sprint |
| P8 | Archive |
상위 Priority가 충돌할 경우 항상 우선한다.
---
# 7. Context Window Management
AI는 Context Window를 효율적으로 사용해야 한다.
우선 포함
- Vision
- Philosophy
- Decision
- Current PRD
필요 시 포함
- UX
- Architecture
- Meeting
후순위
- History
- Archive
Context Overflow를 방지한다.
---
# 8. Knowledge Confidence
검색된 Knowledge는 신뢰도를 가진다.
| Level | Description |
| --- | --- |
| Verified | 공식 승인 |
| Reviewed | 검토 완료 |
| Draft | 초안 |
| Deprecated | 사용 중단 |
| Archived | 역사 기록 |
AI는 Verified Knowledge를 우선한다.
---
# 9. Multi-Document Reasoning
AI는 여러 문서를 함께 추론한다.
Example
```plain text
Research

+

PRD

+

ADR

+

UX

↓

Reasoning

↓

Recommendation
```
단일 문서만으로 결론을 내리지 않는다.
---
# 10. Conflict Resolution
Knowledge 간 충돌이 발생할 수 있다.
예시
```plain text
PRD v1

↓

Camera Upload

PRD v2

↓

Gallery First
```
Resolution Rule
1. Active Version 우선
2. Latest Approved 우선
3. Higher Priority Document 우선
4. ADR 확인
5. Human Confirmation
---
# 11. Knowledge Update Loop
AI는 새로운 Knowledge를 생성할 수 있다.
```plain text
Question

↓

Answer

↓

New Insight

↓

Review

↓

Knowledge Candidate

↓

Official Document
```
AI가 생성한 내용은 Review 없이 공식 Knowledge가 될 수 없다.
---
# 12. AI Retrieval Anti Pattern
## Anti Pattern 1
Keyword Only Search
의미를 고려하지 않는다.
---
## Anti Pattern 2
Single Document Answer
한 개 문서만 참조한다.
---
## Anti Pattern 3
Ignoring Relationships
연결된 Knowledge를 무시한다.
---
## Anti Pattern 4
Using Deprecated Knowledge
Deprecated 문서를 최신 정보처럼 사용한다.
---
## Anti Pattern 5
Ignoring Foundation
Product Philosophy를 무시한다.
---
# 13. AI Prompt Integration
Prompt는 항상 Product Context를 포함한다.
기본 구조
```plain text
Foundation

↓

Product Bible

↓

Current Feature

↓

Current Question
```
Prompt는 독립적으로 존재하지 않는다.
Knowledge Graph의 일부이다.
---
# 14. Retrieval Performance Metrics
AI Retrieval 품질은 다음으로 측정한다.
- Context Accuracy
- Citation Accuracy
- Retrieval Recall
- Retrieval Precision
- Average Retrieval Time
- Knowledge Coverage
- Relationship Expansion Rate
- Hallucination Rate
---
# 15. Operational Rules
## Rule AR-01
AI는 Foundation을 항상 우선 조회한다.
---
## Rule AR-02
Approved Knowledge만 공식 근거로 사용한다.
---
## Rule AR-03
Relationship Expansion을 기본 동작으로 한다.
---
## Rule AR-04
AI는 Context Package를 기반으로 추론한다.
---
## Rule AR-05
AI 생성 결과는 Review를 거쳐 Knowledge가 된다.
---
## Rule AR-06
Archive는 기본 검색 대상이 아니다.
---
## Rule AR-07
Prompt는 Product Context 없이 실행하지 않는다.
---
# 16. Future Evolution
향후 RoRo AI는 다음 기능을 지원한다.
- Automatic Context Building
- Knowledge Gap Detection
- Missing Reference Detection
- Duplicate Knowledge Detection
- Architecture Impact Analysis
- Product Consistency Check
- Autonomous Documentation Suggestion
- Multi-Agent Collaboration
---
# 17. References
Related Documents
- DOC-001 Document Philosophy
- DOC-002 Document Structure
- DOC-003 Metadata Standard
- DOC-004 Document Template Standard
- DOC-005-PART-I Knowledge Management Philosophy
- DOC-005-PART-II Knowledge Architecture
- DOC-005-PART-III Knowledge Relationship Model
- DOC-005-PART-IV Knowledge Lifecycle Management
- DOC-005-PART-V Notion Knowledge Base Architecture
---
# Document Information
Document ID
DOC-005-PART-VI
Title
AI Knowledge Retrieval Framework
Version
1.0.0
Status
Draft
Next
DOC-005-PART-VII Knowledge Governance & Quality Control
---
document_id: DOC-005-PART-VII
parent_document:
- DOC-005
title: Knowledge Governance & Quality Control
book: Foundation
domain: Knowledge Management
category: Standard
version: 1.0.0
status: Draft
owner: Product Owner
created_date: 2026-07-25
related_documents:
- DOC-001
- DOC-002
- DOC-003
- DOC-004
- DOC-005-PART-I
- DOC-005-PART-II
- DOC-005-PART-III
- DOC-005-PART-IV
- DOC-005-PART-V
- DOC-005-PART-VI
tags:
- governance
- quality
- audit
- lifecycle
- product-genome
context_scope:
Global
## summary:
Defines governance principles, quality standards, audit processes, ownership, and continuous improvement mechanisms for the RoRo Knowledge Management System.
# 005 Knowledge Management Standard
# Part VII - Knowledge Governance & Quality Control
Version 1.0.0
Status: Draft
---
# 1. Purpose
본 문서는 RoRo Product Genome의 모든 Knowledge를 지속적으로 신뢰할 수 있는 상태로 유지하기 위한 Governance 체계를 정의한다.
Knowledge는 생성보다 유지가 더 중요하다.
시간이 지날수록 Product는 변화하고 조직은 성장하며 기술은 발전한다.
Knowledge 역시 이에 맞추어 지속적으로 진화해야 한다.
Governance의 목적은 문서를 통제하는 것이 아니라 Product Intelligence를 보호하는 것이다.
---
# 2. Governance Philosophy
RoRo는 다음 원칙을 따른다.
```plain text
Knowledge

↓

Governance

↓

Quality

↓

Trust

↓

Product Intelligence
```
Governance가 없는 Knowledge는 시간이 지날수록 신뢰를 잃는다.
---
# 3. Governance Objectives
Knowledge Governance의 목표는 다음과 같다.
- Single Source of Truth 유지
- 지속적인 품질 향상
- Decision History 보존
- Knowledge 재사용 극대화
- AI 활용성 유지
- Product Consistency 확보
---
# 4. Governance Scope
Governance 대상은 모든 공식 Knowledge이다.
포함 대상
- Foundation Documents
- Product Bible
- PRD
- Research
- ADR
- UX Specification
- Engineering Specification
- AI Prompt
- Release Documentation
- Standard Documents
비공식 메모와 개인 노트는 Governance 대상이 아니다.
---
# 5. Knowledge Ownership
모든 Knowledge는 Owner를 가진다.
Owner의 책임
- 내용 최신화
- 품질 유지
- Metadata 관리
- Relationship 유지
- Review 수행
- Deprecated 여부 결정
Owner가 없는 공식 Knowledge는 존재할 수 없다.
---
# 6. Review Process
모든 Active Knowledge는 정기적으로 Review한다.
Review Process
```plain text
Identify

↓

Review

↓

Update

↓

Approve

↓

Publish
```
Review 시 확인 사항
- 내용 최신성
- Version
- Broken Reference
- Duplicate Knowledge
- Metadata
- Relationship
- AI 활용 가능 여부
---
# 7. Knowledge Audit
Audit는 Knowledge 전체를 대상으로 수행한다.
Audit 항목
## Metadata Audit
- ID 존재
- Version 존재
- Status 존재
- Owner 존재
---
## Relationship Audit
- Broken Reference
- Missing Parent
- Missing Child
- Circular Dependency
---
## Quality Audit
- Structure
- Completeness
- Consistency
- Accuracy
---
## Lifecycle Audit
- 오래된 Draft
- 미검토 Active
- Deprecated 미처리
- Archive 대상
---
# 8. Quality Dimensions
Knowledge Quality는 다음 여섯 가지 관점에서 평가한다.
## Completeness
필수 정보가 모두 존재하는가.
---
## Accuracy
내용이 사실과 일치하는가.
---
## Consistency
다른 Knowledge와 충돌하지 않는가.
---
## Traceability
근거를 추적할 수 있는가.
---
## Reusability
다른 Product Activity에서 재사용 가능한가.
---
## AI Readiness
AI가 이해하고 활용 가능한 구조인가.
---
# 9. Knowledge Quality Score
모든 공식 Knowledge는 Quality Score를 가진다.
| Level | Description |
| --- | --- |
| Level 1 | Draft Quality |
| Level 2 | Structured |
| Level 3 | Reviewed |
| Level 4 | Production Ready |
| Level 5 | Product Genome Standard |
Level 5는 Foundation Document와 핵심 Product Knowledge에 적용한다.
---
# 10. Governance Dashboard
Workspace에는 Governance Dashboard를 운영한다.
Dashboard 항목
- Recently Updated
- Review Due
- Deprecated Documents
- Missing Metadata
- Broken Relationships
- Duplicate Candidates
- Quality Score
- Knowledge Growth
- Review Completion Rate
Governance Dashboard는 Product Health를 나타내는 핵심 지표이다.
---
# 11. Continuous Improvement
Knowledge는 지속적으로 개선한다.
Improvement Cycle
```plain text
Measure

↓

Analyze

↓

Improve

↓

Review

↓

Publish

↓

Measure
```
Governance는 일회성 활동이 아니다.
---
# 12. Governance Anti Pattern
## Anti Pattern 1
Owner 없는 문서
---
## Anti Pattern 2
Version 없는 공식 문서
---
## Anti Pattern 3
Broken Relationship 방치
---
## Anti Pattern 4
Review하지 않는 Active Document
---
## Anti Pattern 5
Duplicate Knowledge 생성
---
## Anti Pattern 6
Foundation을 수정하면서 History를 남기지 않는 행위
---
## Anti Pattern 7
AI Prompt를 개인 문서처럼 관리하는 행위
Prompt 역시 공식 Knowledge이다.
---
# 13. Governance Metrics
Knowledge Governance는 다음 KPI를 관리한다.
| KPI | Description |
| --- | --- |
| Active Knowledge Ratio | Active 문서 비율 |
| Review Completion Rate | Review 완료율 |
| Metadata Completeness | Metadata 충족률 |
| Broken Reference Count | 손상된 Reference 수 |
| Duplicate Knowledge Count | 중복 문서 수 |
| Average Document Age | 평균 문서 갱신 주기 |
| Knowledge Reuse Rate | 재사용률 |
| AI Retrieval Success Rate | AI 검색 성공률 |
---
# 14. Governance Roles
## Product Owner
- Product Knowledge 승인
- Product Bible 관리
- PRD 승인
---
## Design Owner
- UX/UI 관리
- Design Standard 유지
---
## Engineering Owner
- Technical Knowledge 관리
- Architecture 관리
---
## AI Owner
- Prompt 관리
- AI Workflow 관리
---
## Knowledge Owner
- Foundation 관리
- Governance 운영
- Audit 수행
---
# 15. Governance Rules
## Rule KG-01
모든 공식 Knowledge는 Owner를 가진다.
---
## Rule KG-02
모든 Active Knowledge는 정기 Review를 수행한다.
---
## Rule KG-03
Duplicate보다 Reference를 우선한다.
---
## Rule KG-04
Broken Relationship는 즉시 수정한다.
---
## Rule KG-05
Version History를 삭제하지 않는다.
---
## Rule KG-06
Foundation은 Product Genome의 최상위 Knowledge이다.
---
## Rule KG-07
AI가 사용하는 Knowledge는 반드시 Approved 상태여야 한다.
---
## Rule KG-08
Governance는 Product Development Process의 일부이다.
---
# 16. Final Declaration
RoRo Product Genome은 다음 원칙을 선언한다.
Knowledge는 Product의 기억이다.
Knowledge는 조직의 자산이다.
Knowledge는 AI의 사고 기반이다.
Knowledge는 Product Evolution의 핵심 동력이다.
RoRo는 문서를 관리하는 시스템이 아니라 Knowledge를 성장시키는 시스템을 구축한다.
---
# 17. References
Related Documents
- DOC-001 Document Philosophy
- DOC-002 Document Structure
- DOC-003 Metadata Standard
- DOC-004 Document Template Standard
- DOC-005-PART-I Knowledge Management Philosophy
- DOC-005-PART-II Knowledge Architecture
- DOC-005-PART-III Knowledge Relationship Model
- DOC-005-PART-IV Knowledge Lifecycle Management
- DOC-005-PART-V Notion Knowledge Base Architecture
- DOC-005-PART-VI AI Knowledge Retrieval Framework
---
# Document Information
Document ID
DOC-005-PART-VII
Title
Knowledge Governance & Quality Control
Version
1.0.0
Status
Draft
---
# DOC-005 Knowledge Management Standard
Status
Completed
Next
DOC-006 Product Development Framework
