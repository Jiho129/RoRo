<!-- Source: Notion page [032 AI Design Patterns Catalog](https://app.notion.com/p/3aadff1c1f74802d8884dfbfd0eee158?pvs=204). Last edited 2026-08-07T01:53:23.126Z. Extracted as an archival segment from one combined page. -->

---
document_id: DOC-032-PART-II
parent_document:
- DOC-032
title: AI Design Pattern Catalog - Pattern Specification Standard
book: Product Bible
domain: Artificial Intelligence
category: Design Pattern Standard
version: 1.0.0
status: Draft
owner: Chief AI Product Officer
created_date: 2026-07-27
related_documents:
- DOC-031
- DOC-032-PART-I
tags:
- ai
- engineering
- design-pattern
- standard
context_scope: Global
## summary:
Defines the official specification, metadata, lifecycle,
governance, naming convention, quality requirements,
and documentation standard for all AI Design Patterns.
# DOC-032
# AI Design Pattern Catalog
## Part II
# Pattern Specification Standard
Version 1.0.0
Status : Draft
---
archive_source: Notion
source_page_id: 3aadff1c-1f74-802d-8884-dfbfd0eee158
source_page_url: https://app.notion.com/p/3aadff1c1f74802d8884dfbfd0eee158?pvs=204

# 1. Purpose
본 문서는 AI Design Pattern의 공식 작성 규격(Standard Specification)을 정의한다.
모든 Pattern은 본 문서의 규격을 반드시 준수해야 한다.
본 규격의 목적은 다음과 같다.
- Pattern 품질 표준화
- Pattern 재사용성 향상
- Pattern 검색성 향상
- Pattern 유지보수성 확보
- Engineering Documentation 통일
---
# 2. Scope
본 규격은 다음 문서에 적용된다.
- DOC-032 AI Design Pattern Catalog
- DOC-033 Prompt Pattern Library
- DOC-034 Agent Pattern Catalog
- DOC-035 Architecture Reference
- DOC-036 Engineering Standards
---
# 3. Pattern Definition
Pattern은 반복적으로 발생하는 설계 문제에 대해
검증된 해결 방법을 정의한 재사용 가능한 설계 단위이다.
Pattern은
- 코드가 아니다.
- Prompt가 아니다.
- Architecture만도 아니다.
Pattern은
문제
↓
구조
↓
행동
↓
책임
↓
적용 기준
을 정의하는 설계 표준이다.
---
# 4. Pattern Classification
모든 Pattern은 아래 네 가지 유형 중 하나 이상을 가진다.
| Type | Description |
| --- | --- |
| Structural | 시스템 구조 정의 |
| Behavioral | 실행 흐름 정의 |
| Coordination | Agent 협업 정의 |
| Operational | 운영 방식 정의 |
복합 Pattern은 여러 Type을 동시에 가질 수 있다.
---
# 5. Pattern Identifier Standard
모든 Pattern은 고유 ID를 가진다.
형식
AI-PATTERN-XXX
예)
AI-PATTERN-001
AI-PATTERN-002
AI-PATTERN-103
ID는 절대 변경하지 않는다.
---
# 6. Pattern Naming Convention
Pattern 이름은
명확하고
역할 중심으로 작성한다.
좋은 예
- Orchestrator Pattern
- Reviewer Pattern
- Layered Context Pattern
- Retry Pattern
나쁜 예
- Smart Pattern
- AI Pattern
- Better Prompt
---
# 7. Required Metadata
모든 Pattern은 아래 Metadata를 포함해야 한다.
| Field | Required |
| --- | --- |
| Pattern ID | ✓ |
| Name | ✓ |
| Version | ✓ |
| Category | ✓ |
| Status | ✓ |
| Owner | ✓ |
| Last Updated | ✓ |
| Related Patterns | ✓ |
---
# 8. Standard Document Structure
모든 Pattern은 동일한 구조를 사용한다.
## 1.
Purpose
---
## 2.
Problem
---
## 3.
Context
---
## 4.
When to Use
---
## 5.
When NOT to Use
---
## 6.
Architecture
---
## 7.
Sequence Flow
---
## 8.
Implementation Guideline
---
## 9.
Advantages
---
## 10.
Disadvantages
---
## 11.
Trade-offs
---
## 12.
Metrics
---
## 13.
Checklist
---
## 14.
Anti-pattern
---
## 15.
RoRo Example
---
## 16.
Related Patterns
---
# 9. Architecture Representation Standard
모든 Pattern은
ASCII Diagram을 반드시 포함한다.
예
```plain text
User

↓

Planner

↓

Worker

↓

Reviewer

↓

Output
```
복잡한 Diagram은
Mermaid를 추가로 사용할 수 있다.
---
# 10. Sequence Standard
실행 흐름은
반드시
Top-down
순서로 작성한다.
예
```plain text
Request

↓

Planning

↓

Execution

↓

Validation

↓

Output
```
---
# 11. Implementation Standard
Implementation은
기술이 아니라
원칙 중심으로 작성한다.
포함 내용
- Required Components
- Dependency
- Configuration
- Interface
- Error Handling
---
# 12. Pattern Quality Requirements
모든 Pattern은 아래 조건을 만족해야 한다.
- 재사용 가능
- 독립 테스트 가능
- 교체 가능
- 확장 가능
- 문서화 가능
---
# 13. Pattern Lifecycle
Pattern은 다음 생명주기를 가진다.
```plain text
Draft

↓

Review

↓

Prototype

↓

Validation

↓

Approved

↓

Production

↓

Deprecated

↓

Archived
```
---
# 14. Versioning Policy
Version은 Semantic Version을 따른다.
예
1.0.0
Major
↓
Architecture 변경
Minor
↓
기능 추가
Patch
↓
오탈자
설명 수정
---
# 15. Approval Process
새로운 Pattern은
다음 절차를 따른다.
```plain text
Proposal

↓

Architecture Review

↓

Prototype

↓

Pilot

↓

Approval

↓

Catalog
```
---
# 16. Pattern Dependency Rule
Pattern은
다른 Pattern에 의존할 수 있다.
하지만
순환 의존(Circular Dependency)은 금지한다.
허용
```plain text
Planner

↓

Worker

↓

Reviewer
```
금지
```plain text
Planner

↓

Worker

↓

Planner
```
---
# 17. Pattern Review Checklist
Architecture
□ 역할이 명확한가
□ 책임이 하나인가
□ 재사용 가능한가
□ 독립 테스트 가능한가
□ Diagram이 존재하는가
□ Anti-pattern이 정의되었는가
□ RoRo Example이 존재하는가
---
# 18. Pattern Catalog Governance
Catalog 관리 원칙
- Pattern 중복 생성 금지
- Pattern 변경 이력 관리
- Deprecated Pattern 표시
- Related Pattern 유지
- Version 관리
---
# 19. Required Artifacts
본 규격에서 요구하는 산출물
- Pattern Registry
- Pattern Review Checklist
- Pattern Approval Record
- Pattern Dependency Matrix
- Pattern Version History
---
# 20. References
- DOC-031 AI Product Framework
- DOC-032 Part I Introduction & Pattern Philosophy
---
# Document Information
Document ID
DOC-032-PART-II
Document
AI Design Pattern Catalog
Part
II
Title
Pattern Specification Standard
Version
1.0.0
Status
Draft
Next
DOC-032 Part III
Interaction Patterns
