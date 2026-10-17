<!-- Source: Notion page [002 Document Structure](https://app.notion.com/p/3a8dff1c1f7480eb8a25fe06fe273681?pvs=204). Page ID: 3a8dff1c-1f74-80eb-8a25-fe06fe273681. Path: My Travel - RoRo / 100 📖 Foundation / 110 Documentation. Last edited: 2026-07-25T06:59:04.086Z. -->

# 002_Document_Structure.md
Version: 1.0
Status: Draft
Classification: Constitution
Book: I - Foundation
Domain: Documentation
Owner: Product Owner
Source of Truth: Markdown Repository
---
# Part I
# Knowledge Architecture
---
# Chapter 1
# Purpose
## 1.1 Objective
본 문서는 RoRo Product Knowledge Base의 구조를 정의한다.
이 문서는
- 문서의 저장 방식
- 문서 간 관계
- 계층 구조
- 탐색 방법
- 확장 원칙
을 공식적으로 정의한다.
본 문서를 기준으로
모든 Documentation,
Notion,
GitHub,
Figma,
AI Context는
동일한 Knowledge Architecture를 사용한다.
---
## 1.2 Scope
본 문서는 다음 대상을 포함한다.
- Markdown Documents
- ADR
- Product Bible
- PRD
- UX Documentation
- Architecture Documentation
- Design Documentation
- API Documentation
- Research Documentation
- Operations Documentation
본 문서는 구현 코드(Source Code)의 구조를 정의하지 않는다.
---
## 1.3 Goals
Knowledge Architecture의 목표는 다음과 같다.
1.
모든 정보를 단 하나의 위치에서 찾을 수 있다.
1.
문서 수가 증가해도 탐색성이 유지된다.
1.
AI와 사람이 동일한 구조를 이해한다.
1.
문서 간 관계를 추적할 수 있다.
1.
제품이 성장해도 구조를 변경하지 않는다.
---
## 1.4 Non Goals
본 문서는 다음 내용을 정의하지 않는다.
- UI Design
- Software Architecture
- API Specification
- Database Schema
- Source Code Style
해당 내용은 각각의 Domain Document에서 정의한다.
---
# Chapter 2
# Design Goals
Knowledge Architecture는 다음 목표를 가진다.
---
## Goal 1
Predictability
새로운 문서의 위치를
추측할 수 있어야 한다.
예를 들어
Moment Model은
Product Domain에 존재해야 한다.
Architecture Domain에 존재해서는 안 된다.
---
## Goal 2
Consistency
모든 문서는
동일한 규칙을 따른다.
예외를 최소화한다.
---
## Goal 3
Scalability
문서 수와 관계없이
구조는 동일해야 한다.
10개
100개
500개
2,000개
모두 동일한 원칙을 따른다.
---
## Goal 4
AI Readability
AI는
Folder 이름만 보고도
Domain을 추론할 수 있어야 한다.
---
## Goal 5
Human Discoverability
사람은
검색보다
구조를 통해
문서를 찾을 수 있어야 한다.
---
# Chapter 3
# Documentation Topology
RoRo는
Tree Structure를 채택한다.
Knowledge는
다음 계층을 가진다.
Book
↓
Domain
↓
Category
↓
Document
↓
Chapter
↓
Section
↓
Rule
↓
ADR
---
## Why Tree
Tree는
- 이해하기 쉽다.
- 탐색이 쉽다.
- AI Parsing이 쉽다.
- Git 관리가 쉽다.
- 확장이 쉽다.
RoRo는
Graph를 내부 관계로 사용하지만
저장 구조는 Tree를 사용한다.
---
## Internal Relationship
저장 구조
↓
Tree
참조 구조
↓
Knowledge Graph
이는
Storage와
Relationship를
분리하기 위함이다.
---
# Chapter 4
# Knowledge Hierarchy
Knowledge는
다음 우선순위를 가진다.
Level 1
Constitution
↓
Level 2
Philosophy
↓
Level 3
Standard
↓
Level 4
Specification
↓
Level 5
Guide
↓
Level 6
Reference
↓
Level 7
Examples
---
## Meaning
Constitution
절대 규칙
---
Philosophy
왜 존재하는가
---
Standard
반드시 따라야 하는 규격
---
Specification
정확한 정의
---
Guide
권장 방법
---
Reference
참고 자료
---
Example
예시
---
상위 Level은
하위 Level보다
우선한다.
예를 들어
Guide는
Constitution을
변경할 수 없다.
---
# Chapter 5
# Domain Separation
RoRo는
Knowledge를
Domain 단위로 분리한다.
Domain은
책임(Responsibility)을 의미한다.
기술을 의미하지 않는다.
---
## Official Domains
Foundation
제품의 기본 철학
---
Product
제품 정의
---
Design
UX/UI
---
Engineering
기술
---
AI
AI 시스템
---
Operations
운영
---
Research
조사
---
Business
사업
---
## Domain Responsibility
하나의 문서는
하나의 Domain만 가진다.
동일 문서는
여러 Domain에
동시에 존재하지 않는다.
필요한 경우
Reference를 사용한다.
Copy를 사용하지 않는다.
---
## Architecture Decision
ADR-001
Knowledge Architecture는
Book
↓
Domain
↓
Category
↓
Document
↓
Chapter
↓
Section
구조를 사용한다.
---
ADR-002
Knowledge는
Domain 기준으로 관리한다.
---
ADR-003
Storage Structure와
Knowledge Relationship를
분리한다.
---
## Related Documents
001_Document_Philosophy.md
003_Document_Lifecycle.md
020_Architecture_Decision_Record.md
# Part II
# Documentation Hierarchy
---
# Chapter 6
# Book
## 6.1 Definition
Book은 RoRo Product Knowledge Base에서 가장 상위의 논리적 단위(Logical Collection)이다.
Book은 개별 문서를 저장하기 위한 폴더가 아니다.
Book은 하나의 독립적인 지식 영역(Knowledge Domain Group)을 의미한다.
Book은 제품 전체를 이해하기 위한 최상위 분류 체계이다.
---
## 6.2 Responsibilities
Book은 다음을 책임진다.
- 지식 영역의 분리
- 상위 철학 제공
- 문서 탐색 단순화
- 장기 확장성 확보
Book은 세부 기능을 정의하지 않는다.
---
## 6.3 Official Books
RoRo는 다음 Book을 공식 채택한다.
Book I
Foundation
프로젝트 철학과 헌법
---
Book II
Product
제품 정의
---
Book III
Design
UX / UI / Design System
---
Book IV
Engineering
Architecture / API / Code
---
Book V
AI
Prompt / Context / AI System
---
Book VI
Operations
운영
---
Book VII
Research
Research / Benchmark
---
Book VIII
Business
사업 전략
---
## 6.4 Constraints
Book은 다른 Book을 포함할 수 없다.
Book은 순환 참조를 가져서는 안 된다.
Book은 독립적인 목적을 가져야 한다.
---
## Architecture Decision
ADR-004
Knowledge를 Book 단위로 분리한다.
---
# Chapter 7
# Domain
---
## 7.1 Definition
Domain은 하나의 책임(Responsibility)을 의미한다.
Domain은 기술이나 조직이 아니라
책임의 경계를 정의한다.
---
## 7.2 Responsibilities
하나의 Domain은 하나의 질문에 답해야 한다.
예시
Foundation
↓
왜 존재하는가?
---
Product
↓
무엇을 만드는가?
---
Design
↓
사용자는 어떻게 경험하는가?
---
Engineering
↓
어떻게 구현하는가?
---
AI
↓
AI는 어떻게 협업하는가?
---
Operations
↓
어떻게 운영하는가?
---
## 7.3 Single Responsibility Principle
하나의 문서는
하나의 Domain만 가진다.
두 Domain을 동시에 설명해서는 안 된다.
예를 들어
Moment Model은
Product Domain이다.
API 문서에 Moment를 정의해서는 안 된다.
API는 Product를 참조한다.
---
## Architecture Decision
ADR-005
Domain은 Responsibility 기준으로 정의한다.
---
# Chapter 8
# Category
---
## 8.1 Definition
Category는
동일한 목적을 가진 Document의 집합이다.
Category는 Domain보다 작고,
Document보다 큰 단위이다.
---
## 8.2 Example
Book
↓
Product
↓
Category
↓
Core Model
↓
Document
↓
Moment Model
---
또 다른 예
Book
↓
Engineering
↓
Category
↓
API
↓
Document
↓
Authentication API
---
## 8.3 Why Category Exists
Category는
문서가 수백 개로 증가해도
탐색성을 유지하기 위해 존재한다.
Category가 없다면
모든 문서는
Domain 아래에 직접 저장된다.
이는 장기적으로 관리 비용을 증가시킨다.
---
## 8.4 Constraints
Category는
다른 Category를 포함하지 않는다.
Category는
Document만 포함한다.
---
## Architecture Decision
ADR-006
Category를 중간 계층으로 채택한다.
---
# Chapter 9
# Document
---
## 9.1 Definition
Document는
Knowledge를 전달하는 최소 독립 단위이다.
Document는
하나의 주제만 설명한다.
---
## 9.2 Responsibilities
Document는
다음을 가져야 한다.
Purpose
Scope
Definitions
Rules
References
Revision History
Status
Owner
---
## 9.3 Single Topic Rule
하나의 Document는
하나의 핵심 주제만 가진다.
예시
올바른 문서
Moment Model
잘못된 문서
Moment + Story + AI + API
---
## 9.4 Reference over Copy
다른 Document를 설명하지 않는다.
Reference를 사용한다.
---
## Architecture Decision
ADR-007
Single Topic Documentation을 채택한다.
---
# Chapter 10
# Chapter
---
## 10.1 Definition
Chapter는
Document 내부의
가장 큰 논리적 구분이다.
Chapter는
독립적인 의미를 가져야 한다.
---
## 10.2 Responsibilities
Chapter는
하나의 Sub Topic을 설명한다.
---
## Example
Moment Model
↓
Chapter
↓
Lifecycle
↓
Section
↓
Creation
---
## Constraints
Chapter는
다른 Document를 참조할 수 있지만
소유할 수 없다.
---
## Architecture Decision
ADR-008
Document는 Chapter로 구성한다.
---
# Chapter 11
# Section
---
## 11.1 Definition
Section은
Document를 구성하는
최소 설명 단위이다.
---
## Section Characteristics
Section은
하나의 질문에 답해야 한다.
예시
What
Why
How
Constraints
Examples
References
---
## Section Rules
Section은
200\~500 단어 내에서
하나의 개념만 설명하는 것을 권장한다.
지나치게 긴 설명은
새로운 Section으로 분리한다.
---
## Architecture Decision
ADR-009
Section을 Documentation의 최소 설명 단위로 정의한다.
---
## Summary
RoRo Knowledge Hierarchy
Book
↓
Domain
↓
Category
↓
Document
↓
Chapter
↓
Section
↓
Rule
↓
ADR
---
## Related Documents
001_Document_Philosophy.md
003_Document_Lifecycle.md
020_Architecture_Decision_Record.md
# Part III
# Knowledge Relationship Model
---
# Chapter 12
# Reference Model
## 12.1 Principle
RoRo Documentation은
복사(Copy)가 아니라
참조(Reference)를 기반으로 한다.
같은 Knowledge를
둘 이상의 문서가
직접 정의해서는 안 된다.
Knowledge는
한 번만 정의하고
필요한 문서는
이를 참조한다.
---
## 12.2 Why Reference
Reference는
Knowledge Duplication을 제거한다.
동일한 내용을
세 곳에서 수정하는 대신
원본 하나만 수정한다.
모든 참조 문서는
자동으로 동일한 의미를 유지한다.
---
## 12.3 Single Definition Principle
모든 핵심 개념은
단 하나의 공식 정의를 가진다.
예)
Moment
↓
143_Moment_Model.md
Story
↓
144_Story_Model.md
Trip
↓
141_Trip_Model.md
Photo
↓
145_Photo_Model.md
다른 문서는
정의를 복사하지 않는다.
---
## 12.4 Reference Types
RoRo는 네 가지 Reference를 정의한다.
### Definition Reference
공식 정의를 참조한다.
---
### Policy Reference
정책을 참조한다.
---
### Architecture Reference
기술 구조를 참조한다.
---
### Historical Reference
과거 의사결정을 참조한다.
---
## Constitution Rules
Rule 12-1
동일한 정의는
둘 이상의 문서에 존재해서는 안 된다.
Rule 12-2
Reference는
Copy보다 항상 우선한다.
---
## Architecture Decision
ADR-010
Reference-based Knowledge Architecture를 채택한다.
---
# Chapter 13
# Dependency Rules
---
## 13.1 Principle
모든 문서는
의존성(Dependency)을 가진다.
그러나
순환 의존성(Circular Dependency)은
허용하지 않는다.
---
## Dependency Direction
Constitution
↓
Philosophy
↓
Standard
↓
Specification
↓
Guide
↓
Reference
상위 문서는
하위 문서를 참조하지 않는다.
---
## Allowed Dependency
Foundation
↓
Product
↓
Engineering
↓
Implementation
---
## Forbidden Dependency
Engineering
↓
Foundation 변경
Engineering
↓
Product 재정의
Design
↓
Vision 변경
---
## Dependency Levels
### Hard Dependency
없으면 이해할 수 없다.
---
### Soft Dependency
있으면 이해하기 쉽다.
---
### Informational Dependency
추가 정보 제공.
---
## Architecture Decision
ADR-011
Knowledge Dependency Model을 채택한다.
---
# Chapter 14
# Knowledge Graph
---
## Principle
RoRo Documentation은
저장은 Tree,
관계는 Graph를 사용한다.
---
## Why Graph
하나의 Document는
여러 Document와 연결된다.
예)
Moment Model
↓
Story
↓
Timeline
↓
Trip
↓
Media
↓
Location
↓
AI Summary
↓
Database
↓
API
↓
UX
↓
Privacy
↓
Sharing
이는
Tree만으로 표현할 수 없다.
---
## Node
Graph의 Node는
Document이다.
---
## Edge
Edge는
Reference이다.
---
## Relationship Types
Defines
Uses
Depends On
Related To
Deprecated By
Supersedes
Derived From
References
---
## Graph Principles
Graph는
순환 정의를 만들지 않는다.
Graph는
Source of Truth를 변경하지 않는다.
Graph는
Reference만 표현한다.
---
## Example
Moment Model
Defines
↓
Moment
Timeline
Uses
↓
Moment
Story
Uses
↓
Moment
API
Uses
↓
Moment
Database
Uses
↓
Moment
Definition은
항상 하나이다.
---
## Architecture Decision
ADR-012
Knowledge Graph를 공식 Relationship Model로 채택한다.
---
# Chapter 15
# Cross References
---
## Principle
모든 중요한 문서는
다른 문서와 연결된다.
고립된 Document는
Knowledge Base의 일부가 아니다.
---
## Required References
각 Document는
다음을 가진다.
Related Documents
Referenced By
Depends On
Related ADR
Related Standards
Related Policies
---
## Reference Quality
좋은 Reference는
다음을 만족한다.
정확하다.
최신이다.
단방향이 아니다.
추적 가능하다.
---
## Broken Reference
다음은 오류이다.
존재하지 않는 문서 참조
삭제된 ADR 참조
잘못된 버전 참조
순환 참조
---
## Constitution Rules
Rule 15-1
모든 핵심 문서는
Related Documents를 가진다.
Rule 15-2
Reference는
검증 가능해야 한다.
Rule 15-3
Broken Reference는
Documentation Error이다.
---
## Architecture Decision
ADR-013
Cross Reference Validation을 프로젝트 표준으로 채택한다.
---
## Summary
Knowledge Storage
↓
Tree
Knowledge Relationship
↓
Graph
Knowledge Maintenance
↓
Reference
Knowledge Integrity
↓
Dependency Rules
---
## Related Documents
001_Document_Philosophy.md
003_Document_Lifecycle.md
020_Architecture_Decision_Record.md
104_Context_Engineering.md
# Part IV
# Workspace Architecture
---
# Chapter 16
# Physical Workspace Abstraction
## 16.1 Purpose
RoRo Product Knowledge Base는 논리 구조(Logical Structure)와 물리 구조(Physical Workspace)를 명확하게 분리한다.
논리 구조는 제품 지식의 의미를 정의한다.
물리 구조는 해당 지식을 저장하고 관리하는 구현 방식이다.
논리 구조는 변경되지 않는다.
물리 구조는 프로젝트의 성장과 도구의 변화에 따라 변경될 수 있다.
---
## 16.2 Principle
Knowledge는 Tool보다 오래 살아야 한다.
Workspace는 Knowledge를 담는 Container일 뿐이다.
Workspace는 Source of Truth가 아니다.
Source of Truth는 Knowledge 자체이다.
---
## 16.3 Logical vs Physical
Logical Structure
Book
↓
Domain
↓
Category
↓
Document
↓
Chapter
↓
Section
↓
Rule
↓
ADR
Physical Workspace
Notion
Git Repository
Confluence
SharePoint
Google Drive
Local Filesystem
Cloud Storage
---
## 16.4 Independence
Knowledge Architecture는 특정 도구에 종속되지 않는다.
Workspace가 변경되더라도 다음 요소는 변경되지 않는다.
- Document ID
- Domain
- Category
- Knowledge Relationship
- References
- ADR
- Product DNA
---
## 16.5 Migration Principle
Workspace Migration은 저장 위치를 변경하는 작업이다.
Knowledge Migration이 아니다.
문서의 의미와 관계는 유지되어야 한다.
---
## Constitution Rules
Rule 16-1
모든 Knowledge는 Tool Independent 해야 한다.
Rule 16-2
Workspace는 교체 가능해야 한다.
Rule 16-3
Knowledge Architecture는 Workspace보다 우선한다.
---
## Architecture Decision
ADR-014
Logical Knowledge Architecture와 Physical Workspace를 분리한다.
---
# Chapter 17
# Workspace Mapping
## 17.1 Purpose
Workspace Mapping은 Logical Knowledge Architecture를 실제 작업 환경에 연결하는 규칙을 정의한다.
동일한 Logical Structure는 다양한 Workspace에 매핑될 수 있다.
---
## 17.2 Mapping Model
Logical Book
↓
Physical Workspace
Logical Document
↓
Workspace Page
Logical Relationship
↓
Workspace Relation
Logical Metadata
↓
Workspace Properties
---
## 17.3 Current Workspace
현재 RoRo 프로젝트의 Primary Workspace는 Notion이다.
Notion은 Product Knowledge를 관리하기 위한 공식 협업 공간이다.
단, Notion은 Knowledge의 정의를 변경하는 기준이 아니라 Knowledge를 표현하는 수단이다.
---
## 17.4 Future Workspace
RoRo는 다음 Workspace를 지원할 수 있다.
- GitHub Repository
- Markdown Repository
- Confluence
- Obsidian
- SharePoint
- 기타 Knowledge Platform
Workspace의 변경은 Knowledge Architecture의 변경을 의미하지 않는다.
---
## 17.5 Mapping Rule
모든 Workspace는 다음 항목을 동일하게 유지해야 한다.
- Document ID
- Title
- Version
- Status
- Related Documents
- Domain
- Category
---
## Constitution Rules
Rule 17-1
Workspace는 Knowledge를 재정의해서는 안 된다.
Rule 17-2
Workspace 간 이동 시 Document Identity를 유지한다.
---
## Architecture Decision
ADR-015
Workspace Mapping Layer를 공식 채택한다.
---
# Chapter 18
# Document Identity
## 18.1 Purpose
모든 Document는 저장 위치와 관계없이 고유한 Identity를 가진다.
Identity는 문서의 이름이 아니라 문서의 존재 자체를 식별한다.
---
## 18.2 Identity Components
Document Identity는 다음 요소로 구성된다.
- Document ID
- Title
- Domain
- Category
- Version
- Status
이 조합은 문서를 유일하게 식별한다.
---
## 18.3 Persistence
Workspace가 변경되어도 Document Identity는 변경되지 않는다.
예를 들어 동일한 문서는 다음 환경에서 같은 Identity를 가진다.
- Notion
- GitHub
- Markdown Repository
- Local Archive
---
## 18.4 Identifier Rule
Document ID는 재사용하지 않는다.
삭제된 문서의 ID도 영구적으로 보존한다.
---
## Constitution Rules
Rule 18-1
모든 공식 문서는 Document ID를 가진다.
Rule 18-2
Document ID는 영구 식별자(Persistent Identifier)이다.
Rule 18-3
Document ID는 저장 위치와 독립적이다.
---
## Architecture Decision
ADR-016
Persistent Document Identity를 채택한다.
---
# Chapter 19
# Document Metadata
## 19.1 Purpose
Metadata는 Document를 설명하는 구조화된 정보이다.
Metadata는 사람이 읽기 위한 설명이 아니라 사람과 AI가 문서를 이해하기 위한 공통 인터페이스이다.
---
## 19.2 Required Metadata
모든 공식 문서는 다음 Metadata를 가진다.
- Document ID
- Title
- Book
- Domain
- Category
- Version
- Status
- Owner
- Created Date
- Last Updated
- Related Documents
- Related ADR
- Tags
---
## 19.3 Optional Metadata
필요한 경우 다음 Metadata를 추가할 수 있다.
- Sprint
- Milestone
- Epic
- Feature
- Priority
- Reviewer
- AI Context Tags
---
## 19.4 Workspace Mapping
Notion에서는 Metadata를 Page Properties로 관리한다.
향후 GitHub에서는 Front Matter 또는 별도의 Metadata Index를 사용할 수 있다.
표현 방식은 달라도 의미는 동일해야 한다.
---
## Constitution Rules
Rule 19-1
모든 공식 문서는 Required Metadata를 포함한다.
Rule 19-2
Metadata는 문서 내용과 일관성을 유지해야 한다.
Rule 19-3
Metadata 변경도 Revision History에 기록한다.
---
## Architecture Decision
ADR-017
Structured Document Metadata를 프로젝트 표준으로 채택한다.
---
## Related Documents
001_Document_Philosophy.md
003_Document_Lifecycle.md
107_Notion_Workspace.md
108_Git_Repository.md
020_Architecture_Decision_Record.md
# Part V
# Navigation Architecture
---
# Chapter 20
# Table of Contents
## 20.1 Purpose
Table of Contents(이하 TOC)는 Knowledge Base의 공식 탐색 시작점이다.
TOC는 문서를 저장하지 않는다.
TOC는 문서를 연결한다.
---
## 20.2 Principles
TOC는 다음 원칙을 따른다.
- 계층 구조를 반영한다.
- 문서를 중복 나열하지 않는다.
- 최신 상태를 유지한다.
- 논리 구조를 표현한다.
---
## 20.3 Levels
RoRo는 다음 수준의 TOC를 정의한다.
Global TOC
↓
Book TOC
↓
Domain TOC
↓
Category TOC
↓
Document TOC
---
## 20.4 Navigation Rules
모든 공식 문서는
상위 TOC를 통해 도달 가능해야 한다.
고립된 문서는 허용하지 않는다.
---
## Architecture Decision
ADR-018
계층형 TOC를 공식 탐색 구조로 채택한다.
---
# Chapter 21
# Index
## 21.1 Purpose
Index는 Knowledge를 검색하기 위한 구조이다.
TOC는 구조를 보여주고,
Index는 접근 경로를 제공한다.
---
## 21.2 Index Types
RoRo는 다음 Index를 정의한다.
Document Index
Domain Index
ADR Index
Glossary Index
Feature Index
Model Index
Policy Index
---
## 21.3 Search Principles
하나의 Document는
복수의 Index에 포함될 수 있다.
Index는 문서를 복사하지 않는다.
Reference만 유지한다.
---
## 21.4 Index Integrity
Index는
항상 최신 상태를 유지해야 한다.
존재하지 않는 문서를 포함해서는 안 된다.
---
## Constitution Rules
Rule 21-1
Index는 Source of Truth가 아니다.
Rule 21-2
Index는 Navigation Layer이다.
---
## Architecture Decision
ADR-019
다중 Index 구조를 채택한다.
---
# Chapter 22
# Searchability
## 22.1 Principle
Knowledge는
찾을 수 있어야 존재하는 것이다.
검색되지 않는 Knowledge는
실질적으로 존재하지 않는 것과 같다.
---
## 22.2 Search Keys
모든 Document는
다음 요소를 통해 검색 가능해야 한다.
- Title
- Document ID
- Tags
- Domain
- Category
- Related Documents
- Keywords
---
## 22.3 Human Search
사용자는
제목,
구조,
목차를 통해 문서를 찾는다.
---
## 22.4 AI Search
AI는
Metadata,
Reference,
Context,
Semantic Relationship를 통해 문서를 찾는다.
---
## 22.5 Search Quality
좋은 검색은
정확성(Precision)과
재현율(Recall)을
균형 있게 만족해야 한다.
---
## Constitution Rules
Rule 22-1
모든 공식 문서는 검색 가능해야 한다.
Rule 22-2
검색을 위해 문서를 중복 생성해서는 안 된다.
---
## Architecture Decision
ADR-020
Search-first Knowledge Architecture를 채택한다.
---
# Chapter 23
# AI Navigation
## 23.1 Purpose
AI Navigation은
AI Agent가 Knowledge Base를 탐색하는 공식 규칙을 정의한다.
---
## 23.2 Navigation Order
AI는 다음 순서로 Context를 탐색한다.
1.
Document Metadata
↓
1.
Related Documents
↓
1.
Referenced Documents
↓
1.
Related ADR
↓
1.
Glossary
↓
1.
Constitution
---
## 23.3 Context Assembly
AI는 필요한 Context만 조합한다.
전체 Repository를
무조건 읽지 않는다.
---
## 23.4 Context Priority
Context 우선순위는 다음과 같다.
Constitution
↓
Standards
↓
Specifications
↓
Guides
↓
Examples
---
## 23.5 Context Integrity
AI는
복수의 정의가 발견되면
Source of Truth를 우선한다.
충돌이 발생하면
ADR을 확인한다.
---
## Constitution Rules
Rule 23-1
AI는 Source of Truth를 우선한다.
Rule 23-2
AI는 Reference를 따라 Context를 확장한다.
Rule 23-3
AI는 Definition을 재생성하지 않는다.
---
## Architecture Decision
ADR-021
AI Navigation Model을 공식 채택한다.
---
## Related Documents
001_Document_Philosophy.md
003_Document_Lifecycle.md
020_Architecture_Decision_Record.md
103_AI_Governance.md
104_Context_Engineering.md
# Part VI
# Knowledge Quality Specification
---
# Chapter 24
# Knowledge Quality
## 24.1 Purpose
Knowledge Quality는 RoRo Product Knowledge Base에 포함되는 모든 문서의 최소 품질 기준(Minimum Quality Standard)을 정의한다.
모든 공식 문서는 본 장의 기준을 충족해야 한다.
---
## 24.2 Quality Principles
좋은 Documentation은 다음 특성을 가진다.
### Accuracy
내용은 사실에 기반해야 한다.
추정이나 가정은 명확히 구분한다.
---
### Completeness
핵심 내용을 누락하지 않는다.
참조만으로 이해할 수 없는 문서는 불완전한 문서로 간주한다.
---
### Consistency
동일한 용어는 항상 동일한 의미를 가진다.
동일한 규칙은 모든 문서에 일관되게 적용된다.
---
### Traceability
모든 중요한 의사결정은 추적 가능해야 한다.
필요 시 ADR 또는 관련 문서를 통해 근거를 확인할 수 있어야 한다.
---
### Maintainability
문서는 변경과 확장을 고려하여 작성한다.
부분 수정이 전체 구조를 훼손해서는 안 된다.
---
### AI Readability
문서는 사람이 읽기 쉽고 AI가 해석하기 쉬워야 한다.
모호한 표현보다 명확한 구조를 우선한다.
---
## 24.3 Quality Score
공식 문서는 다음 항목을 자체 점검한다.
- Accuracy
- Completeness
- Consistency
- Traceability
- Maintainability
- AI Readability
각 항목은 Pass 또는 Fail로 평가한다.
---
## Constitution Rules
Rule 24-1
품질 기준을 충족하지 못한 문서는 공식 문서로 승인하지 않는다.
Rule 24-2
모든 문서는 AI와 사람이 동일하게 이해할 수 있어야 한다.
---
## Architecture Decision
ADR-022
Knowledge Quality Standard를 프로젝트 표준으로 채택한다.
---
# Chapter 25
# Documentation Integrity
## 25.1 Purpose
Integrity는 Documentation의 신뢰성을 유지하기 위한 규칙을 정의한다.
문서 간 충돌은 Product Knowledge의 무결성을 훼손한다.
---
## 25.2 Integrity Principles
문서는 다음 조건을 만족해야 한다.
- 중복 정의가 없어야 한다.
- Source of Truth를 유지해야 한다.
- Reference는 유효해야 한다.
- Metadata는 최신 상태여야 한다.
- Revision History는 누락되지 않아야 한다.
---
## 25.3 Integrity Violations
다음은 Documentation Error로 정의한다.
- 동일 개념의 중복 정의
- 순환 참조
- 끊어진 참조(Broken Reference)
- 오래된 Metadata
- 존재하지 않는 ADR 참조
- 잘못된 Document ID
---
## 25.4 Integrity Recovery
무결성 오류가 발견되면 다음 순서로 처리한다.
1. 오류 확인
2. Source of Truth 확인
3. 중복 제거
4. Reference 수정
5. Revision History 기록
---
## Constitution Rules
Rule 25-1
Source of Truth는 항상 하나여야 한다.
Rule 25-2
무결성 오류를 발견하면 즉시 수정한다.
---
## Architecture Decision
ADR-023
Documentation Integrity Policy를 공식 채택한다.
---
# Chapter 26
# Validation Rules
## 26.1 Purpose
Validation은 문서가 구조적·논리적 기준을 충족하는지 확인하는 절차이다.
---
## 26.2 Required Validation
모든 공식 문서는 다음 항목을 검증한다.
- Document ID 존재
- Metadata 존재
- Related Documents 확인
- Reference 유효성
- ADR 연결 여부
- Status 확인
---
## 26.3 Optional Validation
필요한 경우 다음을 추가 검증한다.
- 용어 일관성
- 태그 일관성
- AI Context 품질
- 검색 가능성
---
## 26.4 Validation Frequency
Validation은 다음 시점에 수행한다.
- 신규 문서 생성
- 주요 수정
- 승인 전
- 정기 품질 점검
---
## Constitution Rules
Rule 26-1
검증되지 않은 문서는 공식 Repository에 포함하지 않는다.
Rule 26-2
Validation 결과는 재현 가능해야 한다.
---
## Architecture Decision
ADR-024
Documentation Validation Process를 채택한다.
---
# Chapter 27
# Governance
## 27.1 Purpose
Governance는 Product Knowledge를 지속적으로 관리하기 위한 운영 원칙을 정의한다.
---
## 27.2 Governance Roles
다음 역할을 정의한다.
### Product Owner
Knowledge의 최종 책임자
---
### Contributor
문서를 작성하거나 수정한다.
---
### Reviewer
문서의 품질과 일관성을 검토한다.
---
### AI Agent
초안 작성, 구조 제안, 품질 점검을 지원한다.
최종 승인 권한은 가지지 않는다.
---
## 27.3 Change Management
모든 중요한 변경은 다음 절차를 따른다.
1. Proposal
2. Discussion
3. Review
4. Approval
5. Documentation Update
6. Implementation
---
## 27.4 Governance Principles
- 사람이 최종 승인한다.
- AI는 협업자이다.
- 모든 변경은 추적 가능해야 한다.
- 중요한 변경은 ADR로 기록한다.
---
## Constitution Rules
Rule 27-1
공식 문서는 승인 없이 Published 상태로 변경할 수 없다.
Rule 27-2
Governance는 프로젝트 규모와 관계없이 동일하게 적용한다.
---
## Architecture Decision
ADR-025
Knowledge Governance Model을 프로젝트 표준으로 채택한다.
---
## Related Documents
001_Document_Philosophy.md
003_Document_Lifecycle.md
020_Architecture_Decision_Record.md
021_Project_History.md
103_AI_Governance.md
# Part VII
# Evolution & Architecture Principles
---
# Chapter 28
# Scalability
## 28.1 Purpose
RoRo Knowledge Architecture는 현재 프로젝트만을 위한 구조가 아니다.
제품의 성장, 조직의 확장, AI의 발전을 고려한 장기 구조(Long-term Architecture)이다.
---
## 28.2 Scalability Dimensions
Knowledge Architecture는 다음 방향으로 확장 가능해야 한다.
### Document Scale
문서 수가 증가하여도 기존 구조를 변경하지 않는다.
새로운 문서는 기존 계층에 추가된다.
---
### Team Scale
프로젝트 참여 인원이 증가하여도 동일한 구조를 사용한다.
팀마다 별도의 구조를 만들지 않는다.
---
### Product Scale
MVP에서 정식 서비스까지 동일한 Architecture를 유지한다.
기능이 증가해도 Foundation은 변경하지 않는다.
---
### AI Scale
새로운 AI Agent가 추가되어도 동일한 Context Architecture를 사용한다.
AI마다 별도의 Documentation을 만들지 않는다.
---
### Organization Scale
프로젝트가 하나의 제품에서 여러 제품군(Product Portfolio)으로 확장되더라도 동일한 구조를 유지한다.
Book과 Domain은 확장 가능하지만 기존 의미는 변경하지 않는다.
---
## 28.3 Scalability Principles
확장을 위해 기존 구조를 파괴하지 않는다.
새로운 요구사항은 기존 Architecture를 확장하는 방식으로 수용한다.
---
## Constitution Rules
Rule 28-1
확장은 허용되지만 기존 구조의 의미는 변경하지 않는다.
Rule 28-2
새로운 Domain은 기존 Domain의 책임을 침범해서는 안 된다.
---
## Architecture Decision
ADR-026
Scalable Knowledge Architecture를 프로젝트 표준으로 채택한다.
---
# Chapter 29
# Evolution & Migration
## 29.1 Purpose
Knowledge는 지속적으로 발전한다.
그러나 발전은 무질서한 변경(Change)이 아니라 관리되는 진화(Evolution)여야 한다.
---
## 29.2 Evolution Principles
RoRo는 다음 원칙을 따른다.
- 기존 Knowledge를 존중한다.
- History를 삭제하지 않는다.
- 변경 이유를 기록한다.
- Source of Truth를 유지한다.
---
## 29.3 Migration
Migration은 Workspace나 Tool의 변경을 의미한다.
Migration 과정에서 다음 요소는 유지되어야 한다.
- Document Identity
- Knowledge Relationship
- Reference
- Metadata
- Revision History
Migration은 기술 이전이지 Knowledge의 재작성(Rewriting)이 아니다.
---
## 29.4 Deprecation
문서를 더 이상 사용하지 않더라도 즉시 삭제하지 않는다.
Deprecated 상태로 전환한 후 Archive 정책에 따라 관리한다.
삭제는 최후의 수단이다.
---
## Constitution Rules
Rule 29-1
모든 Migration은 Knowledge Integrity를 유지해야 한다.
Rule 29-2
History는 삭제보다 보존을 우선한다.
---
## Architecture Decision
ADR-027
Knowledge Evolution Policy를 프로젝트 표준으로 채택한다.
---
# Chapter 30
# Final Architecture Principles
## 30.1 Core Principles
RoRo Knowledge Architecture는 다음 원칙을 기반으로 한다.
### Knowledge Before Tool
도구는 Knowledge를 담는 수단이다.
Knowledge가 도구보다 우선한다.
---
### Structure Before Scale
규모보다 구조를 먼저 설계한다.
좋은 구조는 성장을 견딘다.
---
### Reference Before Copy
동일한 Knowledge를 반복 정의하지 않는다.
Reference를 통해 연결한다.
---
### Identity Before Location
문서는 저장 위치가 아니라 Identity로 관리한다.
Workspace는 변경될 수 있다.
Identity는 변경되지 않는다.
---
### Relationship Before Navigation
문서는 고립된 정보가 아니다.
Knowledge는 서로 연결되어 하나의 시스템을 구성한다.
---
### Human Before AI
AI는 Product Knowledge를 이해하고 활용하는 협업자이다.
최종 판단과 승인 권한은 사람에게 있다.
---
### Evolution Before Replacement
기존 구조를 폐기하기보다 발전시킨다.
제품은 누적된 Knowledge 위에서 성장한다.
---
## 30.2 Final Declaration
RoRo Documentation은 단순한 문서 집합이 아니다.
RoRo Knowledge Architecture는 제품의 구조를 정의하고,
프로젝트의 기억을 보존하며,
사람과 AI가 동일한 기반 위에서 협업할 수 있도록 하는 공통 언어이다.
모든 문서는 이 구조를 존중한다.
모든 AI는 이 구조를 이해한다.
모든 의사결정은 이 구조 안에서 추적된다.
RoRo Product Genome은 이 Architecture 위에서 성장한다.
---
## Final Constitution Rules
Rule 30-1
모든 공식 문서는 본 Architecture를 따른다.
Rule 30-2
Architecture의 변경은 ADR 승인 없이 수행할 수 없다.
Rule 30-3
Knowledge는 프로젝트의 가장 중요한 자산으로 간주한다.
---
## Final Architecture Decisions
ADR-028
RoRo Knowledge Architecture Specification v1.0을 공식 승인한다.
ADR-029
본 문서를 Product Knowledge Base의 구조적 표준으로 채택한다.
ADR-030
향후 모든 Documentation은 본 문서를 준수한다.
---
# End of Document
Document Status: Approved
Version: 1.0
Next Document:
003_Document_Lifecycle.md
