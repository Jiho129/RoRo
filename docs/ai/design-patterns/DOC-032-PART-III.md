<!-- Source: Notion page [032 AI Design Patterns Catalog](https://app.notion.com/p/3aadff1c1f74802d8884dfbfd0eee158?pvs=204). Last edited 2026-08-07T01:53:23.126Z. Extracted as an archival segment from one combined page. -->

---
document_id: DOC-032-PART-III
parent_document:
- DOC-032
title: AI Design Pattern Catalog - Interaction Patterns
book: Product Bible
domain: Artificial Intelligence
category: Interaction Patterns
version: 1.0.0
status: Draft
owner: Chief AI Product Officer
created_date: 2026-07-27
related_documents:
- DOC-032-PART-I
- DOC-032-PART-II
tags:
- interaction
- conversation
- ux
- ai
## summary:
Defines reusable interaction patterns between users and AI systems,
including conversational UX, guided workflows, copilots, and escalation strategies.
# DOC-032
# AI Design Pattern Catalog
## Part III
# Interaction Patterns
Version 1.0.0
Status : Draft
---
archive_source: Notion
source_page_id: 3aadff1c-1f74-802d-8884-dfbfd0eee158
source_page_url: https://app.notion.com/p/3aadff1c1f74802d8884dfbfd0eee158?pvs=204

# 3.0 Overview
Interaction Pattern은
사용자와 AI가 어떻게 협업하고 정보를 주고받는지를 정의하는 설계 패턴이다.
Interaction Pattern은 단순한 UI 패턴이 아니다.
다음을 함께 정의한다.
- 사용자 경험(UX)
- 대화 흐름
- AI의 응답 방식
- 사용자 제어권
- 오류 복구
- 인간 개입 방식
Interaction Pattern은 AI Product의 사용성을 결정하는 핵심 요소이다.
---
# Interaction Pattern Catalog
| Pattern ID | Pattern Name | Status |
| --- | --- | --- |
| AI-PATTERN-001 | Chat Interaction Pattern | Approved |
| AI-PATTERN-002 | Copilot Pattern | Draft |
| AI-PATTERN-003 | Wizard Pattern | Draft |
| AI-PATTERN-004 | Guided Workflow Pattern | Draft |
| AI-PATTERN-005 | Conversational Form Pattern | Draft |
| AI-PATTERN-006 | Progressive Disclosure Pattern | Draft |
| AI-PATTERN-007 | Multi-turn Conversation Pattern | Draft |
| AI-PATTERN-008 | Human Escalation Pattern | Draft |
---
# 3.1 AI-PATTERN-001
# Chat Interaction Pattern
---
## Pattern ID
AI-PATTERN-001
---
## Category
Interaction Pattern
---
## Status
Approved
---
## Purpose
사용자가 자연어를 통해 AI와 자유롭게 상호작용할 수 있도록 하는 가장 기본적인 Interaction Pattern을 정의한다.
이 Pattern은 AI Product의 기본 인터페이스이며, 대부분의 AI 서비스의 출발점이 된다.
---
## Problem
전통적인 UI는 사용자가 기능을 찾아야 한다.
예를 들어,
- 메뉴 탐색
- 버튼 클릭
- 입력 폼 작성
등이 필요하다.
AI Product에서는 이러한 방식이 오히려 사용성을 떨어뜨릴 수 있다.
사용자는 자신의 의도를 자연어로 표현하고 싶어한다.
---
## Solution
AI는 자연어를 입력으로 받아 의도를 해석하고, 적절한 응답을 생성한다.
```plain text
User

↓

Natural Language Input

↓

Intent Understanding

↓

Reasoning

↓

Response Generation

↓

User
```
---
## Architecture
```plain text
+------------------+
|      User        |
+------------------+
          |
          v
+------------------+
| Conversation UI  |
+------------------+
          |
          v
+------------------+
| Intent Analyzer  |
+------------------+
          |
          v
+------------------+
| LLM / Agent      |
+------------------+
          |
          v
+------------------+
| Response Builder |
+------------------+
          |
          v
+------------------+
| Conversation UI  |
+------------------+
```
---
## Responsibilities
### User
- 질문 입력
- 추가 정보 제공
- 결과 확인
### Conversation Layer
- 입력 수집
- Context 유지
- 대화 기록 관리
### AI
- 의도 분석
- 추론
- 응답 생성
- 필요한 경우 질문 반환
---
## Interaction Flow
```plain text
User Question

↓

Intent Analysis

↓

Need More Information?

↓

Yes → Ask Clarifying Question

↓

No

↓

Generate Answer

↓

Return Response
```
---
## Design Principles
### Natural Language First
모든 기능은 자연어를 우선으로 제공한다.
---
### Progressive Clarification
정보가 부족하면 추측하지 않는다.
필요한 정보를 사용자에게 질문한다.
---
### Context Awareness
이전 대화를 활용하여 응답한다.
---
### Transparency
AI의 한계와 불확실성을 숨기지 않는다.
---
## When to Use
다음과 같은 상황에서 적합하다.
- 일반 질의응답
- 여행 계획
- 문서 작성
- 아이디어 브레인스토밍
- 일정 생성
- AI 비서
---
## When NOT to Use
다음과 같은 경우에는 다른 Pattern을 고려한다.
- 반드시 정해진 절차를 따라야 하는 업무
- 법적 동의가 필요한 프로세스
- 복잡한 다단계 입력
- 안전이 중요한 작업
이 경우에는 Wizard Pattern 또는 Guided Workflow Pattern이 적합하다.
---
## Advantages
- 학습 비용이 낮다.
- 자연스럽다.
- 확장성이 높다.
- 새로운 기능 추가가 쉽다.
- 다양한 도메인에 적용 가능하다.
---
## Disadvantages
- 사용자 의도가 모호할 수 있다.
- 잘못된 추론 가능성
- 긴 대화에서 Context 관리가 어려움
- Prompt Injection 위험
---
## Trade-offs
| 장점 | 단점 |
| --- | --- |
| 높은 자유도 | 낮은 예측 가능성 |
| 자연스러운 UX | 입력 품질 의존 |
| 빠른 기능 확장 | Guardrail 필요 |
---
## Failure Handling
AI가 의도를 이해하지 못하면 다음 순서를 따른다.
```plain text
Confidence Check

↓

Clarifying Question

↓

Retry

↓

Human Escalation
```
---
## Observability
기록해야 할 항목
- User Input
- Intent
- Context Version
- Prompt Version
- Response Time
- Token Usage
- Confidence
- User Feedback
---
## Success Metrics
- Intent Recognition Accuracy
- Response Acceptance Rate
- Clarification Rate
- User Satisfaction
- Conversation Completion Rate
- Average Response Time
---
## Anti-patterns
### Menu Chat
채팅처럼 보이지만 실제로는 버튼만 제공
---
### Guessing AI
정보가 부족해도 추측하여 답변
---
### Infinite Conversation
종료 조건 없이 계속 질문
---
### Context Reset
이전 대화를 무시하는 응답
---
## RoRo Example
사용자
> "이번 오사카 여행을 하루씩 여행일기로 만들어줘."
AI
↓
일정을 분석
↓
사진 선택
↓
스토리 생성
↓
사용자 확인
↓
Memory Book 생성
---
## Related Patterns
- AI-PATTERN-002 Copilot Pattern
- AI-PATTERN-003 Wizard Pattern
- AI-PATTERN-007 Multi-turn Conversation Pattern
- Layered Context Pattern
- Reviewer Pattern
---
## Implementation Checklist
- 자연어 입력 지원
- Context 유지
- Clarification 로직 구현
- 대화 이력 저장
- Observability 구축
- Feedback 수집
- Prompt Injection 방어
- 종료 조건 정의
---
# End of Section 3.1
Next Section
AI-PATTERN-002
Copilot Pattern
# DOC-032 — AI Design Pattern Catalog
## Part III — Interaction Patterns
# AI-PATTERN-001 — Chat Interaction Pattern
## 001-01 Executive Summary
### 1. Document Purpose
본 문서는 **Chat Interaction Pattern**을 AI 제품에 적용하기 위한 설계 원칙과 핵심 규격을 정의한다.
Chat Interaction Pattern은 사용자가 자연어를 통해 AI에게 질문하거나 요청하고, AI가 대화의 맥락을 이해하여 응답하는 가장 기본적인 AI Interaction Pattern이다.
본 문서는 특정 UI 프레임워크나 특정 LLM 제품의 구현 방법을 규정하지 않는다. 대신 다양한 AI 제품과 기술 스택에서 재사용할 수 있도록 **사용자 의도 → Context → AI 처리 → 응답 → 후속 상호작용**의 구조적 원칙을 정의한다.
---
### 2. Executive Summary
Chat Interaction Pattern의 핵심은 단순한 "채팅창"을 만드는 것이 아니다.
핵심은 사용자가 원하는 목표를 자연어로 표현할 수 있도록 하고, AI가 그 의도를 해석한 뒤 필요한 Context를 확보하여 적절한 결과를 제공하며, 사용자가 결과를 검토하고 다음 행동을 결정할 수 있도록 하는 것이다.
표준적인 흐름은 다음과 같다.
```plain text
User Intent
    ↓
Message Input
    ↓
Intent & Context Understanding
    ↓
Need Clarification?
    ├── Yes → Clarifying Question → User
    └── No
          ↓
      Task Execution
          ↓
      Response Validation
          ↓
      Response Generation
          ↓
        User
          ↓
   Follow-up / Correction / Completion
```
따라서 Chat Interaction Pattern은 다음 네 가지 요소를 동시에 만족해야 한다.
1. **Natural Interaction** — 사용자가 자연어로 목표를 표현할 수 있어야 한다.
2. **Context Continuity** — 이전 대화와 현재 작업에 필요한 Context를 적절히 유지해야 한다.
3. **Controlled Uncertainty** — AI가 모르는 내용을 임의로 추정하지 않고 필요한 경우 질문해야 한다.
4. **User Agency** — 최종 결과에 대한 사용자 확인, 수정, 취소가 가능해야 한다.
---
### 3. Pattern Definition
**Chat Interaction Pattern**은 다음과 같이 정의한다.
> 사용자의 자연어 입력을 AI가 해석하고, 대화 Context 및 제품 상태를 활용하여 적절한 응답 또는 행동을 생성하며, 필요할 경우 추가 질의를 통해 목표를 구체화하는 상호작용 설계 패턴.
이 정의에서 중요한 것은 **Chat = Text Interface**가 아니라는 점이다.
Chat UI는 표현 방식일 뿐이며, Pattern의 핵심은 다음과 같은 **상호작용 제어 구조**에 있다.
```plain text
Expression
    ↓
Understanding
    ↓
Context Resolution
    ↓
Decision
    ↓
Generation / Action
    ↓
Validation
    ↓
Feedback
```
---
### 4. Problem Addressed
전통적인 소프트웨어에서는 사용자가 기능을 알고 있어야 한다.
```plain text
User
 ↓
Menu
 ↓
Feature
 ↓
Form
 ↓
Submit
```
Chat Interaction Pattern에서는 사용자의 목표를 중심으로 상호작용을 설계한다.
```plain text
User Goal
 ↓
Natural Language
 ↓
AI Interpretation
 ↓
Appropriate Capability
 ↓
Result
```
이를 통해 사용자는 제품의 내부 기능 구조를 모두 알지 않아도 원하는 결과를 요청할 수 있다.
그러나 자연어 기반 상호작용은 다음과 같은 새로운 문제를 만든다.
- 의도가 불명확할 수 있음
- 하나의 요청에 여러 작업이 포함될 수 있음
- 필요한 정보가 누락될 수 있음
- 이전 대화의 의미가 현재 요청에 영향을 줄 수 있음
- AI의 해석이 사용자 의도와 다를 수 있음
- 생성 결과가 사실과 다를 수 있음
- AI가 수행한 행동을 사용자가 인지하지 못할 수 있음
따라서 Chat Interaction Pattern은 **자유로운 입력**과 **통제 가능한 시스템 동작** 사이의 균형을 설계해야 한다.
---
### 5. Applicability
다음 상황에 적합하다.
- 일반적인 AI Assistant
- 질의응답
- 아이디어 생성
- 문서 작성 및 편집
- 여행 계획
- 여행 기록 및 Memory 생성
- 데이터 탐색
- 개인화 추천
- 자연어 기반 검색
- 복수 기능을 하나의 진입점에서 제공하는 AI 제품
특히 사용자가 사전에 제품의 기능 구조를 정확히 알 필요가 없는 경우 효과적이다.
---
### 6. Non-Goals
본 Pattern은 다음을 직접 규정하지 않는다.
- 특정 LLM 선택
- 특정 Prompt Engineering 기법
- 특정 Vector Database
- 특정 UI Library
- 특정 Backend Framework
- 특정 Agent Framework
또한 Chat Interaction Pattern이 모든 AI 기능을 Chat으로 구현해야 한다는 의미도 아니다.
사용자의 목표 달성을 위해 구조화된 Form, Wizard, Button, Timeline 등의 UI가 더 적합한 경우에는 다른 Interaction Pattern과 조합해야 한다.
---
### 7. Core Design Principle
Chat Interaction Pattern의 핵심 원칙은 다음 한 문장으로 요약할 수 있다.
> **AI는 사용자의 말을 그대로 처리하는 것이 아니라 사용자가 달성하려는 목표를 이해하고, 그 목표를 가장 안전하고 명확한 방식으로 달성하도록 지원해야 한다.**
이를 설계 원칙으로 표현하면 다음과 같다.
```plain text
User says X
     ↓
AI understands Goal Y
     ↓
AI determines required Context
     ↓
AI selects appropriate action
     ↓
AI provides Result Z
     ↓
User confirms / edits / continues
```
---
### 8. Reference Architecture
기본적인 Chat Interaction Architecture는 다음과 같다.
```plain text
┌──────────────────────┐
│        User          │
└──────────┬───────────┘
           │
           ▼
┌──────────────────────┐
│   Conversation UI    │
└──────────┬───────────┘
           │
           ▼
┌──────────────────────┐
│ Conversation Gateway │
└──────────┬───────────┘
           │
           ▼
┌──────────────────────┐
│ Intent / Context     │
│ Resolution Layer     │
└──────────┬───────────┘
           │
           ▼
┌──────────────────────┐
│ AI Reasoning /       │
│ Agent Layer          │
└──────────┬───────────┘
           │
           ├──────────────► Tools / Data / Knowledge
           │
           ▼
┌──────────────────────┐
│ Response Validation  │
└──────────┬───────────┘
           │
           ▼
┌──────────────────────┐
│ Response Presentation │
└──────────┬───────────┘
           │
           ▼
          User
```
---
### 9. User Control Model
Chat Interaction Pattern은 AI의 자동화를 최대화하는 것보다 **사용자가 AI의 행동을 이해하고 통제할 수 있는 것**을 우선한다.
특히 다음 행동은 사용자에게 명확히 표시하는 것을 원칙으로 한다.
- 정보 생성
- 정보 수정
- 데이터 저장
- 데이터 삭제
- 외부 서비스 호출
- 비용이 발생할 수 있는 작업
- 다른 사용자와의 공유
- 공개 상태 변경
AI가 단순히 답변을 생성하는 경우와 실제 제품 상태를 변경하는 경우를 동일하게 취급해서는 안 된다.
```plain text
Informational Response
    ↓
Low Risk
    ↓
Usually Automatic

State-changing Action
    ↓
Higher Risk
    ↓
Confirmation / Permission as Required
```
---
### 10. RoRo Application
RoRo에서 Chat Interaction Pattern은 **자연어 기반 여행 기록 Assistant의 기본 진입점**으로 활용할 수 있다.
예를 들어 사용자가 다음과 같이 입력할 수 있다.
> "어제 찍은 사진으로 여행일기 만들어줘."
RoRo는 이를 단순히 텍스트 생성 요청으로 처리하지 않고 다음과 같이 해석할 수 있다.
```plain text
User Request
    ↓
"여행일기 생성"
    ↓
Identify Trip
    ↓
Identify Date
    ↓
Find Relevant Photos
    ↓
Resolve Schedule / Location / Expense Context
    ↓
Generate Draft
    ↓
Present Draft
    ↓
User Edit / Approve
    ↓
Save Memory
```
이 구조에서 Chat Interaction Pattern은 전체 기능을 직접 수행하지 않는다.
대신 사용자의 의도를 제품의 적절한 기능과 연결하는 **Interaction Layer** 역할을 수행한다.
---
### 11. Pattern Boundary
Chat Interaction Pattern의 책임은 다음 범위까지로 제한한다.
**Responsible**
- 자연어 입력 수집
- 대화 Context 연결
- 의도 해석
- Clarification
- 결과 전달
- 후속 대화 지원
**Not Responsible**
- 전문적인 업무 실행 자체
- 복잡한 Workflow orchestration
- 장기 Memory 저장 정책
- 최종 품질 판정
- 권한 정책 자체
이러한 책임은 각각 별도의 Pattern 또는 Architecture Layer로 분리한다.
예:
```plain text
Chat Interaction
      ↓
Orchestrator
      ↓
Specialist Agent
      ↓
Reviewer
      ↓
Memory / Storage
```
---
### 12. Key Risks
Chat Interaction Pattern의 주요 위험은 다음과 같다.
| Risk | Description | Primary Control |
| --- | --- | --- |
| Intent Misinterpretation | 사용자 의도를 잘못 이해 | Clarification |
| Context Drift | 대화가 길어지며 의미가 변질 | Context Management |
| Hallucination | 근거 없는 정보 생성 | Validation / Retrieval |
| Over-Automation | 사용자가 원하지 않는 행동 수행 | Permission / Confirmation |
| Prompt Injection | 악의적 입력으로 동작 변경 | Input / Tool Guardrail |
| Privacy Leakage | 불필요한 개인정보 노출 | Data Minimization |
| Infinite Loop | 대화가 종료되지 않음 | Completion Criteria |
---
### 13. Quality Gate
Chat Interaction Pattern을 Production에 적용하기 전에 최소한 다음 항목을 검증해야 한다.
```plain text
□ User intent can be represented naturally
□ Ambiguous requests can trigger clarification
□ Required context can be resolved
□ Context does not drift unexpectedly
□ High-risk actions require appropriate control
□ AI uncertainty can be surfaced
□ Conversation can terminate successfully
□ User can correct AI output
□ User can undo or recover from supported actions
□ Logs allow major interaction failures to be diagnosed
```
---
### 14. Strategic Significance
Chat Interaction Pattern은 AI Product의 단순한 UI 패턴이 아니라 **AI와 사용자 사이의 기본 Operating Model**이다.
따라서 RoRo에서는 Chat을 모든 기능의 최종 UI로 간주하지 않고 다음과 같이 정의한다.
> **Chat은 사용자의 목표를 AI Capability로 연결하는 가장 유연한 Entry Point 중 하나다.**
이에 따라 Chat은 다른 Interaction Pattern과 조합되어야 한다.
```plain text
Chat
 ├── Copilot
 ├── Wizard
 ├── Guided Workflow
 ├── Conversational Form
 ├── Progressive Disclosure
 └── Human Escalation
```
---
### 15. Section Conclusion
AI-PATTERN-001 Chat Interaction Pattern은 사용자가 자연어로 목표를 표현하고 AI가 그 목표를 이해하여 적절한 정보 또는 행동으로 연결하는 기본 상호작용 표준이다.
그러나 Chat의 핵심 가치는 "대화할 수 있음" 자체가 아니다.
핵심은 다음 세 가지다.
1. **사용자의 목표를 이해한다.**
2. **불확실한 경우 확인한다.**
3. **AI가 수행하는 행동에 대해 사용자의 통제권을 보장한다.**
이 세 가지 원칙은 이후의 모든 Interaction Pattern과 연결되는 기본 원칙으로 사용한다.
---
## Document Navigation
**Previous**
DOC-032-PART-III — Interaction Patterns Overview
**Current**
DOC-032-P3-001-01 — AI-PATTERN-001 / Executive Summary
**Next**
DOC-032-P3-001-02 — Problem Statement & Motivation
**Related Patterns**
- AI-PATTERN-002 Copilot Pattern
- AI-PATTERN-003 Wizard Pattern
- AI-PATTERN-007 Multi-turn Conversation Pattern
- AI-PATTERN-008 Human Escalation Pattern
**Related Documents**
- DOC-032-PART-I — Introduction & Pattern Philosophy
- DOC-032-PART-II — Pattern Specification Standard
---
## document_id: DOC-032-P3-001-02
parent_document: DOC-032
part: III
pattern_id: AI-PATTERN-001
section: 001-02
title: Problem Statement & Motivation
document_type: AI Design Pattern Specification
version: 1.0.0
status: Draft
language: ko-KR
