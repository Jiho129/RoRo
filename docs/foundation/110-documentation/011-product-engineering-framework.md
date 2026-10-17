<!-- Source: Notion page [011 Product Engineering Framework](https://app.notion.com/p/3a9dff1c1f748009847bd77af2ec1878?pvs=204). Page ID: 3a9dff1c-1f74-8009-847b-d77af2ec1878. Path: My Travel - RoRo / 100 📖 Foundation / 110 Documentation. Last edited: 2026-07-26T07:41:19.403Z. -->

# 011 Product Engineering Framework

---
document_id: DOC-011-PART-I
parent_document:
- DOC-011
title: Engineering Manifesto
book: Foundation
domain: Product Engineering
category: Operating Framework
version: 1.0.0
status: Draft
owner: Chief Technology Officer
created_date: 2026-07-26
related_documents:
- DOC-006
- DOC-009
- DOC-010
tags:
- engineering
- manifesto
- software
- architecture
- ai-engineering
context_scope:
Global
## summary:
Defines the philosophy, principles, values, ethics, and decision model that govern engineering activities across the product lifecycle.
# 011 Product Engineering Framework
# Part I - Engineering Manifesto
Version 1.0.0
Status: Draft
---
# 1. Purpose
본 문서는 RoRo Product Engineering의 철학과 운영 원칙을 정의한다.
RoRo에서 Engineering은 단순히 소프트웨어를 개발하는 활동이 아니다.
Engineering은 제품의 의도(Intent)를 신뢰할 수 있고, 확장 가능하며, 유지보수 가능한 소프트웨어 시스템으로 구현하는 과정이다.
---
# 2. Engineering Definition
Engineering은 다음을 수행한다.
- Product Strategy를 구현한다.
- Discovery 결과를 현실화한다.
- Design을 동작하는 제품으로 만든다.
- 사용자의 문제를 해결하는 시스템을 구축한다.
- 지속 가능한 기술 자산을 만든다.
Engineering의 결과물은 코드(Code)가 아니라 **제품(Product)** 이다.
---
# 3. Engineering Philosophy
좋은 Engineering은 복잡한 기술을 만드는 것이 아니라 복잡함을 제거하는 것이다.
기술은 사용자에게 보이지 않아야 한다.
사용자가 느끼는 것은 기능이 아니라 경험이며, Engineering은 그 경험을 안정적으로 제공해야 한다.
---
# 4. Engineering Values
RoRo Engineering은 다음 가치를 따른다.
- User Value First
- Simplicity over Complexity
- Reliability over Cleverness
- Maintainability over Speed
- Automation by Default
- Security by Design
- Continuous Learning
---
# 5. Engineering Principles
## Principle 1
Every Feature Must Have a User Purpose
모든 기능은 명확한 사용자 가치를 가져야 한다.
---
## Principle 2
Architecture Before Implementation
구현보다 구조를 먼저 설계한다.
---
## Principle 3
Readable Code Wins
읽기 쉬운 코드는 장기적인 생산성을 높인다.
---
## Principle 4
Automate Repetitive Work
반복 작업은 자동화를 우선한다.
---
## Principle 5
Measure Before Optimize
측정 없는 최적화는 수행하지 않는다.
---
## Principle 6
Build for Change
변화를 수용할 수 있는 구조를 만든다.
---
## Principle 7
Engineering Supports Product
기술은 제품 목표를 지원하기 위한 수단이다.
---
# 6. Engineering Decision Model
모든 기술적 의사결정은 다음 순서를 따른다.
```plain text
User Value

↓

Business Value

↓

Architecture

↓

Implementation

↓

Optimization
```
기술적 우수성보다 사용자 가치와 제품 목표를 우선한다.
---
# 7. Engineering Ethics
모든 Engineering 활동은 다음 기준을 따른다.
- 사용자 데이터를 존중한다.
- 보안을 기본값으로 설계한다.
- 장애를 숨기지 않는다.
- 품질 문제를 투명하게 공유한다.
- 기술 부채를 지속적으로 관리한다.
- AI 활용 시 책임성을 유지한다.
---
# 8. AI-assisted Engineering
AI는 Engineering의 생산성을 높이는 도구이다.
AI는 다음 활동을 지원할 수 있다.
- Code Generation
- Refactoring
- Documentation
- Test Generation
- Static Analysis
- Architecture Review
- Debugging Assistance
AI가 생성한 결과물도 사람과 동일한 품질 기준을 충족해야 한다.
---
# 9. Engineering Success Metrics
Engineering의 성공은 다음 기준으로 평가한다.
| KPI | Description |
| --- | --- |
| Product Reliability | 서비스 안정성 |
| Deployment Frequency | 배포 빈도 |
| Change Failure Rate | 변경 실패율 |
| Mean Time to Recovery | 평균 복구 시간 |
| Code Maintainability | 유지보수성 |
| Engineering Velocity | 개발 생산성 |
| Customer Impact | 사용자 가치 |
---
# 10. Anti Patterns
## Anti Pattern 1
기술 자체를 목표로 삼는다.
---
## Anti Pattern 2
복잡한 구조를 과도하게 설계한다.
---
## Anti Pattern 3
사용자 가치보다 기술 선호를 우선한다.
---
## Anti Pattern 4
자동화 가능한 작업을 반복 수행한다.
---
## Anti Pattern 5
품질보다 일정만 우선한다.
---
## Anti Pattern 6
AI가 생성한 코드를 검토 없이 사용한다.
---
## Anti Pattern 7
기술 부채를 무시한다.
---
# 11. Engineering Rules
## Rule EN-01
모든 개발은 사용자 가치와 연결되어야 한다.
---
## Rule EN-02
Architecture는 구현보다 먼저 정의한다.
---
## Rule EN-03
코드는 작성보다 이해하기 쉬워야 한다.
---
## Rule EN-04
자동화 가능한 작업은 수동으로 반복하지 않는다.
---
## Rule EN-05
모든 변경은 테스트 가능해야 한다.
---
## Rule EN-06
AI 생성 결과물도 동일한 품질 기준을 적용한다.
---
## Rule EN-07
Engineering의 성공은 제품 성공으로 평가한다.
---
# 12. References
Related Documents
- DOC-006 Product Development Framework
- DOC-009 Product Discovery Framework
- DOC-010 Product Design Framework
---
# Document Information
Document ID
DOC-011-PART-I
Title
Engineering Manifesto
Version
1.0.0
Status
Draft
Next
DOC-011-PART-II Engineering Operating Model
---
document_id: DOC-011-PART-II
parent_document:
- DOC-011
title: Engineering Operating Model
book: Foundation
domain: Product Engineering
category: Operating Framework
version: 1.0.0
status: Draft
owner: Chief Technology Officer
created_date: 2026-07-26
related_documents:
- DOC-006
- DOC-009
- DOC-010
- DOC-011-PART-I
tags:
- engineering
- operating-model
- delivery
- lifecycle
- ai-engineering
context_scope:
Global
## summary:
Defines the end-to-end operating model for transforming validated product intent into reliable software through iterative engineering, verification, release, and continuous learning.
# 011 Product Engineering Framework
# Part II - Engineering Operating Model
Version 1.0.0
Status: Draft
---
# 1. Purpose
본 문서는 Product Engineering의 표준 운영 흐름을 정의한다.
RoRo에서 Engineering은 요구사항을 구현하는 활동이 아니라, 검증된 제품 의도를 안정적이고 유지보수 가능한 소프트웨어로 지속적으로 전달하는 운영 시스템이다.
---
# 2. Operating Philosophy
Engineering은 프로젝트가 아니라 흐름(Flow)을 관리한다.
작업량을 늘리는 것보다 가치 전달의 흐름을 최적화하는 것이 중요하다.
작은 단위의 반복적인 전달과 빠른 피드백이 대규모 일괄 개발보다 우선한다.
---
# 3. Engineering Lifecycle
```plain text
Validated Product Intent

↓

Engineering Planning

↓

Architecture

↓

Implementation

↓

Verification

↓

Integration

↓

Release

↓

Observability

↓

Learning

↓

Continuous Improvement
```
모든 단계는 이전 단계의 산출물을 입력으로 사용하며, 결과는 다음 단계의 품질을 높이는 학습으로 연결된다.
---
# 4. Engineering Workflow
## Phase 1. Engineering Planning
- 요구사항 분석
- 기술 리스크 식별
- 작업 분해
- 일정 및 우선순위 결정
---
## Phase 2. Architecture
- 시스템 구조 설계
- 인터페이스 정의
- 데이터 모델 검토
- 기술 선택
---
## Phase 3. Implementation
- 기능 개발
- 코드 리뷰
- 단위 테스트
- 문서화
---
## Phase 4. Verification
- 통합 테스트
- 품질 점검
- 성능 검증
- 보안 검토
---
## Phase 5. Release
- 배포 승인
- 운영 환경 배포
- 배포 검증
- 롤백 준비
---
## Phase 6. Observation
- 모니터링
- 로그 분석
- 사용자 행동 분석
- 장애 감지
---
## Phase 7. Learning
- 회고
- 기술 부채 식별
- 개선 과제 등록
- Knowledge Repository 업데이트
---
# 5. Engineering Quality Gates
| Gate | Exit Condition |
| --- | --- |
| Gate 1 | 요구사항 이해 완료 |
| Gate 2 | Architecture Review 완료 |
| Gate 3 | Code Review 완료 |
| Gate 4 | 테스트 통과 |
| Gate 5 | 보안 검토 완료 |
| Gate 6 | 배포 승인 |
| Gate 7 | 운영 모니터링 확인 |
| Gate 8 | 회고 및 지식 등록 완료 |
Quality Gate는 품질을 보장하기 위한 기준이며, 형식적인 승인 절차가 아니다.
---
# 6. AI-assisted Engineering Flow
AI는 각 단계에서 다음과 같은 역할을 수행할 수 있다.
| Phase | AI Support |
| --- | --- |
| Planning | 작업 분해, 리스크 식별 |
| Architecture | 설계 대안 제안 |
| Implementation | 코드 생성 및 리팩터링 |
| Verification | 테스트 코드 생성, 정적 분석 |
| Release | 배포 체크리스트 생성 |
| Observation | 로그 분석, 이상 탐지 |
| Learning | 회고 요약, 개선안 도출 |
AI는 생산성을 높이는 도구이며, 최종 책임은 Engineering Team이 가진다.
---
# 7. Required Artifacts
모든 Engineering 활동은 다음 산출물을 유지한다.
- Engineering Plan
- Architecture Decision Record (ADR)
- Source Code
- Test Report
- Security Checklist
- Release Note
- Post-release Review
- Engineering Retrospective
---
# 8. Success Metrics
| KPI | Description |
| --- | --- |
| Lead Time for Changes | 변경 리드타임 |
| Deployment Frequency | 배포 빈도 |
| Change Failure Rate | 변경 실패율 |
| Mean Time to Recovery | 평균 복구 시간 |
| Test Coverage | 테스트 커버리지 |
| Code Review Coverage | 코드 리뷰 적용률 |
| Engineering Throughput | 엔지니어링 처리량 |
---
# 9. Operational Checklist
□ 요구사항이 Discovery 및 Design과 연결되는가
□ Architecture Review를 완료했는가
□ Code Review를 수행했는가
□ 테스트를 통과했는가
□ 보안 검토를 완료했는가
□ 운영 모니터링을 설정했는가
□ 회고와 Knowledge 등록을 완료했는가
---
# 10. Engineering Anti Pattern
## Anti Pattern 1
요구사항 검증 없이 구현을 시작한다.
---
## Anti Pattern 2
Architecture 없이 기능을 추가한다.
---
## Anti Pattern 3
Code Review를 생략한다.
---
## Anti Pattern 4
테스트보다 일정 준수를 우선한다.
---
## Anti Pattern 5
배포 후 모니터링하지 않는다.
---
## Anti Pattern 6
장애를 개인의 실수로만 본다.
---
## Anti Pattern 7
회고 없이 다음 개발을 시작한다.
---
# 11. Engineering Operating Rules
## Rule EO-01
Engineering은 검증된 Product Intent를 입력으로 한다.
---
## Rule EO-02
Architecture는 구현 전에 승인되어야 한다.
---
## Rule EO-03
모든 변경은 Code Review를 거친다.
---
## Rule EO-04
배포는 자동화 가능한 범위까지 자동화한다.
---
## Rule EO-05
운영 데이터는 다음 개발의 입력이 된다.
---
## Rule EO-06
회고 결과는 반드시 Knowledge Repository에 등록한다.
---
## Rule EO-07
Engineering의 목표는 코드 작성이 아니라 지속적인 가치 전달이다.
---
# 12. References
Related Documents
- DOC-006 Product Development Framework
- DOC-009 Product Discovery Framework
- DOC-010 Product Design Framework
- DOC-011-PART-I Engineering Manifesto
---
# Document Information
Document ID
DOC-011-PART-II
Title
Engineering Operating Model
Version
1.0.0
Status
Draft
Next
DOC-011-PART-III Architecture Framework
---
document_id: DOC-011-PART-III
parent_document:
- DOC-011
title: Architecture Framework
book: Foundation
domain: Product Engineering
category: Operating Framework
version: 1.0.0
status: Draft
owner: Chief Technology Officer
created_date: 2026-07-26
related_documents:
- DOC-006
- DOC-009
- DOC-010
- DOC-011-PART-I
- DOC-011-PART-II
tags:
- architecture
- software-design
- system-design
- scalability
- adr
context_scope:
Global
## summary:
Defines architectural principles, decision processes, system design standards, and scalability guidelines for building reliable and adaptable product systems.
# 011 Product Engineering Framework
# Part III - Architecture Framework
Version 1.0.0
Status: Draft
---
# 1. Purpose
본 문서는 RoRo Product Architecture를 설계하고 운영하기 위한 원칙과 기준을 정의한다.
Architecture는 단순한 기술 구조가 아니다.
Architecture는 Product Vision과 User Experience를 안정적으로 구현하기 위한 시스템 구조이다.
---
# 2. Architecture Philosophy
좋은 Architecture는 복잡성을 관리한다.
좋은 Architecture는 현재 요구사항만 만족하는 것이 아니라 미래의 변화 가능성을 고려한다.
Architecture의 목표는 기술적 완벽성이 아니라 지속 가능한 제품 발전이다.
---
# 3. Architecture Objectives
Architecture는 다음 목표를 가진다.
- 제품 확장성 확보
- 시스템 안정성 확보
- 개발 생산성 향상
- 기술 부채 최소화
- 변경 비용 감소
- 장애 영향 최소화
- 서비스 품질 향상
---
# 4. Architecture Principles
## Principle 1
Business First Architecture
기술 구조는 Business Goal과 Product Value를 지원해야 한다.
---
## Principle 2
Simple Before Complex
필요 이상의 복잡성을 만들지 않는다.
---
## Principle 3
Loose Coupling
시스템 간 의존성을 최소화한다.
---
## Principle 4
High Cohesion
관련 기능은 함께 관리한다.
---
## Principle 5
Design for Change
변화를 고려한 구조를 만든다.
---
## Principle 6
Failure is Normal
장애 가능성을 기본 전제로 설계한다.
---
## Principle 7
Data is Product Asset
데이터는 핵심 Product Asset으로 관리한다.
---
# 5. Architecture Decision Model
모든 Architecture 결정은 다음 과정을 따른다.
```plain text
Problem Definition

↓

Constraints Analysis

↓

Alternative Solutions

↓

Trade-off Evaluation

↓

Decision

↓

Documentation

↓

Review
```
Architecture 결정은 반드시 기록되어야 한다.
---
# 6. Architecture Layers
RoRo Architecture는 다음 계층 구조를 따른다.
```plain text
Experience Layer

↓

Application Layer

↓

Domain Layer

↓

Data Layer

↓

Infrastructure Layer

↓

Security Layer
```
각 Layer는 명확한 책임을 가진다.
---
# 7. Architecture Components
Architecture 설계 시 다음 요소를 정의한다.
| Component | Description |
| --- | --- |
| Client Architecture | Web/App 구조 |
| Backend Architecture | Service 구조 |
| Data Architecture | 데이터 관리 구조 |
| AI Architecture | AI Service 구조 |
| Integration Architecture | External API 구조 |
| Infrastructure Architecture | Cloud 구조 |
| Security Architecture | 보호 구조 |
---
# 8. Architecture Decision Record (ADR)
중요한 Architecture 결정은 ADR로 관리한다.
ADR Structure:
```plain text
Title

Context

Problem

Decision

Alternatives

Trade-offs

Consequences

Status

Date
```
ADR은 Engineering Knowledge의 핵심 자산이다.
---
# 9. Scalability Principles
시스템은 다음 확장성을 고려한다.
## Horizontal Scalability
트래픽 증가 대응
---
## Functional Scalability
기능 확장 대응
---
## Data Scalability
데이터 증가 대응
---
## Team Scalability
조직 성장 대응
---
# 10. AI Architecture Consideration
AI Product는 기존 Software Architecture와 다른 고려사항이 필요하다.
주요 고려 영역:
- Model Integration
- Prompt Management
- AI Cost Control
- Data Privacy
- Model Evaluation
- Human Feedback Loop
- AI Reliability
AI 기능은 별도의 Architecture Decision을 필요로 한다.
---
# 11. Architecture Validation
Architecture는 구현 전에 검증한다.
검증 항목:
- Performance
- Scalability
- Security
- Maintainability
- Cost
- Reliability
- Operational Complexity
---
# 12. Required Artifacts
모든 Architecture 설계는 다음 산출물을 유지한다.
- System Architecture Diagram
- Data Flow Diagram
- API Specification
- ADR Document
- Security Review
- Performance Consideration
- Cost Analysis
---
# 13. Architecture Metrics
| KPI | Description |
| --- | --- |
| System Availability | 서비스 가용성 |
| Latency | 응답 시간 |
| Scalability Index | 확장성 |
| Technical Debt | 기술 부채 |
| Architecture Review Coverage | 검토 범위 |
| Change Impact | 변경 영향도 |
---
# 14. Architecture Anti Pattern
## Anti Pattern 1
기술 선택부터 시작한다.
---
## Anti Pattern 2
현재 요구사항만 고려한다.
---
## Anti Pattern 3
모든 기능을 하나의 시스템에 집중한다.
---
## Anti Pattern 4
Architecture Decision을 기록하지 않는다.
---
## Anti Pattern 5
확장성을 고려하지 않는다.
---
## Anti Pattern 6
AI 기능을 기존 기능처럼 단순 취급한다.
---
## Anti Pattern 7
운영 비용을 고려하지 않는다.
---
# 15. Architecture Rules
## Rule AR-01
Architecture는 Product Goal에서 시작한다.
---
## Rule AR-02
중요한 기술 결정은 ADR로 기록한다.
---
## Rule AR-03
복잡성은 의도적으로 관리한다.
---
## Rule AR-04
변경 가능성을 고려하여 설계한다.
---
## Rule AR-05
데이터는 핵심 자산으로 관리한다.
---
## Rule AR-06
AI 기능은 별도 평가 기준을 가진다.
---
## Rule AR-07
Architecture 품질은 제품 성공으로 평가한다.
---
# 16. References
Related Documents
- DOC-006 Product Development Framework
- DOC-009 Product Discovery Framework
- DOC-010 Product Design Framework
- DOC-011-PART-I Engineering Manifesto
- DOC-011-PART-II Engineering Operating Model
---
# Document Information
Document ID
DOC-011-PART-III
Title
Architecture Framework
Version
1.0.0
Status
Draft
Next
DOC-011-PART-IV Coding Standards Framework
---
document_id: DOC-011-PART-IV
parent_document:
- DOC-011
title: Coding Standards Framework
book: Foundation
domain: Product Engineering
category: Operating Framework
version: 1.0.0
status: Draft
owner: Chief Technology Officer
created_date: 2026-07-26
related_documents:
- DOC-011-PART-I
- DOC-011-PART-II
- DOC-011-PART-III
tags:
- coding-standard
- code-quality
- software-engineering
- ai-code
context_scope:
Global
## summary:
Defines coding principles, quality standards, naming conventions, review rules, documentation requirements, and AI-generated code policies.
# 011 Product Engineering Framework
# Part IV - Coding Standards Framework
Version 1.0.0
Status: Draft
---
# 1. Purpose
본 문서는 RoRo Software Engineering에서 작성되는 코드의 품질, 일관성, 유지보수성을 확보하기 위한 Coding Standard를 정의한다.
Coding Standard는 코드 작성 규칙이 아니다.
Coding Standard는 팀과 AI Agent가 동일한 품질 기준으로 Software를 만들기 위한 Engineering Language이다.
---
# 2. Coding Philosophy
좋은 코드는 작동하는 코드가 아니다.
좋은 코드는:
- 이해하기 쉽고
- 변경하기 쉽고
- 테스트하기 쉽고
- 안전하게 운영 가능한 코드
이다.
코드의 첫 번째 목적은 컴퓨터 실행이 아니라 사람과 조직의 지속적인 이해이다.
---
# 3. Coding Principles
## Principle 1
Readability First
읽기 쉬운 코드를 우선한다.
---
## Principle 2
Explicit over Implicit
명확한 표현을 선호한다.
---
## Principle 3
Small and Focused
작은 책임을 가진 구조를 만든다.
---
## Principle 4
Avoid Premature Optimization
필요하기 전에 최적화하지 않는다.
---
## Principle 5
Consistency Matters
개인 취향보다 팀 표준을 우선한다.
---
## Principle 6
Code is Product Asset
코드는 장기적인 제품 자산이다.
---
# 4. Repository Structure
Repository는 명확한 구조를 가져야 한다.
Example:
```plain text
project/

├── docs/

├── src/

│   ├── components/

│   ├── features/

│   ├── services/

│   ├── models/

│   └── utils/

├── tests/

├── config/

├── scripts/

└── README.md
```
구조는 프로젝트 목적에 따라 변경할 수 있으나 책임 영역은 명확해야 한다.
---
# 5. Naming Convention
## Variables
명확한 의미를 가진 이름을 사용한다.
좋은 예:
```plain text
userProfile

travelHistory

expenseSummary
```
나쁜 예:
```plain text
data

temp

value
```
---
## Functions
함수 이름은 행동을 표현한다.
좋은 예:
```plain text
generateTravelDiary()

calculateExpense()

validatePermission()
```
---
## Components
Component 이름은 역할을 표현한다.
좋은 예:
```plain text
TripTimelineCard

MemoryGallery

ExpenseSummary
```
---
# 6. Code Organization
하나의 Module은 하나의 책임을 가진다.
권장 원칙:
- Single Responsibility
- Low Coupling
- High Cohesion
- Clear Dependency
---
# 7. Error Handling Standard
Error는 정상적인 상황으로 취급한다.
모든 시스템은 다음을 고려한다.
- Error Detection
- Error Logging
- User Message
- Recovery Strategy
- Monitoring
---
# 8. Documentation Standard
중요한 코드에는 문서가 필요하다.
Documentation 대상:
- Architecture Decision
- Complex Logic
- Business Rule
- API Contract
- Data Model
- Security Rule
단순 코드를 설명하는 주석보다 "왜 존재하는지"를 설명한다.
---
# 9. Testing Requirement
코드는 테스트 가능해야 한다.
최소 기준:
- Unit Test
- Integration Test
- Regression Test
핵심 Business Logic은 높은 테스트 커버리지를 유지한다.
---
# 10. Code Review Standard
모든 주요 변경은 Review를 거친다.
Review 기준:
- Correctness
- Readability
- Maintainability
- Security
- Performance
- Test Coverage
- Architecture Alignment
---
# 11. AI Generated Code Policy
AI가 생성한 코드도 동일한 기준을 적용한다.
AI Code Review Checklist:
□ 목적이 명확한가
□ Architecture와 일치하는가
□ 보안 문제가 없는가
□ 테스트가 존재하는가
□ 불필요한 복잡성이 없는가
□ 사람이 이해 가능한가
---
# 12. Code Quality Metrics
| KPI | Description |
| --- | --- |
| Code Review Coverage | 리뷰 적용률 |
| Test Coverage | 테스트 범위 |
| Defect Density | 결함 밀도 |
| Technical Debt | 기술 부채 |
| Maintainability Index | 유지보수성 |
| Build Success Rate | 빌드 성공률 |
---
# 13. Coding Anti Pattern
## Anti Pattern 1
동작만 하는 코드를 작성한다.
---
## Anti Pattern 2
복잡한 로직을 설명하지 않는다.
---
## Anti Pattern 3
중복 코드를 지속적으로 만든다.
---
## Anti Pattern 4
테스트 없는 핵심 기능을 배포한다.
---
## Anti Pattern 5
AI 생성 코드를 검증 없이 사용한다.
---
## Anti Pattern 6
개인 스타일을 팀 표준보다 우선한다.
---
## Anti Pattern 7
기술 부채를 방치한다.
---
# 14. Coding Rules
## Rule CS-01
코드는 사람이 읽을 수 있어야 한다.
---
## Rule CS-02
명확성이 최적화보다 우선한다.
---
## Rule CS-03
모든 주요 변경은 Review 대상이다.
---
## Rule CS-04
Business Logic은 테스트 가능해야 한다.
---
## Rule CS-05
AI 생성 코드도 동일한 품질 기준을 적용한다.
---
## Rule CS-06
코드는 Product Asset으로 관리한다.
---
## Rule CS-07
코드 품질은 지속적으로 개선한다.
---
# 15. References
Related Documents
- DOC-011-PART-I Engineering Manifesto
- DOC-011-PART-II Engineering Operating Model
- DOC-011-PART-III Architecture Framework
---
# Document Information
Document ID
DOC-011-PART-IV
Title
Coding Standards Framework
Version
1.0.0
Status
Draft
Next
DOC-011-PART-V AI-assisted Engineering Framework
---
document_id: DOC-011-PART-V
parent_document:
- DOC-011
title: AI-assisted Engineering Framework
book: Foundation
domain: Product Engineering
category: Operating Framework
version: 1.0.0
status: Draft
owner: Chief Technology Officer
created_date: 2026-07-26
related_documents:
- DOC-005
- DOC-006
- DOC-009
- DOC-010
- DOC-011-PART-I
- DOC-011-PART-II
- DOC-011-PART-III
- DOC-011-PART-IV
tags:
- ai-engineering
- coding-agent
- automation
- generative-ai
- software-development
context_scope:
Global
## summary:
Defines principles, workflows, governance, and quality standards for integrating AI agents into software engineering activities.
# 011 Product Engineering Framework
# Part V - AI-assisted Engineering Framework
Version 1.0.0
Status: Draft
---
# 1. Purpose
본 문서는 AI 기술을 Engineering Workflow에 통합하기 위한 원칙과 운영 기준을 정의한다.
RoRo에서 AI는 단순한 자동화 도구가 아니다.
AI는 Engineering Team의 사고력과 생산성을 확장하는 협업 시스템이다.
---
# 2. AI Engineering Philosophy
AI는 코드를 빠르게 만드는 도구가 아니다.
AI의 핵심 가치는:
- 문제 이해
- 설계 지원
- 반복 작업 자동화
- 품질 개선
- 지식 확장
이다.
최종 책임은 항상 Human Engineer에게 있다.
---
# 3. AI Engineering Principles
## Principle 1
Human in the Loop
중요한 의사결정에는 사람이 참여한다.
---
## Principle 2
Intent Before Generation
코드 생성 전에 목적과 요구사항을 명확히 한다.
---
## Principle 3
Review Before Trust
AI 결과물은 반드시 검토한다.
---
## Principle 4
Context is Critical
AI 품질은 제공되는 Context 품질에 의해 결정된다.
---
## Principle 5
AI Should Amplify Expertise
AI는 전문가의 판단을 강화한다.
---
# 4. AI Engineering Workflow
```plain text
Problem Definition

↓

Context Preparation

↓

AI Collaboration

↓

Generated Output

↓

Human Review

↓

Testing

↓

Integration

↓

Learning
```
---
# 5. AI Agent Roles
RoRo Engineering에서 AI Agent는 다음 역할을 수행할 수 있다.
| Role | Responsibility |
| --- | --- |
| Coding Agent | 코드 생성 및 수정 |
| Review Agent | 코드 품질 검토 |
| Test Agent | 테스트 생성 |
| Documentation Agent | 문서화 |
| Debug Agent | 문제 분석 |
| Architecture Agent | 설계 검토 |
| Knowledge Agent | 지식 검색 |
---
# 6. AI Input Standard
AI에게 제공해야 하는 Context:
- Product Requirement
- User Story
- Architecture Decision
- Coding Standard
- Existing Code
- Test Requirement
- Security Policy
Context 없는 AI 요청은 품질 저하를 발생시킨다.
---
# 7. AI Code Generation Standard
AI 생성 코드는 다음 검증을 통과해야 한다.
```plain text
Generated Code

↓

Architecture Review

↓

Code Review

↓

Test

↓

Security Check

↓

Merge
```
---
# 8. AI Prompt Engineering Standard
좋은 Engineering Prompt는 다음 구조를 가진다.
```plain text
Context

+

Goal

+

Constraint

+

Expected Output

+

Validation Criteria
```
예:
Bad Prompt:
"로그인 기능 만들어줘"
Good Prompt:
"현재 Authentication Architecture 기준으로 OAuth 기반 로그인 기능을 구현하라. Security Policy와 Test Requirement를 만족하고 API Interface를 정의하라."
---
# 9. AI Security Policy
AI 활용 시 다음을 보호한다.
- Source Code
- Customer Data
- Personal Information
- Security Configuration
- Business Secret
민감 데이터는 승인된 환경에서만 처리한다.
---
# 10. AI Cost Management
AI 사용은 비용 효율성을 고려한다.
관리 항목:
- Model Selection
- Token Usage
- Request Frequency
- Automation Priority
- Human Review Cost
가장 큰 모델보다 가장 적합한 모델을 선택한다.
---
# 11. AI Quality Metrics
| KPI | Description |
| --- | --- |
| AI Adoption Rate | AI 활용률 |
| Generated Code Acceptance Rate | 생성 코드 승인율 |
| AI Defect Rate | AI 생성 결함률 |
| Development Time Reduction | 개발 시간 감소 |
| Review Efficiency | 리뷰 효율 |
| AI Cost Efficiency | 비용 효율 |
---
# 12. AI Anti Pattern
## Anti Pattern 1
AI 결과물을 검토 없이 사용한다.
---
## Anti Pattern 2
Context 없이 AI에게 요청한다.
---
## Anti Pattern 3
AI를 단순 자동 완성 도구로만 사용한다.
---
## Anti Pattern 4
보안 데이터를 무분별하게 입력한다.
---
## Anti Pattern 5
AI가 내린 판단을 무조건 신뢰한다.
---
## Anti Pattern 6
Human Responsibility를 제거한다.
---
## Anti Pattern 7
AI 사용량만 생산성으로 판단한다.
---
# 13. AI Engineering Rules
## Rule AI-01
AI는 Engineering Capability를 확장하는 도구이다.
---
## Rule AI-02
중요한 기술 결정은 Human이 책임진다.
---
## Rule AI-03
AI 생성 결과물은 동일한 Quality Gate를 적용한다.
---
## Rule AI-04
AI 활용에는 충분한 Context를 제공한다.
---
## Rule AI-05
AI 사용 과정과 결과는 기록 가능해야 한다.
---
## Rule AI-06
AI 비용과 품질을 함께 관리한다.
---
## Rule AI-07
AI Engineering Knowledge를 지속적으로 축적한다.
---
# 14. Required Artifacts
AI Engineering 활동은 다음을 기록한다.
- AI Task Description
- Prompt Record
- Generated Output
- Human Review Result
- Validation Result
- Improvement Learning
---
# 15. References
Related Documents
- DOC-005 Knowledge Management Framework
- DOC-006 Product Development Framework
- DOC-011-PART-I Engineering Manifesto
- DOC-011-PART-II Engineering Operating Model
- DOC-011-PART-III Architecture Framework
- DOC-011-PART-IV Coding Standards Framework
---
# Document Information
Document ID
DOC-011-PART-V
Title
AI-assisted Engineering Framework
Version
1.0.0
Status
Draft
Next
DOC-011-PART-VI Testing & Quality Framework
---
document_id: DOC-011-PART-VI
parent_document:
- DOC-011
title: Testing & Quality Framework
book: Foundation
domain: Product Engineering
category: Operating Framework
version: 1.0.0
status: Draft
owner: Chief Technology Officer
created_date: 2026-07-26
related_documents:
- DOC-006
- DOC-009
- DOC-010
- DOC-011-PART-I
- DOC-011-PART-II
- DOC-011-PART-III
- DOC-011-PART-IV
- DOC-011-PART-V
tags:
- testing
- quality-engineering
- automation
- reliability
- validation
context_scope:
Global
## summary:
Defines the quality engineering principles, testing strategy, automation standards, and validation processes required to deliver reliable product experiences.
# 011 Product Engineering Framework
# Part VI - Testing & Quality Framework
Version 1.0.0
Status: Draft
---
# 1. Purpose
본 문서는 RoRo Product Engineering에서 Software Quality를 확보하기 위한 Testing 및 Quality Engineering 기준을 정의한다.
Testing은 개발 완료 후 수행하는 검증 활동이 아니다.
Testing은 Product Intent가 실제 Software Experience로 정확하게 전달되는지를 지속적으로 확인하는 Engineering Process이다.
---
# 2. Quality Philosophy
Quality는 Testing Team만의 책임이 아니다.
Quality는:
- Product
- Design
- Engineering
- QA
- Operations
모든 구성원이 함께 책임지는 결과이다.
---
# 3. Quality Principles
## Principle 1
Quality Starts Early
품질은 개발 이후가 아니라 설계 단계부터 시작한다.
---
## Principle 2
Prevent Before Detect
문제를 찾는 것보다 문제 발생을 예방한다.
---
## Principle 3
Automate Repetition
반복 검증은 자동화한다.
---
## Principle 4
Test User Value
기능뿐 아니라 사용자 경험을 검증한다.
---
## Principle 5
Risk-based Testing
중요도와 위험도에 따라 테스트 우선순위를 결정한다.
---
# 4. Quality Engineering Lifecycle
```plain text
Requirement Analysis

↓

Test Strategy

↓

Test Design

↓

Automation

↓

Execution

↓

Result Analysis

↓

Release Decision

↓

Learning
```
---
# 5. Testing Pyramid
RoRo는 다음 Testing Pyramid를 적용한다.
```plain text
          E2E Test

       Integration Test

    Component Test

 Unit Test
```
낮은 비용의 테스트를 많이 유지하고, 높은 비용의 테스트는 핵심 시나리오 중심으로 운영한다.
---
# 6. Testing Types
## Unit Test
목적:
개별 코드 단위의 정확성 검증
대상:
- Business Logic
- Utility
- Calculation
---
## Integration Test
목적:
Module 간 연결 검증
대상:
- API
- Database
- External Service
---
## End-to-End Test
목적:
실제 사용자 경험 검증
대상:
- Critical User Journey
- Core Feature
---
## Performance Test
목적:
성능과 확장성 검증
검증 항목:
- Response Time
- Throughput
- Resource Usage
---
## Security Test
목적:
보안 위험 검증
검증 항목:
- Authentication
- Authorization
- Data Protection
---
# 7. AI-assisted Testing
AI는 Testing 활동을 지원한다.
지원 영역:
| Area | AI Role |
| --- | --- |
| Test Generation | 테스트 케이스 생성 |
| Bug Analysis | 오류 원인 분석 |
| Regression | 영향 범위 분석 |
| Documentation | 테스트 문서 작성 |
| Coverage Analysis | 테스트 누락 탐지 |
AI 생성 테스트도 동일한 품질 기준을 적용한다.
---
# 8. Test Automation Standard
자동화 우선 대상:
- 반복 테스트
- Regression Test
- Critical Path
- API Test
- Build Verification
자동화하지 않는 영역:
- Exploratory Testing
- 사용자 감성 평가
- 초기 Concept Validation
---
# 9. Release Quality Gate
Release 전 다음 기준을 만족해야 한다.
| Gate | Requirement |
| --- | --- |
| Gate 1 | Unit Test Pass |
| Gate 2 | Integration Test Pass |
| Gate 3 | Critical Scenario Pass |
| Gate 4 | Security Check Pass |
| Gate 5 | Performance Check Pass |
| Gate 6 | Release Approval |
---
# 10. Quality Metrics
| KPI | Description |
| --- | --- |
| Test Coverage | 테스트 범위 |
| Defect Escape Rate | 출시 후 결함률 |
| Automation Rate | 자동화 비율 |
| Regression Stability | 회귀 안정성 |
| Mean Time to Detect | 탐지 시간 |
| Mean Time to Fix | 수정 시간 |
---
# 11. Quality Knowledge Management
모든 테스트 결과는 Knowledge Asset으로 관리한다.
저장 대상:
- Test Case
- Bug Pattern
- Root Cause
- Regression History
- Quality Improvement
실패 경험은 다음 품질 개선의 입력이다.
---
# 12. Testing Anti Pattern
## Anti Pattern 1
테스트를 개발 마지막 단계로 생각한다.
---
## Anti Pattern 2
Manual Test만 의존한다.
---
## Anti Pattern 3
Coverage 숫자만 관리한다.
---
## Anti Pattern 4
Critical User Journey를 테스트하지 않는다.
---
## Anti Pattern 5
Regression Test를 반복 수행한다.
---
## Anti Pattern 6
발견된 Bug의 원인을 기록하지 않는다.
---
## Anti Pattern 7
AI 생성 코드를 테스트 없이 배포한다.
---
# 13. Quality Rules
## Rule QE-01
Quality는 모든 팀의 책임이다.
---
## Rule QE-02
Testing은 Early Stage부터 시작한다.
---
## Rule QE-03
반복 검증은 자동화한다.
---
## Rule QE-04
사용자 경험을 테스트한다.
---
## Rule QE-05
Critical Path는 반드시 보호한다.
---
## Rule QE-06
모든 장애와 Bug는 학습 자산으로 관리한다.
---
## Rule QE-07
Quality 기준은 지속적으로 개선한다.
---
# 14. Required Artifacts
Quality Engineering은 다음 산출물을 유지한다.
- Test Strategy
- Test Plan
- Test Case
- Automation Report
- Defect Report
- Release Quality Report
- Quality Retrospective
---
# 15. References
Related Documents
- DOC-006 Product Development Framework
- DOC-009 Product Discovery Framework
- DOC-010 Product Design Framework
- DOC-011-PART-I Engineering Manifesto
- DOC-011-PART-II Engineering Operating Model
- DOC-011-PART-III Architecture Framework
- DOC-011-PART-IV Coding Standards Framework
- DOC-011-PART-V AI-assisted Engineering Framework
---
# Document Information
Document ID
DOC-011-PART-VI
Title
Testing & Quality Framework
Version
1.0.0
Status
Draft
Next
DOC-011-PART-VII DevSecOps Framework
---
document_id: DOC-011-PART-VII
parent_document:
- DOC-011
title: DevSecOps Framework
book: Foundation
domain: Product Engineering
category: Operating Framework
version: 1.0.0
status: Draft
owner: Chief Technology Officer
created_date: 2026-07-26
related_documents:
- DOC-011-PART-I
- DOC-011-PART-II
- DOC-011-PART-III
- DOC-011-PART-IV
- DOC-011-PART-V
- DOC-011-PART-VI
tags:
- devsecops
- ci-cd
- security
- operations
- reliability
context_scope:
Global
## summary:
Defines the continuous delivery, infrastructure, security, monitoring, and operational reliability standards required for secure and scalable product operation.
# 011 Product Engineering Framework
# Part VII - DevSecOps Framework
Version 1.0.0
Status: Draft
---
# 1. Purpose
본 문서는 RoRo Product Engineering에서 Software를 안정적이고 안전하게 운영하기 위한 DevSecOps Framework를 정의한다.
DevSecOps는 Development, Security, Operations를 통합하여 빠르고 안정적인 Product Delivery를 가능하게 하는 운영 방식이다.
---
# 2. DevSecOps Philosophy
Security와 Operations는 개발 이후 추가되는 단계가 아니다.
Security는 설계부터 포함되어야 하며,
Operations는 개발 결과가 아니라 Product Experience의 일부이다.
---
# 3. DevSecOps Objectives
DevSecOps는 다음 목표를 가진다.
- 빠른 배포
- 안정적인 운영
- 자동화된 품질 검증
- 보안 내재화
- 장애 대응력 향상
- 운영 비용 최적화
---
# 4. DevSecOps Principles
## Principle 1
Security by Design
보안은 기본 설계 요소이다.
---
## Principle 2
Automation First
반복 가능한 운영 작업은 자동화한다.
---
## Principle 3
Continuous Delivery
작은 변경을 안전하게 지속적으로 전달한다.
---
## Principle 4
Observability First
시스템 상태를 항상 이해할 수 있어야 한다.
---
## Principle 5
Failure Ready
장애를 고려하고 대응 가능하게 설계한다.
---
# 5. DevSecOps Lifecycle
```plain text
Code Commit

↓

Build

↓

Test

↓

Security Scan

↓

Deploy

↓

Monitor

↓

Feedback

↓

Improve
```
모든 단계는 자동화 가능 영역을 지속적으로 확대한다.
---
# 6. CI/CD Framework
Continuous Integration:
목표:
- 코드 변경 통합
- 자동 빌드
- 자동 테스트
- 품질 검증
---
Continuous Delivery:
목표:
- 안전한 배포 준비
- 환경 일관성 유지
- 빠른 Release
---
Continuous Deployment:
조건:
- 충분한 자동화
- 안정적인 테스트
- 명확한 Rollback 전략
---
# 7. Infrastructure as Code (IaC)
Infrastructure는 코드로 관리한다.
관리 대상:
- Cloud Resource
- Network
- Database
- Environment Configuration
- Deployment Setting
장점:
- 재현성 확보
- 변경 추적 가능
- 오류 감소
- 자동화 가능
---
# 8. Security Framework
Security는 다음 영역을 포함한다.
## Identity Security
- Authentication
- Authorization
- Access Control
---
## Data Security
- Encryption
- Privacy Protection
- Data Lifecycle Management
---
## Application Security
- Vulnerability Management
- Dependency Check
- Secure Coding
---
## Infrastructure Security
- Network Protection
- Cloud Security
- Configuration Management
---
# 9. Security Development Lifecycle
```plain text
Design

↓

Threat Modeling

↓

Implementation

↓

Security Testing

↓

Release

↓

Monitoring
```
Security는 모든 Lifecycle 단계에 포함된다.
---
# 10. Observability Framework
Monitoring은 단순 장애 확인이 아니다.
Observability는 시스템 내부 상태를 이해하는 능력이다.
핵심 요소:
## Metrics
시스템 상태 측정
---
## Logs
문제 원인 분석
---
## Traces
요청 흐름 추적
---
# 11. Incident Management
장애 발생 시 다음 절차를 따른다.
```plain text
Detection

↓

Response

↓

Mitigation

↓

Recovery

↓

Root Cause Analysis

↓

Prevention
```
목표는 책임 추적이 아니라 시스템 개선이다.
---
# 12. Reliability Engineering
Reliability는 다음 기준으로 관리한다.
- Availability
- Latency
- Error Rate
- Recovery Time
- Capacity
---
# 13. SLO / SLA Framework
서비스 목표를 명확히 정의한다.
Example:
| Metric | Target |
| --- | --- |
| Availability | 99.9% |
| Response Time | Defined by Product Requirement |
| Recovery Time | Defined by Criticality |
---
# 14. DevSecOps Metrics
| KPI | Description |
| --- | --- |
| Deployment Frequency | 배포 빈도 |
| Lead Time | 변경 전달 시간 |
| Change Failure Rate | 변경 실패율 |
| Recovery Time | 장애 복구 시간 |
| Security Issue Resolution | 보안 문제 해결 시간 |
| Automation Coverage | 자동화 범위 |
---
# 15. DevSecOps Anti Pattern
## Anti Pattern 1
보안을 출시 직전에 검토한다.
---
## Anti Pattern 2
수동 배포에 의존한다.
---
## Anti Pattern 3
운영 환경을 문서화하지 않는다.
---
## Anti Pattern 4
모니터링 없이 서비스를 운영한다.
---
## Anti Pattern 5
장애 원인을 개인 책임으로 처리한다.
---
## Anti Pattern 6
Rollback 전략 없이 배포한다.
---
## Anti Pattern 7
Infrastructure 변경을 추적하지 않는다.
---
# 16. DevSecOps Rules
## Rule DS-01
Security는 Design 단계부터 포함한다.
---
## Rule DS-02
배포 가능한 모든 과정은 자동화를 우선한다.
---
## Rule DS-03
운영 상태는 항상 관측 가능해야 한다.
---
## Rule DS-04
장애 대응 프로세스를 사전에 정의한다.
---
## Rule DS-05
Infrastructure 변경은 코드로 관리한다.
---
## Rule DS-06
서비스 안정성은 지속적으로 측정한다.
---
## Rule DS-07
운영 데이터는 제품 개선에 활용한다.
---
# 17. Required Artifacts
DevSecOps 활동은 다음 산출물을 유지한다.
- CI/CD Pipeline Definition
- Infrastructure Code
- Security Checklist
- Threat Model
- Monitoring Dashboard
- Incident Report
- Post Incident Review
---
# 18. References
Related Documents
- DOC-011-PART-I Engineering Manifesto
- DOC-011-PART-II Engineering Operating Model
- DOC-011-PART-III Architecture Framework
- DOC-011-PART-IV Coding Standards Framework
- DOC-011-PART-V AI-assisted Engineering Framework
- DOC-011-PART-VI Testing & Quality Framework
---
# Document Information
Document ID
DOC-011-PART-VII
Title
DevSecOps Framework
Version
1.0.0
Status
Draft
Next
DOC-011-PART-VIII Engineering Knowledge Framework
---
document_id: DOC-011-PART-VIII
parent_document:
- DOC-011
title: Engineering Knowledge Framework
book: Foundation
domain: Product Engineering
category: Operating Framework
version: 1.0.0
status: Draft
owner: Chief Technology Officer
created_date: 2026-07-26
related_documents:
- DOC-005
- DOC-006
- DOC-011-PART-I
- DOC-011-PART-II
- DOC-011-PART-III
- DOC-011-PART-IV
- DOC-011-PART-V
- DOC-011-PART-VI
- DOC-011-PART-VII
tags:
- engineering-knowledge
- documentation
- adr
- learning
- ai-memory
context_scope:
Global
## summary:
Defines how engineering knowledge, decisions, experience, and technical learning are captured, shared, maintained, and leveraged by humans and AI systems.
# 011 Product Engineering Framework
# Part VIII - Engineering Knowledge Framework
Version 1.0.0
Status: Draft
---
# 1. Purpose
본 문서는 Engineering 조직에서 생성되는 기술 지식과 경험을 체계적으로 관리하기 위한 Knowledge Framework를 정의한다.
Engineering Knowledge는 단순 문서가 아니다.
Engineering Knowledge는 조직의 기술적 판단, 경험, 해결 방법, 실패 경험을 축적한 Product Asset이다.
---
# 2. Knowledge Philosophy
코드는 실행되는 지식이다.
문서는 설명되는 지식이다.
Architecture Decision은 판단의 지식이다.
Engineering 조직은 이 모든 것을 지속적으로 축적해야 한다.
---
# 3. Engineering Knowledge Objectives
Engineering Knowledge Framework는 다음 목표를 가진다.
- 반복 문제 감소
- 의사결정 속도 향상
- 신규 구성원 Onboarding 개선
- 기술 자산 축적
- AI Context 품질 향상
- Engineering Capability 확장
---
# 4. Knowledge Categories
RoRo Engineering Knowledge는 다음 영역으로 관리한다.
| Category | Description |
| --- | --- |
| Architecture Knowledge | 시스템 구조와 결정 |
| Code Knowledge | 구현 방식과 패턴 |
| Product Knowledge | 기능 의도와 Business Logic |
| Operational Knowledge | 운영 경험 |
| Security Knowledge | 보안 기준 |
| Testing Knowledge | 품질 경험 |
| AI Knowledge | AI 활용 경험 |
---
# 5. Knowledge Lifecycle
```plain text
Create

↓

Capture

↓

Review

↓

Store

↓

Share

↓

Use

↓

Improve
```
Knowledge는 작성으로 끝나지 않는다.
사용되고 개선되어야 한다.
---
# 6. Required Knowledge Artifacts
Engineering 조직은 다음 산출물을 유지한다.
## Architecture Decision Record (ADR)
기술 선택 이유와 Trade-off 기록
---
## Engineering Decision Log
중요한 개발 판단 기록
---
## API Documentation
Interface 계약 관리
---
## Code Pattern Library
재사용 가능한 구현 방식 관리
---
## Incident Report
장애 원인과 개선 사항 기록
---
## Technical Debt Register
기술 부채 관리
---
# 7. ADR Framework
ADR은 다음 구조를 가진다.
```plain text
Decision Title

Context

Problem

Options

Decision

Trade-off

Impact

Status
```
ADR은 단순 기록이 아니라 미래 Engineering 판단의 기준이다.
---
# 8. Technical Debt Management
기술 부채는 제거 대상이 아니라 관리 대상이다.
관리 항목:
- 발생 원인
- 영향 범위
- 우선순위
- 해결 계획
- 비용 대비 효과
---
# 9. AI Knowledge Integration
AI Engineering 시대에는 Knowledge가 AI Context가 된다.
AI 활용을 위해 다음 정보를 구조화한다.
- Architecture Rule
- Coding Standard
- Product Rule
- API Pattern
- Security Policy
- Past Decision
좋은 Knowledge는 좋은 AI 결과를 만든다.
---
# 10. Engineering Documentation Standard
좋은 문서는 다음 특징을 가진다.
## Clear
명확하다.
## Current
최신 상태를 유지한다.
## Searchable
검색 가능하다.
## Connected
관련 문서와 연결된다.
## Actionable
실행 가능하다.
---
# 11. Knowledge Ownership
Knowledge는 작성자가 아니라 조직이 소유한다.
| Knowledge | Owner |
| --- | --- |
| Architecture | Architect / Tech Lead |
| Code Standard | Engineering Team |
| Product Logic | Product Team |
| Security | Security Owner |
| Operations | SRE / Platform Team |
---
# 12. Knowledge Metrics
| KPI | Description |
| --- | --- |
| Documentation Coverage | 문서화 범위 |
| ADR Adoption | ADR 활용률 |
| Knowledge Usage | 활용 빈도 |
| Search Success Rate | 검색 성공률 |
| Onboarding Time | 신규 적응 시간 |
| Repeated Issue Reduction | 반복 문제 감소 |
---
# 13. Engineering Learning Loop
Engineering은 다음 Cycle을 반복한다.
```plain text
Build

↓

Operate

↓

Observe

↓

Learn

↓

Improve

↓

Build Better
```
실패 경험은 제거해야 하는 기록이 아니라 개선을 위한 자산이다.
---
# 14. Knowledge Anti Pattern
## Anti Pattern 1
개인의 경험에 의존한다.
---
## Anti Pattern 2
중요한 결정을 기록하지 않는다.
---
## Anti Pattern 3
오래된 문서를 방치한다.
---
## Anti Pattern 4
코드만 남기고 이유를 남기지 않는다.
---
## Anti Pattern 5
실패 경험을 삭제한다.
---
## Anti Pattern 6
AI에게 Context를 제공하지 않는다.
---
## Anti Pattern 7
Knowledge Ownership이 없다.
---
# 15. Engineering Knowledge Rules
## Rule EK-01
중요한 판단은 기록한다.
---
## Rule EK-02
Knowledge는 조직 자산이다.
---
## Rule EK-03
문서는 검색 가능해야 한다.
---
## Rule EK-04
실패 경험은 학습 자산으로 관리한다.
---
## Rule EK-05
AI 활용을 위해 Context를 구조화한다.
---
## Rule EK-06
Knowledge는 지속적으로 개선한다.
---
## Rule EK-07
코드와 문서는 함께 진화한다.
---
# 16. Required Artifacts
Engineering Knowledge Repository:
- Architecture Repository
- ADR Repository
- API Documentation
- Coding Pattern Library
- Incident Knowledge Base
- Technical Debt Board
- AI Context Library
---
# 17. References
Related Documents
- DOC-005 Knowledge Management Framework
- DOC-006 Product Development Framework
- DOC-011-PART-I Engineering Manifesto
- DOC-011-PART-II Engineering Operating Model
- DOC-011-PART-III Architecture Framework
- DOC-011-PART-IV Coding Standards Framework
- DOC-011-PART-V AI-assisted Engineering Framework
- DOC-011-PART-VI Testing & Quality Framework
- DOC-011-PART-VII DevSecOps Framework
---
# Document Information
Document ID
DOC-011-PART-VIII
Title
Engineering Knowledge Framework
Version
1.0.0
Status
Draft
Next
DOC-011-PART-IX Engineering Governance Framework
---
document_id: DOC-011-PART-IX
parent_document:
- DOC-011
title: Engineering Governance Framework
book: Foundation
domain: Product Engineering
category: Operating Framework
version: 1.0.0
status: Draft
owner: Chief Technology Officer
created_date: 2026-07-26
related_documents:
- DOC-005
- DOC-006
- DOC-009
- DOC-010
- DOC-011-PART-I
- DOC-011-PART-II
- DOC-011-PART-III
- DOC-011-PART-IV
- DOC-011-PART-V
- DOC-011-PART-VI
- DOC-011-PART-VII
- DOC-011-PART-VIII
tags:
- engineering-governance
- architecture-review
- quality
- ai-governance
- decision-making
context_scope:
Global
## summary:
Defines engineering governance principles, decision authority, review mechanisms, quality controls, and continuous improvement systems.
# 011 Product Engineering Framework
# Part IX - Engineering Governance Framework
Version 1.0.0
Status: Draft
---
# 1. Purpose
본 문서는 RoRo Engineering 조직의 의사결정 체계와 품질 관리 기준을 정의한다.
Engineering Governance는 개발 속도를 제한하는 통제가 아니다.
Engineering Governance는 제품 목표와 기술 방향을 일치시키고 지속 가능한 Engineering 시스템을 만드는 운영 체계이다.
---
# 2. Governance Philosophy
좋은 Governance는 승인 단계를 늘리지 않는다.
좋은 Governance는:
- 명확한 책임
- 빠른 의사결정
- 반복 가능한 기준
- 투명한 기록
을 제공한다.
---
# 3. Governance Objectives
Engineering Governance는 다음 목표를 가진다.
- 기술 방향 정렬
- Architecture 품질 확보
- Security 기준 유지
- Engineering Quality 확보
- AI 활용 책임성 확보
- 지속적인 개선 문화 구축
---
# 4. Governance Principles
## Principle 1
Clear Ownership
모든 중요한 결정에는 책임자가 존재한다.
---
## Principle 2
Decision Transparency
중요한 판단은 기록되고 공유된다.
---
## Principle 3
Standards Before Scale
확장 전에 기준을 만든다.
---
## Principle 4
Automation Over Approval
가능한 검증은 자동화한다.
---
## Principle 5
Learning Over Blame
문제 발생 시 책임보다 개선을 우선한다.
---
# 5. Engineering Governance Model
RoRo Governance 구조:
```plain text
Product Strategy

↓

Engineering Leadership

↓

Architecture Review

↓

Engineering Teams

↓

Quality & Security Validation

↓

Release

↓

Learning
```
---
# 6. Decision Authority Model
| Decision Area | Owner |
| --- | --- |
| Product Requirement | Product Owner |
| UX Decision | Design Owner |
| Architecture Decision | Engineering Architect |
| Security Decision | Security Owner |
| Quality Decision | Quality Owner |
| Release Decision | Engineering Leadership |
---
# 7. Architecture Review Board
Architecture Review가 필요한 경우:
- 신규 System 추가
- 주요 Technology 변경
- Data Architecture 변경
- Security 영향 변경
- Scale 영향 변경
Review 항목:
- Problem
- Alternative
- Trade-off
- Risk
- Cost
- Long-term Impact
---
# 8. Engineering Review Framework
주요 Review:
## Code Review
목적:
코드 품질 확보
---
## Architecture Review
목적:
시스템 방향 검증
---
## Security Review
목적:
보안 위험 관리
---
## Quality Review
목적:
사용자 경험 품질 확보
---
# 9. AI Governance
AI 활용에는 별도 Governance를 적용한다.
관리 영역:
- AI Tool Usage
- Data Protection
- Prompt Management
- Generated Code Review
- Model Selection
- Cost Management
---
# 10. Engineering Metrics Governance
측정 대상:
| Category | Metrics |
| --- | --- |
| Delivery | Lead Time, Deployment Frequency |
| Reliability | Availability, Recovery Time |
| Quality | Defect Rate, Test Coverage |
| Architecture | Technical Debt |
| AI | Adoption, Efficiency |
| Knowledge | Documentation Coverage |
---
# 11. Technical Debt Governance
Technical Debt는 지속적으로 관리한다.
관리 Cycle:
```plain text
Identify

↓

Prioritize

↓

Plan

↓

Resolve

↓

Measure
```
---
# 12. Continuous Improvement Framework
Engineering 개선 Cycle:
```plain text
Measure

↓

Analyze

↓

Improve

↓

Standardize

↓

Repeat
```
개선 결과는 Engineering Knowledge Repository에 반영한다.
---
# 13. Governance Anti Pattern
## Anti Pattern 1
모든 것을 승인 절차로 만든다.
---
## Anti Pattern 2
책임자가 없는 결정을 한다.
---
## Anti Pattern 3
기술 선택 이유를 기록하지 않는다.
---
## Anti Pattern 4
Metrics 없이 개선한다.
---
## Anti Pattern 5
AI 사용 기준이 없다.
---
## Anti Pattern 6
문제를 개인 책임으로 처리한다.
---
## Anti Pattern 7
Governance가 Innovation을 방해한다.
---
# 14. Engineering Governance Rules
## Rule EG-01
중요한 결정에는 명확한 Owner가 존재한다.
---
## Rule EG-02
Architecture Decision은 기록한다.
---
## Rule EG-03
검증 가능한 기준은 자동화한다.
---
## Rule EG-04
Security와 Quality는 기본 요구사항이다.
---
## Rule EG-05
AI 사용은 책임 가능한 방식으로 관리한다.
---
## Rule EG-06
Technical Debt는 지속적으로 관리한다.
---
## Rule EG-07
Governance의 목적은 Alignment와 Improvement이다.
---
# 15. Engineering Governance Artifacts
필수 관리 문서:
- Architecture Decision Record
- Review Record
- Security Assessment
- Quality Report
- AI Usage Record
- Technical Debt Register
- Improvement Report
---
# 16. DOC-011 Product Engineering Framework Summary
DOC-011은 다음 Engineering System을 정의한다.
```plain text
Engineering Manifesto

↓

Operating Model

↓

Architecture

↓

Coding Standards

↓

AI-assisted Engineering

↓

Testing & Quality

↓

DevSecOps

↓

Engineering Knowledge

↓

Governance
```
---
# 17. Final Engineering Principle
RoRo Engineering의 최종 원칙:
> Build software that creates user value, evolves with change, learns continuously, and improves through intelligence.
---
# Document Information
Document ID
DOC-011-PART-IX
Title
Engineering Governance Framework
Version
1.0.0
Status
Draft
---
# DOC-011 Product Engineering Framework
Status
Completed
Framework Components:
✅ Engineering Manifesto
✅ Engineering Operating Model
✅ Architecture Framework
✅ Coding Standards Framework
✅ AI-assisted Engineering Framework
✅ Testing & Quality Framework
✅ DevSecOps Framework
✅ Engineering Knowledge Framework
✅ Engineering Governance Framework
---
Next
DOC-012 Product Delivery Framework
