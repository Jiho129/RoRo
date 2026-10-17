<!-- Source: Notion page [001 Document Philosophy](https://app.notion.com/p/3a8dff1c1f7480ad98cbf30be1a7332d?pvs=204). Page ID: 3a8dff1c-1f74-80ad-98cb-f30be1a7332d. Path: My Travel - RoRo / 100 📖 Foundation / 110 Documentation. Last edited: 2026-07-27T23:39:27.724Z. -->

# 001 Document Philosophy

---
Book: I
Volume: Foundation
Document No: 001
Title: Document Philosophy
Version: 1.0
Status: Writing
Owner: Jiho Song
Maintainer: RoRo Project
Source of Truth: Markdown
Classification: Constitution
Parent Document:
000_Master_Index.md
Related Documents:
002_Document_Structure.md
003_Document_Lifecycle.md
004_Versioning_Policy.md
---
# Book I
# Foundation
# Document 001
# Document Philosophy
> **"Products are not built from code.
They are built from decisions.
Documentation is where those decisions live."**
---
# Preface
## Before You Read
이 문서는 문서 작성법을 설명하는 문서가 아니다.
Markdown 문법을 설명하는 문서도 아니다.
GitHub 사용법을 설명하는 문서도 아니다.
RoRo 프로젝트에서 Documentation은 하나의 도구가 아니라 **제품을 구성하는 핵심 시스템(System)** 이다.
따라서 본 문서는 프로젝트의 모든 문서보다 우선하는 철학을 정의한다.
앞으로 작성될 Product Bible, Technical Architecture, UX Guideline, Design System, API Specification, AI Prompt, Decision Log는 모두 본 문서의 철학을 따라야 한다.
본 문서를 읽는 독자는 다음 중 한 명일 수 있다.
- 프로젝트를 처음 맡은 Product Manager
- UX Designer
- Backend Engineer
- Frontend Engineer
- AI Engineer
- QA Engineer
- 미래의 나 자신
- AI Coding Agent
이들은 프로젝트의 역사도, 회의도, 채팅도 알지 못한다.
그러므로 이 문서는 어떤 전제 지식도 요구하지 않는다.
모든 내용은 문서 자체만으로 이해 가능해야 한다.
---
## Why This Document Exists
RoRo 프로젝트는 하나의 문제의식에서 출발하였다.
프로젝트는 성장할수록 코드보다 **의사결정의 이유**가 먼저 사라진다.
처음에는 모든 사람이 기억한다.
왜 이 구조를 선택했는지.
왜 이 기능을 넣었는지.
왜 어떤 기능은 제외했는지.
왜 특정 이름을 선택했는지.
하지만 프로젝트가 커질수록 기억은 사람에게 의존하게 된다.
사람은 회사를 떠난다.
회의는 잊힌다.
채팅은 검색되지 않는다.
그러나 제품은 계속 유지되어야 한다.
RoRo는 이 문제를 해결하기 위해 만들어진 프로젝트이기도 하다.
우리는 여행의 기억을 보존하려고 한다.
동시에 프로젝트 자신의 기억도 보존하려고 한다.
제품이 기억을 다루면서 정작 자신의 기억을 잃어버리는 것은 가장 큰 모순이다.
이 문서는 그 모순을 방지하기 위해 존재한다.
---
# Chapter 1
# Why Documentation Exists
## Documentation is not a Deliverable
많은 조직에서는 문서를 산출물(Deliverable)로 취급한다.
프로젝트가 끝나면 작성하는 것.
감사를 대비하기 위해 작성하는 것.
인수인계를 위해 마지막에 정리하는 것.
RoRo는 이러한 관점을 채택하지 않는다.
문서는 프로젝트의 마지막 결과물이 아니다.
문서는 프로젝트를 구성하는 핵심 요소이다.
제품은 다음 요소가 결합되어 만들어진다.
- Problem
- Vision
- Philosophy
- Decision
- Design
- Architecture
- Implementation
- Validation
- Learning
이 중 코드가 표현하는 것은 Implementation뿐이다.
나머지는 코드만으로는 설명할 수 없다.
따라서 Documentation은 코드를 설명하기 위해 존재하는 것이 아니라,
**코드가 존재하는 이유를 설명하기 위해 존재한다.**
---
## Documentation is Memory
RoRo의 핵심 철학은 Memory이다.
우리는 여행의 기억을 보존하려고 한다.
하지만 프로젝트 역시 기억을 가진다.
예를 들어 다음과 같은 질문을 생각해보자.
- 왜 Moment가 가장 작은 단위인가?
- 왜 Timeline이 아니라 Story를 선택했는가?
- 왜 AI는 자동 게시를 하지 않는가?
- 왜 Privacy를 기본값으로 설정했는가?
- 왜 가족 중심으로 MVP를 시작하는가?
이 질문의 답은 코드 안에 존재하지 않는다.
Database에도 없다.
Figma에도 없다.
답은 사람의 기억 속에만 존재한다.
문서는 사람의 기억을 외부에 저장하는 시스템이다.
즉,
**Documentation은 프로젝트의 장기 기억(Long-term Memory)이다.**
---
## Documentation Creates Shared Reality
제품 개발은 여러 사람이 함께 하나의 현실을 만들어가는 과정이다.
그러나 사람은 모두 다른 배경을 가진다.
디자이너는 화면을 먼저 본다.
개발자는 구조를 먼저 본다.
기획자는 사용자 문제를 먼저 본다.
AI는 입력된 정보만 본다.
만약 공통된 기준이 없다면 모두 서로 다른 제품을 상상하게 된다.
결국 회의는 늘어나고, 수정은 반복되며, 프로젝트는 방향을 잃는다.
Documentation은 이러한 문제를 해결한다.
문서는 프로젝트 구성원이 공유하는 **공통 현실(Shared Reality)** 을 만든다.
모든 사람은 같은 문서를 보고,
같은 문제를 이해하고,
같은 철학을 기준으로 의사결정을 내린다.
---
# Chapter 2
# The Cost of Forgotten Knowledge
## Every Project Loses Knowledge
모든 프로젝트는 지식을 잃는다.
문제는 지식을 잃는다는 사실이 아니라,
언제 잃어버렸는지조차 모른다는 것이다.
프로젝트 초기에 내렸던 결정은 시간이 지나며 '당연한 것'으로 여겨진다.
그리고 어느 순간, 아무도 그 이유를 설명하지 못한다.
이 현상을 우리는 **Knowledge Loss**라고 정의한다.
Knowledge Loss는 버그보다 위험하다.
버그는 발견된다.
지식의 손실은 발견되지 않는다.
---
## The Hidden Cost
지식을 잃으면 다음과 같은 비용이 발생한다.
### 동일한 논의를 반복한다.
이미 결론이 난 문제를 다시 토론한다.
### 동일한 실수를 반복한다.
과거에 실패했던 방식을 다시 시도한다.
### 철학이 변질된다.
사용자 경험보다 구현 편의가 우선된다.
### 기술 부채가 증가한다.
원래 의도와 다른 코드가 계속 추가된다.
### 신규 인원의 학습 비용이 증가한다.
프로젝트를 이해하는 데 수개월이 걸린다.
---
## Knowledge Debt
기술 부채(Technical Debt)는 널리 알려져 있다.
RoRo는 여기에 하나를 더 정의한다.
**Knowledge Debt**
지식을 기록하지 않아 미래에 발생하는 모든 비용을 의미한다.
예를 들어,
"왜 AI가 일기를 자동 저장하지 않는가?"
라는 질문에 답하는 문서가 없다면,
미래의 개발자는 사용자의 승인 절차를 제거할 수도 있다.
그 결과 제품 철학은 무너진다.
이러한 비용은 코드 수정 비용보다 훨씬 크다.
Knowledge Debt는 조용히 쌓이며,
프로젝트의 정체성을 조금씩 침식한다.
---
## Documentation as an Investment
문서를 작성하는 것은 비용처럼 보인다.
하지만 실제로는 미래를 위한 투자이다.
좋은 문서는 다음과 같은 가치를 만든다.
- 동일한 질문에 반복적으로 답하지 않아도 된다.
- 새로운 팀원이 빠르게 프로젝트를 이해할 수 있다.
- AI가 프로젝트의 맥락을 정확히 이해한다.
- 설계 변경 시 영향 범위를 쉽게 분석할 수 있다.
- 의사결정의 일관성이 유지된다.
문서는 프로젝트의 속도를 늦추지 않는다.
오히려 장기적으로 가장 큰 속도 향상을 만든다.
---
## Closing Reflection
RoRo는 사람의 기억을 보존하는 제품이다.
그러므로 프로젝트 자신도 기억을 잃어서는 안 된다.
우리가 남기는 모든 문서는 미래의 팀원에게 보내는 편지이며,
미래의 우리 자신에게 남기는 설명서이다.
문서를 작성하는 목적은 과거를 기록하는 것이 아니다.
미래가 같은 실수를 반복하지 않도록 만드는 것이다.
---
**Architecture Notes**
- 본 문서는 RoRo Documentation Constitution의 시작점이다.
- 이후 모든 문서는 "기억을 보존한다"는 철학을 공유해야 한다.
- Documentation은 프로젝트의 Long-term Memory Layer로 정의한다.
**Decision Records**
- ADR-001: Markdown을 Source of Truth로 사용한다. (상세 내용은 추후 ADR 문서에서 정의)
- ADR-002: Documentation Driven Development를 프로젝트 기본 원칙으로 채택한다.
**Related Documents**
- 000_Master_Index.md
- 002_Document_Structure.md
- 020_Decision_Framework.md
- 230_Project_History.md
# Chapter 4
# The History of Documentation
## Understanding the Origin of Documentation
문서는 소프트웨어 산업에서 시작되지 않았다.
인류는 문자가 만들어지기 전부터 지식을 전달하기 위한 방법을 고민해 왔다.
동굴 벽화는 단순한 그림이 아니었다.
그것은 다음 세대에게 전달하기 위한 정보 저장 장치였다.
농경 사회에서는 계절과 수확량을 기록하였다.
항해 시대에는 별의 위치와 해류를 기록하였다.
건축가는 도면을 남겼다.
과학자는 실험 노트를 남겼다.
법률가는 판례를 남겼다.
이 모든 기록의 목적은 동일했다.
> "기억을 사람에게만 의존하지 않는다."
Documentation의 본질은 기록이 아니라 **지식의 외부화(Externalization of Knowledge)** 이다.
RoRo 역시 같은 철학을 따른다.
우리는 여행의 기억을 외부화한다.
동시에 제품을 만드는 과정의 기억도 외부화한다.
---
## The Industrial Revolution of Knowledge
산업혁명 이후 문서는 또 다른 역할을 갖게 된다.
대규모 조직은 개인의 기억만으로 운영될 수 없었다.
공장은 작업 매뉴얼을 만들었다.
철도 회사는 운영 절차를 만들었다.
군대는 작전 교범을 만들었다.
병원은 진료 프로토콜을 만들었다.
조직이 커질수록 문서는 선택이 아니라 필수가 되었다.
왜냐하면 조직의 규모가 커질수록 개인의 기억보다 **조직의 기억**이 더 중요해졌기 때문이다.
RoRo도 마찬가지이다.
현재는 한 명의 기획자가 대부분의 의사결정을 기억하고 있을 수 있다.
그러나 프로젝트가 성장하면 이러한 방식은 반드시 실패한다.
문서는 조직의 규모를 확장하기 위한 전제조건이다.
---
## Software Changed the Nature of Documentation
소프트웨어 산업은 문서의 역할을 크게 바꾸었다.
초기의 프로그램은 단순했다.
개발자는 자신이 작성한 코드를 모두 이해할 수 있었다.
그러나 소프트웨어가 복잡해질수록 새로운 문제가 생겼다.
코드는 동작을 설명한다.
하지만 **의도(Intention)** 는 설명하지 않는다.
다음 코드를 생각해보자.
```plain text
if (approvalRequired) {
    ...
}
```
이 코드는 승인 절차가 있다는 사실만 보여준다.
그러나 다음 질문에는 답하지 못한다.
- 왜 승인이 필요한가?
- 어떤 사용자 경험을 보호하기 위한 것인가?
- 자동 승인과 비교했는가?
- MVP에서도 필요한가?
- 미래에도 유지되어야 하는가?
이 질문의 답은 코드가 아니라 문서에 존재해야 한다.
---
## Documentation Through the AI Era
AI의 등장으로 많은 사람들이 문서의 필요성이 줄어들 것이라고 예상했다.
그러나 현실은 정반대였다.
AI는 입력된 정보만 이해한다.
맥락이 없으면 추론한다.
추론은 종종 틀린다.
즉,
AI 시대일수록
정확한 Documentation의 중요성은 더욱 커진다.
AI는 문서를 대체하지 않는다.
오히려 문서를 가장 많이 소비하는 독자가 된다.
RoRo는 AI 시대를 전제로 설계된다.
따라서 모든 문서는 사람이 읽기 쉽고,
동시에 AI가 구조적으로 해석하기 쉬워야 한다.
---
# Chapter 5
# Why Most Documentation Fails
## Failure Pattern 1
### Documentation Becomes an Afterthought
가장 흔한 실패는 문서를 마지막에 작성하는 것이다.
프로젝트 초반에는 시간이 없다는 이유로 미룬다.
출시 직전에는 바쁘다는 이유로 미룬다.
출시 후에는 이미 끝났다는 이유로 미룬다.
결국 문서는 존재하지 않는다.
RoRo는 이를 금지한다.
Documentation은 프로젝트의 시작과 함께 만들어져야 한다.
---
## Failure Pattern 2
### Documentation Explains What, Not Why
많은 문서는 기능을 설명한다.
예를 들어,
"Moment는 여행의 최소 단위이다."
하지만 이것은 정의일 뿐이다.
좋은 문서는 다음까지 설명해야 한다.
- 왜 Trip이 아닌 Moment인가?
- Event와 비교했는가?
- Photo를 최소 단위로 할 수도 있었는데 왜 선택하지 않았는가?
- 이 구조가 AI에게 어떤 장점을 제공하는가?
- 이 구조가 UX에 어떤 영향을 주는가?
RoRo의 모든 문서는 **Why**를 중심으로 작성된다.
---
## Failure Pattern 3
### Documentation Stops Evolving
문서는 살아있는 자산이다.
하지만 대부분의 프로젝트에서는 출시와 동시에 문서의 시간이 멈춘다.
새로운 기능은 코드에만 반영된다.
몇 개월 후 문서는 현실과 완전히 달라진다.
이 상태를 RoRo에서는 **Documentation Drift**라고 정의한다.
Documentation Drift는 버그보다 위험하다.
왜냐하면 잘못된 문서는 잘못된 의사결정을 만든다.
---
## Failure Pattern 4
### Documentation Exists Everywhere
문서가 많다고 좋은 프로젝트는 아니다.
다음과 같은 상황은 매우 위험하다.
- 일부 내용은 Notion에 있다.
- 일부 내용은 Figma에 있다.
- 일부 내용은 Slack에 있다.
- 일부 내용은 이메일에 있다.
- 일부 내용은 개인 메모에 있다.
이 상태에서는 아무도 최신 정보를 확신할 수 없다.
RoRo는 이를 허용하지 않는다.
Markdown만이 Source of Truth이다.
다른 모든 시스템은 표현 계층(Presentation Layer)이다.
---
## Failure Pattern 5
### Documentation Has No Owner
모든 사람이 작성할 수 있는 문서는
결국 아무도 관리하지 않는 문서가 된다.
모든 문서는 반드시 다음을 가져야 한다.
- Author
- Maintainer
- Reviewer
- Approval Status
Ownership 없는 문서는 시간이 지나며 반드시 폐기된다.
---
# Chapter 6
# Knowledge Entropy
## Entropy Exists in Software
물리학에서 엔트로피는 질서가 무질서로 변하는 경향을 의미한다.
프로젝트도 동일하다.
시간이 지날수록
프로젝트는 자연스럽게 복잡해진다.
새로운 기능이 추가된다.
새로운 사람이 참여한다.
새로운 기술이 도입된다.
규칙은 늘어나고,
예외는 증가하며,
맥락은 희미해진다.
이를 우리는 **Knowledge Entropy**라고 정의한다.
---
## The Five Sources of Knowledge Entropy
### 1. Time
시간은 모든 프로젝트의 적이다.
회의 내용은 잊힌다.
결정의 이유는 흐려진다.
문서는 이를 보존해야 한다.
---
### 2. Team Growth
사람이 늘어날수록
암묵지는 공유되지 않는다.
문서는 암묵지를 명시지로 전환한다.
---
### 3. Product Expansion
기능이 많아질수록
철학은 보이지 않게 된다.
RoRo는 기능보다 철학을 먼저 기록한다.
---
### 4. Technology Changes
프레임워크는 바뀐다.
언어도 바뀐다.
AI 모델도 바뀐다.
그러나 제품 철학은 유지되어야 한다.
문서는 기술보다 오래 살아야 한다.
---
### 5. Human Memory
사람의 기억은 정확하지 않다.
같은 회의를 들은 사람도 서로 다른 내용을 기억한다.
기억은 재구성된다.
문서는 기억을 대체하는 것이 아니라
기억의 기준점(Baseline)을 제공한다.
---
## Fighting Entropy
Knowledge Entropy는 제거할 수 없다.
그러나 줄일 수는 있다.
RoRo는 다음 원칙으로 엔트로피에 대응한다.
1. 모든 중요한 결정을 기록한다.
2. Why를 반드시 기록한다.
3. Source of Truth를 하나만 유지한다.
4. Deprecated를 삭제보다 우선한다.
5. Revision History를 남긴다.
6. Living Documentation을 유지한다.
7. AI가 이해할 수 있는 구조로 작성한다.
---
## Architecture Reflection
RoRo는 여행의 기억을 보존하는 제품이다.
동시에 프로젝트의 기억도 보존한다.
사용자가 사진을 잃지 않기를 바라는 것처럼,
우리는 제품의 철학도 잃지 않기를 바란다.
Documentation은 코드의 부속물이 아니다.
Documentation은 프로젝트의 기억 시스템이며,
Knowledge Entropy에 맞서는 가장 중요한 아키텍처이다.
---
## Architecture Notes
- Knowledge Entropy를 RoRo 프로젝트의 공식 개념으로 정의한다.
- Documentation Drift를 주요 프로젝트 리스크로 관리한다.
- 모든 ADR(Architecture Decision Record)은 Knowledge Entropy 감소를 목적으로 작성한다.
## Decision Records
- ADR-003: Documentation Drift를 프로젝트 위험 항목으로 정의한다.
- ADR-004: Knowledge Entropy를 프로젝트 관리 지표에 포함한다.
## Related Documents
- 002_Document_Structure.md
- 003_Document_Lifecycle.md
- 020_Decision_Framework.md
- 117_Decision_Log.md
# Chapter 7
# Documentation as a Product
## The First Product We Build
대부분의 소프트웨어 프로젝트는 다음과 같은 질문으로 시작한다.
> "우리는 무엇을 만들 것인가?"
RoRo는 다른 질문으로 시작한다.
> "우리는 무엇을 이해하고 있는가?"
제품은 이해에서 시작된다.
그리고 이해는 문서에서 시작된다.
따라서 RoRo에서 가장 먼저 만들어지는 산출물은 코드가 아니다.
가장 먼저 만들어지는 제품은 Documentation이다.
Documentation은 제품을 설명하는 문서가 아니다.
Documentation 자체가 제품의 첫 번째 구현(First Implementation)이다.
---
## Documentation Has Users
모든 제품에는 사용자가 있다.
Documentation도 마찬가지다.
RoRo Documentation의 사용자는 다음과 같다.
### Product Manager
제품의 철학과 요구사항을 이해한다.
### UX Designer
사용자의 경험과 설계 원칙을 이해한다.
### Frontend Engineer
화면과 상호작용을 구현한다.
### Backend Engineer
도메인 모델과 API를 구현한다.
### AI Engineer
프롬프트와 컨텍스트를 설계한다.
### QA Engineer
제품이 의도대로 동작하는지 검증한다.
### Future Team Members
프로젝트의 역사와 의사결정을 이해한다.
### AI Coding Agents
문서를 기반으로 정확한 코드를 생성한다.
Documentation은 이 모든 사용자를 위한 제품이다.
따라서 Documentation 역시 사용자 경험(User Experience)을 가져야 한다.
---
## Documentation Has Features
제품은 기능을 가진다.
문서도 기능을 가져야 한다.
RoRo Documentation은 최소한 다음 기능을 수행해야 한다.
- 지식을 저장한다.
- 지식을 전달한다.
- 지식을 검색한다.
- 지식을 연결한다.
- 지식을 검증한다.
- 지식을 발전시킨다.
이 중 하나라도 수행하지 못한다면 문서는 기능적으로 실패한 것이다.
---
## Documentation Has Quality Attributes
좋은 제품은 품질 속성을 가진다.
Documentation도 동일하다.
RoRo는 다음 품질 속성을 정의한다.
### Accuracy
사실과 일치해야 한다.
### Completeness
중요한 맥락이 누락되지 않아야 한다.
### Consistency
다른 문서와 충돌하지 않아야 한다.
### Traceability
모든 결정의 근거를 추적할 수 있어야 한다.
### Maintainability
쉽게 수정할 수 있어야 한다.
### Discoverability
필요한 정보를 쉽게 찾을 수 있어야 한다.
### Readability
사람과 AI 모두 이해하기 쉬워야 한다.
Documentation도 하나의 제품이라면 품질을 측정할 수 있어야 한다.
---
## Documentation is Never Finished
코드는 완료될 수 있다.
하지만 Documentation은 완료되지 않는다.
제품이 변화하는 한,
문서도 함께 변화한다.
RoRo는 Documentation을 Living Product로 정의한다.
---
# Chapter 8
# Documentation Driven Development
## A Different Development Model
전통적인 개발 모델은 다음과 같다.
```plain text
Idea

↓

Code

↓

Test

↓

Documentation
```
RoRo는 이 순서를 채택하지 않는다.
RoRo의 개발 순서는 다음과 같다.
```plain text
Problem

↓

Documentation

↓

Discussion

↓

Decision

↓

Design

↓

Implementation

↓

Validation

↓

Documentation Update
```
문서는 시작점이며,
동시에 마지막 결과물이기도 하다.
---
## Why Documentation Comes First
문서를 먼저 작성하면
아직 구현되지 않은 제품을 검토할 수 있다.
이것은 매우 중요하다.
코드는 변경 비용이 크다.
문서는 변경 비용이 작다.
좋은 프로젝트는
비용이 가장 작은 단계에서 가장 많은 의사결정을 한다.
Documentation Driven Development는
비용을 줄이기 위한 전략이기도 하다.
---
## Documentation Before Design
Figma보다 먼저 작성되는 것은 Product Bible이다.
Design은 문서를 시각화하는 과정이다.
좋은 디자인은
좋은 문서를 기반으로 한다.
반대로
문서 없는 디자인은
예쁜 그림에 불과하다.
---
## Documentation Before Code
코드는 문서를 구현한다.
문서는 코드를 설명하지 않는다.
이 순서는 절대로 뒤바뀌지 않는다.
개발자는 구현 전에 반드시 관련 문서를 읽어야 한다.
문서가 없다면 구현도 존재하지 않는다.
---
## Documentation Before AI
AI Agent 역시 예외가 아니다.
AI에게 다음과 같이 요청하는 것은 금지한다.
> "여행 앱 하나 만들어줘."
반드시 문서를 제공해야 한다.
예를 들어,
- Product Philosophy
- Feature Specification
- API Rules
- UX Constitution
이 제공되어야 한다.
AI는 문서를 읽고 구현해야 한다.
문서를 추측해서는 안 된다.
---
## Documentation Creates Better Decisions
좋은 의사결정은
좋은 정보에서 나온다.
Documentation은
프로젝트의 의사결정 품질을 높인다.
모든 Feature Review는
문서를 기준으로 진행된다.
회의는 의견을 모은다.
문서는 결정을 남긴다.
---
# Chapter 9
# Documentation as a Knowledge Graph
## Documentation is Not a Collection of Files
많은 프로젝트는 문서를 파일의 집합으로 관리한다.
RoRo는 그렇게 생각하지 않는다.
RoRo Documentation은
하나의 거대한 Knowledge Graph이다.
각 문서는 독립적으로 존재하지 않는다.
모든 문서는 서로 연결된다.
예를 들어,
"Moment"
라는 문서는 다음 문서와 연결된다.
- Product Philosophy
- Memory First
- AI Storyt
- Timeline
- Database
- API
- UX Flow
- Notification
- Sharing
- AI Prompt
Moment를 이해하려면
이 모든 문서를 함께 이해해야 한다.
---
## Nodes and Relationships
Knowledge Graph에서는
문서는 Node이다.
문서 간 연결은 Relationship이다.
RoRo는 다음 관계를 정의한다.
### Parent
상위 문서
### Child
하위 문서
### Depends On
의존 문서
### Related To
관련 문서
### Replaces
대체 문서
### Deprecated By
폐기 문서
### References
참조 문서
모든 문서는 최소 하나 이상의 관계를 가져야 한다.
고립된 문서는 존재해서는 안 된다.
---
## Knowledge Navigation
사용자는 문서를 읽는 것이 아니다.
지식을 탐색한다.
따라서 문서는 항상
다음 문서로 자연스럽게 이동할 수 있어야 한다.
RoRo Documentation은
책(Book)이면서
동시에 위키(Wiki)이다.
---
## Documentation as Organizational Intelligence
조직의 수준은
사람의 능력으로 결정되지 않는다.
조직이 지식을 얼마나 축적하고 재사용할 수 있는가로 결정된다.
RoRo Documentation은
단순한 프로젝트 문서가 아니다.
프로젝트의 집단 지성(Collective Intelligence)을 저장하는 시스템이다.
새로운 사람은
기억을 이어받는다.
AI는
맥락을 이어받는다.
프로젝트는
철학을 이어받는다.
---
## Architecture Notes
- Documentation을 독립적인 Product로 정의한다.
- Documentation Driven Development를 공식 개발 프로세스로 채택한다.
- RoRo Documentation을 Knowledge Graph 구조로 관리한다.
## Decision Records
- ADR-005 : Documentation은 프로젝트의 첫 번째 구현이다.
- ADR-006 : 모든 구현은 관련 문서와 연결되어야 한다.
- ADR-007 : 문서는 파일이 아니라 Knowledge Graph의 Node로 관리한다.
## Related Documents
- 002_Document_Structure.md
- 008_Decision_Framework.md
- 090_Product_Constitution.md
- 097_Database.md
- 103_Prompt_Engineering.md
# Chapter 10
# Documentation Layers
## Introduction
모든 복잡한 시스템은 계층(Layer)을 가진다.
운영체제는 커널과 사용자 공간을 구분한다.
네트워크는 OSI Layer를 가진다.
소프트웨어는 Presentation, Business, Data Layer를 가진다.
Documentation도 예외가 아니다.
RoRo에서는 Documentation을 하나의 평면적인 저장소가 아니라 계층 구조를 가진 시스템(System of Knowledge)으로 정의한다.
계층 구조를 정의하는 목적은 단순하다.
**모든 정보는 자신의 위치를 가져야 한다.**
잘못된 위치에 저장된 정보는 시간이 지날수록 프로젝트를 혼란스럽게 만든다.
---
## Why Layers Matter
프로젝트가 작을 때는 모든 내용을 하나의 문서에 적어도 문제가 없다.
그러나 프로젝트가 성장하면 다음과 같은 문제가 발생한다.
- 제품 철학과 구현 세부사항이 한 문서에 섞인다.
- UX 규칙과 API 규칙이 같은 페이지에 존재한다.
- AI Prompt가 Feature Specification과 충돌한다.
- 동일한 정의가 여러 문서에서 반복된다.
- 어떤 문서를 수정해야 하는지 알 수 없다.
이러한 문제를 해결하기 위해 Documentation Layer를 정의한다.
---
## The Seven Layers of RoRo Documentation
RoRo Documentation은 다음 일곱 개의 계층으로 구성된다.
### Layer 1 — Philosophy
가장 상위 계층이다.
제품이 존재하는 이유를 정의한다.
예시
- Vision
- Mission
- Core Values
- Memory First
- Privacy First
이 계층은 거의 변경되지 않는다.
---
### Layer 2 — Constitution
제품이 반드시 지켜야 하는 원칙을 정의한다.
예시
- AI Constitution
- UX Constitution
- Privacy Constitution
- Product Rules
Constitution은 철학을 실제 규칙으로 변환한다.
---
### Layer 3 — Knowledge
도메인 지식을 축적하는 계층이다.
예시
- 여행 행동 연구
- 사용자 인터뷰
- 경쟁사 분석
- Memory Psychology
- AI Research
Knowledge는 제품의 근거(Evidence)를 제공한다.
---
### Layer 4 — Specification
무엇을 만들 것인지 정의한다.
예시
- Feature Specification
- Product Bible
- PRD
- Screen Specification
개발자는 대부분 이 계층을 직접 사용한다.
---
### Layer 5 — Design
Specification을 사용자 경험으로 변환한다.
예시
- UX Flow
- Wireframe
- Design System
- High Fidelity UI
Figma는 이 계층에 속한다.
---
### Layer 6 — Engineering
Design을 실제 시스템으로 구현한다.
예시
- Architecture
- API
- Database
- Backend
- Frontend
- AI Prompt
GitHub와 코드베이스는 이 계층에 속한다.
---
### Layer 7 — Operations
제품을 운영하기 위한 계층이다.
예시
- Sprint
- Release
- QA
- Monitoring
- Analytics
- Roadmap
운영은 개발 이후에 시작되는 것이 아니라 제품과 함께 지속된다.
---
## Layer Dependency
각 계층은 아래 방향으로만 의존할 수 있다.
```plain text
Philosophy

↓

Constitution

↓

Knowledge

↓

Specification

↓

Design

↓

Engineering

↓

Operations
```
상위 계층은 하위 계층을 알 필요가 없다.
반대로 하위 계층은 반드시 상위 계층을 이해해야 한다.
예를 들어 API는 Vision을 직접 구현하지 않지만, Vision과 모순되어서는 안 된다.
---
## Layer Violation
다음은 계층 위반(Layer Violation)으로 간주한다.
- API 문서에서 제품 철학을 정의하는 경우
- Figma에서 기능 요구사항을 변경하는 경우
- 코드에서 UX 정책을 결정하는 경우
- 운영 문서에서 아키텍처를 변경하는 경우
모든 변경은 해당 계층의 문서에서 먼저 이루어져야 한다.
---
#
# Chapter 11
# Single Source of Truth
---
## Principle
RoRo 프로젝트는 하나의 절대 원칙을 가진다.
> **Every Fact Has One Home.**
모든 사실(Fact)은 단 하나의 공식 위치(Official Location)만 가져야 한다.
동일한 정보가 두 곳 이상 존재하는 순간,
프로젝트는 두 개 이상의 진실(Two Truths)을 가지게 된다.
두 개 이상의 진실은 반드시 불일치로 이어진다.
RoRo는 이를 프로젝트의 가장 위험한 상태 중 하나로 정의한다.
---
## Why This Principle Exists
RoRo 초기에는 여러 도구를 함께 사용하였다.
- ChatGPT
- Notion
- GitHub
- Figma
- 개인 메모
- Google Spreadsheet
각 도구는 목적이 달랐다.
하지만 중요한 문제는
같은 내용이 여러 곳에 존재하기 시작했다는 것이다.
예를 들어,
Product Bible은 Notion에 있고,
UX는 Figma에 있으며,
Architecture는 ChatGPT 대화 안에 존재했다.
이 상태에서는 다음 질문에 답할 수 없었다.
> "최신 정보는 어디에 있는가?"
이 질문에 즉시 답하지 못하는 순간,
Source of Truth는 존재하지 않는 것이다.
---
## Case Study
### Sprint 6
RoRo Delivery Sprint 6에서는
Notion Connector와 Figma Connector를 연결하였다.
초기 목표는
ChatGPT
↓
Notion 생성
↓
Figma 생성
↓
GitHub 생성
순으로 자동화하는 것이었다.
하지만 실제 프로젝트에서는 여러 제약을 경험하였다.
대표적으로
- Connector 권한 제한
- MCP 세션 제약
- 생성 성공 여부 확인의 어려움
- 동일 문서의 중복 관리
이 경험을 통해 프로젝트는 중요한 결정을 내렸다.
> "도구는 Source of Truth가 될 수 없다."
도구는 언제든 바뀔 수 있다.
그러나 프로젝트의 지식은 도구에 종속되어서는 안 된다.
---
## Official Definition
RoRo는 다음을 공식 정의한다.
### Markdown Repository
유일한 Source of Truth
역할
- 공식 원본
- 변경 이력
- 제품 철학
- Feature 정의
- ADR 저장
---
### Notion
Knowledge Workspace
역할
- 탐색
- 협업
- 읽기
- 프로젝트 관리
Notion은 원본이 아니다.
---
### Figma
Design Workspace
역할
- UX 표현
- Interaction
- Design System
- Prototype
Figma는 원본이 아니다.
---
### GitHub
Implementation Workspace
역할
- Source Code
- CI/CD
- Release
GitHub는 코드의 원본이다.
제품 철학의 원본은 아니다.
---
## Information Flow
정보는 항상 아래 방향으로 이동한다.
Markdown
↓
Notion
↓
Figma
↓
GitHub
↓
Running Product
역방향 수정은 허용되지 않는다.
예를 들어
GitHub에서 API를 수정하였다면
Markdown을 먼저 수정해야 한다.
그 후
다른 시스템을 동기화한다.
---
## Architecture Decision
ADR-012
**Markdown Repository를 프로젝트의 유일한 Source of Truth로 채택한다.**
Status
Accepted
Reason
- Tool Independence
- Long-term Preservation
- AI Compatibility
- Version Control
- Portability
---
# Chapter 12
# Living Documentation
---
## Principle
문서는 완료되는 순간부터 낡기 시작한다.
Documentation은 제품과 함께 성장해야 한다.
RoRo는 Documentation을
Static Asset이 아니라
Living System으로 정의한다.
---
## Documentation Never Ends
많은 프로젝트는
출시
↓
문서 작성 종료
라는 흐름을 가진다.
RoRo는 이를 허용하지 않는다.
제품이 살아있는 동안
문서도 살아있다.
---
## Revision Is Knowledge
수정은 실패의 증거가 아니다.
수정은 학습의 결과이다.
좋은 프로젝트일수록
Revision History가 길다.
문서가 오랫동안 수정되지 않았다면
다음 두 가지 가능성을 의심해야 한다.
1.
제품이 죽었다.
또는
1.
문서가 죽었다.
---
## Documentation Evolution
RoRo Documentation은
삭제(Delete)를 기본으로 하지 않는다.
Evolution을 기본으로 한다.
즉
Wrong
↓
Deprecated
↓
Replaced
↓
Archived
순으로 관리한다.
과거의 의사결정은
프로젝트의 역사이기 때문이다.
---
## Case Study
RoRo 브랜드 역시
처음부터 RoRo가 아니었다.
프로젝트에서는
Replay
Rememo
KERO
EO
MyMoment
등 여러 이름을 검토하였다.
최종적으로
RoRo가 선택되었다.
이 과정은 삭제되지 않는다.
브랜드의 진화 과정 역시
제품의 중요한 역사이기 때문이다.
---
## Architecture Decision
ADR-013
모든 중요한 변경은
Revision History에 남긴다.
삭제보다
Deprecated를 우선한다.
---
# Chapter 13
# Documentation as Organizational Memory
---
## Principle
사람은 기억한다.
조직은 기록한다.
RoRo는
Documentation을
Organizational Memory라고 정의한다.
---
## Human Memory Cannot Scale
프로젝트 초반에는
모든 사람이
모든 결정을 기억한다.
하지만 프로젝트는 성장한다.
기능은 늘어난다.
사람이 늘어난다.
시간이 흐른다.
기억은 반드시 사라진다.
문서는
사람의 기억을 대체하는 것이 아니다.
사람의 기억을 보존하는 장치이다.
---
## Organizational Memory
RoRo Documentation은
다음 내용을 기억한다.
Vision
Mission
Decision
Architecture
UX
Research
Experiment
Failure
Lessons Learned
Future Ideas
즉
프로젝트의 모든 기억을 저장한다.
---
## Memory Categories
RoRo는 기억을 다음 다섯 가지로 분류한다.
### Philosophical Memory
왜 존재하는가.
---
### Product Memory
무엇을 만들기로 했는가.
---
### Technical Memory
어떻게 구현하는가.
---
### Operational Memory
어떻게 운영하는가.
---
### Historical Memory
왜 현재 모습이 되었는가.
---
## Case Study
RoRo MVP는
모든 여행자를 대상으로 하지 않았다.
첫 번째 사용자는
프로젝트 작성자의 가족이었다.
이 결정에는 여러 이유가 있었다.
- 가장 빠른 검증 가능
- 실제 여행 일정 존재
- 사진 확보 가능
- 피드백 즉시 가능
- 실패 비용 최소
이 결정은
단순한 MVP Scope가 아니라
Product Philosophy의 일부이다.
따라서
Product Memory로 보존한다.
---
## Lessons Learned
프로젝트는
기억을 다루는 제품이다.
따라서
프로젝트 자신도
기억을 잃어서는 안 된다.
RoRo Documentation은
제품의 기억 시스템이며
동시에
조직의 기억 시스템이다.
---
## Architecture Decisions
ADR-014
Documentation을 Organizational Memory로 정의한다.
ADR-015
모든 Product Decision은 Organizational Memory에 영구 보존한다.
---
## Related Documents
002_Document_Structure.md
020_Architecture_Decision_Record.md
021_Project_History.md
022_Lessons_Learned.md
090_Product_Philosophy.md
091_Memory_First.md
# Chapter 14
# Documentation and AI
---
## Principle
RoRo는 AI를 개발자나 기획자를 대체하는 존재로 정의하지 않는다.
AI는 프로젝트의 **Collaborative Intelligence**이다.
AI는 아이디어를 제안하고,
문서를 정리하며,
구현을 지원하고,
반복 작업을 자동화한다.
그러나 제품의 철학과 최종 의사결정은 인간에게 남겨둔다.
RoRo는 이 원칙을 **Human Authority Principle**이라 정의한다.
---
## Why This Principle Exists
RoRo는 AI를 적극적으로 활용하는 프로젝트이다.
Product Bible
PRD
UX
Figma
Architecture
Code
QA
Documentation
모든 단계에서 AI가 참여한다.
그러나 AI는 프로젝트의 역사와 사용자의 삶을 직접 경험하지 않는다.
AI는 입력된 정보를 기반으로 추론한다.
반대로 사용자는 실제 여행을 경험하고,
사진을 촬영하며,
감정을 느끼고,
가족과 추억을 만든다.
RoRo는 기억을 다루는 서비스이므로,
기억의 최종 소유권은 사용자에게 있다.
---
## Human Authority Principle
RoRo는 다음 원칙을 채택한다.
AI는
- 제안(Propose)할 수 있다.
- 초안(Draft)을 만들 수 있다.
- 정리(Organize)할 수 있다.
- 추천(Recommend)할 수 있다.
AI는 다음을 수행해서는 안 된다.
- 사용자의 기억을 수정한다.
- 존재하지 않는 사실을 확정한다.
- 사용자의 의사 없이 공개한다.
- 여행의 감정을 대신 결정한다.
- 경험하지 않은 사건을 사실처럼 기록한다.
---
## Constitution Rule
### Rule 14-1
AI Generated ≠ User Approved
AI가 생성한 모든 결과는 초안이다.
최종 기록은 사용자가 승인해야 한다.
---
### Rule 14-2
Memory Ownership Belongs to Users
모든 기억의 소유권은 사용자에게 있다.
AI는 기억을 관리할 뿐,
소유하지 않는다.
---
### Rule 14-3
Never Rewrite Human Experience
사용자의 실제 경험을
AI가 더 "좋은 이야기"로 바꾸지 않는다.
표현은 개선할 수 있다.
사실은 변경할 수 없다.
---
## RoRo Case Study
MVP 설계 과정에서 다음 기능을 검토하였다.
> "여행이 끝나면 AI가 자동으로 여행일기를 게시한다."
기능적으로는 구현이 가능하였다.
그러나 다음 문제가 있었다.
- 사용자가 원하지 않는 사진이 포함될 수 있다.
- 가족 사진이 외부로 공유될 수 있다.
- AI가 잘못 선택한 사진이 대표 이미지가 될 수 있다.
- 사용자의 감정과 다른 내용이 게시될 수 있다.
프로젝트는 이 기능을 채택하지 않았다.
대신 다음 원칙을 선택하였다.
> AI는 자동 생성하지만,
게시는 사용자가 승인한다.
이 결정은 Product Philosophy의 일부이다.
---
## AI Confidence
AI는 자신의 확신 수준을 표현해야 한다.
예시
★★★★★
사진과 일정이 모두 존재
↓
신뢰도 매우 높음
★★★★☆
사진은 있으나 위치 정보 부족
★★★☆☆
사진만 존재
★★☆☆☆
사용자의 일정만 존재
★☆☆☆☆
추론만 존재
신뢰도가 낮은 결과는
사용자에게 반드시 알려야 한다.
---
## Architecture Decision
ADR-016
AI는 Product Owner가 아니다.
ADR-017
AI는 사용자의 기억을 수정할 수 없다.
ADR-018
AI Generated Content는 User Approval 이후에만 Published 상태가 된다.
---
# Chapter 15
# Documentation and Decision Making
---
## Principle
좋은 프로젝트는
좋은 결정을 많이 내리는 프로젝트가 아니다.
좋은 결정을 **기록하는 프로젝트**이다.
기억은 사라진다.
결정은 왜 내려졌는지가 사라진다.
RoRo는 모든 중요한 결정을
문서화한다.
---
## Decisions Are First-Class Assets
RoRo는 의사결정을
프로젝트의 핵심 자산으로 정의한다.
기능은 변경될 수 있다.
UI도 변경될 수 있다.
기술도 변경될 수 있다.
그러나
왜 그런 결정을 내렸는지는
프로젝트의 역사이다.
---
## Decision Categories
모든 결정은 다음으로 분류한다.
### Product Decision
예
Moment 선택
Story 선택
Family MVP
---
### UX Decision
예
Bottom Navigation
Dashboard 구조
AI Review Flow
---
### Technical Decision
예
Flutter 선택
Firebase 여부
Markdown Repository
---
### Business Decision
예
MVP Scope
Premium 기능
AI 비용 전략
---
### Organizational Decision
예
Documentation Driven Development
Source of Truth
Sprint 운영 방식
---
## Every Decision Needs Context
다음과 같은 기록은 금지한다.
> Moment를 선택하였다.
반드시 다음을 기록한다.
왜 선택했는가.
무엇과 비교했는가.
무엇을 포기했는가.
언제 다시 검토할 것인가.
---
## Trade-off Recording
RoRo는 Trade-off를 반드시 기록한다.
예시
Moment
장점
- AI 분석 용이
- Story 생성 용이
- 확장 가능
단점
- 모델이 복잡해짐
- 초기에 이해하기 어려움
Trade-off 없는 설계는
존재하지 않는다.
---
## Constitution Rule
Rule 15-1
모든 Product Decision은 ADR을 가진다.
Rule 15-2
Trade-off가 없는 결정은 승인하지 않는다.
Rule 15-3
Rejected Option도 반드시 보존한다.
---
## RoRo Case Study
브랜드명 검토
검토 후보
Replay
Rememo
EO
KERO
RoRo
최종 선택
RoRo
Rejected Option은 삭제하지 않는다.
브랜드의 진화 과정도
제품의 역사이기 때문이다.
---
## Architecture Decision
ADR-019
모든 주요 의사결정은 ADR과 연결한다.
ADR-020
Rejected Decision도 Documentation에 보존한다.
---
# Chapter 16
# Documentation Ownership
---
## Principle
문서는 작성자가 아니라
관리자가 필요하다.
Owner가 없는 문서는
시간이 지나면 반드시 오래된다.
RoRo는 모든 문서에
명확한 Ownership을 부여한다.
---
## Ownership Model
각 문서는 최소 다음 정보를 가진다.
Author
최초 작성자
Maintainer
현재 관리 책임자
Reviewer
품질 검토자
Approver
최종 승인자
Status
Draft
Review
Approved
Published
Deprecated
Archived
---
## Role Definition
### Product Owner
제품 철학을 책임진다.
### Product Manager
요구사항을 책임진다.
### Designer
UX와 Design System을 책임진다.
### Engineer
기술 구현을 책임진다.
### AI Agent
초안 작성,
검색,
요약,
연결을 지원한다.
AI는 문서의 Owner가 될 수 없다.
---
## Ownership Transfer
담당자가 변경되더라도
문서의 역사와 Revision History는 유지한다.
Ownership은 변경될 수 있지만
History는 변경되지 않는다.
---
## Constitution Rules
Rule 16-1
모든 문서는 Owner를 가진다.
Rule 16-2
Owner 없는 문서는 Published 될 수 없다.
Rule 16-3
AI는 Maintainer가 될 수 없다.
Rule 16-4
Owner는 변경될 수 있지만
Revision History는 삭제할 수 없다.
---
## RoRo Case Study
RoRo는 ChatGPT를 활용하여
PRD
UX
Architecture
Product Bible
등을 작성하였다.
그러나 모든 최종 결정은
프로젝트 Owner가 검토하였다.
AI는 생산성을 높였지만
제품의 책임은 인간이 가진다.
이 경험을 바탕으로
RoRo는
Human Authority Principle을
프로젝트 전체에 적용한다.
---
## Architecture Decisions
ADR-021
모든 문서는 명시적인 Owner를 가진다.
ADR-022
AI는 Contributor이지만 Author 또는 Approver가 될 수 없다.
ADR-023
Ownership 변경은 가능하지만 Documentation History는 영구 보존한다.
---
## Related Documents
020_Architecture_Decision_Record.md
021_Project_History.md
022_Lessons_Learned.md
090_Product_Philosophy.md
103_AI_Governance.md
106_Notion_Workspace.md
108_GitHub_Repository.md
# Chapter 17
# Documentation Governance
---
## Principle
문서는 작성보다 운영이 어렵다.
RoRo는 Documentation을 프로젝트의 자산으로 정의하며,
모든 자산은 Governance를 가져야 한다.
Governance의 목적은 문서를 통제하는 것이 아니라,
프로젝트 전체가 동일한 원칙을 따르도록 하는 것이다.
---
## Objectives
Documentation Governance의 목적은 다음과 같다.
- 철학의 일관성 유지
- 중복 제거
- 품질 유지
- 변경 이력 관리
- 장기적인 유지보수
- AI 협업 품질 향상
---
## Governance Principles
### Principle 1 — Consistency Before Speed
빠르게 문서를 만드는 것보다
일관된 문서를 만드는 것이 중요하다.
새로운 기능이 추가되더라도
기존 철학과 충돌해서는 안 된다.
---
### Principle 2 — Documentation Before Implementation
새로운 기능은 구현 전에 반드시 문서화되어야 한다.
승인되지 않은 문서를 기반으로 한 구현은
실험(Experiment)으로 분류하며,
공식 제품에 포함되지 않는다.
---
### Principle 3 — Change Is Visible
모든 중요한 변경은 추적 가능해야 한다.
다음 항목은 반드시 기록한다.
- 변경 일시
- 변경자
- 변경 이유
- 영향 범위
- 관련 ADR
---
### Principle 4 — No Silent Change
조용한 변경(Silent Change)은 금지한다.
기존 의미를 변경하는 수정은
반드시 Revision History에 기록한다.
---
## Governance Levels
RoRo는 문서를 다음 네 단계로 관리한다.
### Level 1 — Draft
초안
### Level 2 — Review
검토 중
### Level 3 — Approved
공식 승인
### Level 4 — Published
프로젝트 표준
---
## RoRo Case Study
Sprint 6에서는 Product Bible의 구조가 여러 차례 변경되었다.
초기에는 기능 중심 구조였으나,
AI와 사람이 함께 사용하는 과정에서
탐색성과 유지보수성이 떨어진다는 문제가 발견되었다.
이에 따라 문서 구조를 '철학 → 제품 → 설계 → 구현 → 운영'의 계층형 구조로 재설계하였다.
이 경험은 이후 모든 문서 구조의 기준이 되었다.
---
## Architecture Decision
ADR-024
모든 공식 문서는 Governance Workflow를 따른다.
ADR-025
Silent Change를 금지한다.
---
# Chapter 18
# Documentation Review
---
## Principle
모든 문서는 검토를 통해 성장한다.
검토의 목적은 오류를 찾는 것이 아니라,
문서의 품질을 높이는 것이다.
---
## Review Objectives
Review는 다음 다섯 가지를 확인한다.
### Accuracy
사실과 일치하는가.
---
### Completeness
필요한 정보가 누락되지 않았는가.
---
### Consistency
다른 문서와 충돌하지 않는가.
---
### Traceability
관련 문서와 ADR을 추적할 수 있는가.
---
### Readability
사람과 AI 모두 이해할 수 있는가.
---
## Multi-Perspective Review
RoRo는 문서를 하나의 관점으로 검토하지 않는다.
각 역할은 서로 다른 질문을 한다.
### Product
이 기능은 제품 철학과 일치하는가.
---
### Design
사용자 경험과 일관성이 있는가.
---
### Engineering
구현 가능한가.
---
### AI
AI가 충분한 맥락을 이해할 수 있는가.
---
### Operations
출시 후 운영 가능한가.
---
## Review Checklist
문서는 Publish 전에 최소한 다음을 만족해야 한다.
- 목적이 명확하다.
- 용어가 일관된다.
- 중복 정의가 없다.
- 참조 문서가 존재한다.
- ADR이 연결되어 있다.
- Owner가 지정되어 있다.
- 상태(Status)가 정의되어 있다.
---
## RoRo Case Study
RoRo는 여러 차례 ChatGPT 세션을 넘나들며 프로젝트를 진행하였다.
세션이 바뀔 때마다 일부 맥락이 손실되었고,
이를 복구하기 위해 많은 시간이 소요되었다.
이 경험을 바탕으로,
문서는 AI 세션을 이어주는 핵심 컨텍스트라는 원칙을 채택하였다.
문서는 사람뿐 아니라 AI도 검토할 수 있어야 한다.
---
## Architecture Decision
ADR-026
모든 Published 문서는 Review Checklist를 만족해야 한다.
ADR-027
AI Readability를 Review 항목에 포함한다.
---
# Chapter 19
# Documentation Quality Model
---
## Principle
품질은 느낌이 아니라 측정 가능한 기준이어야 한다.
RoRo는 Documentation Quality를 정량적·정성적으로 평가한다.
---
## Quality Dimensions
### Accuracy
사실과 일치하는가.
---
### Completeness
필요한 정보가 모두 포함되어 있는가.
---
### Consistency
다른 문서와 용어 및 정책이 일치하는가.
---
### Traceability
모든 결정을 추적할 수 있는가.
---
### Maintainability
수정이 쉬운 구조인가.
---
### AI Readability
AI가 별도의 설명 없이도 이해할 수 있는가.
---
### Human Readability
사람이 빠르게 핵심을 파악할 수 있는가.
---
## Quality Scoring
각 항목은 1\~5점으로 평가한다.
| 항목 | 기준 |
| --- | --- |
| Accuracy | 사실 일치 |
| Completeness | 정보 충실도 |
| Consistency | 일관성 |
| Traceability | 추적 가능성 |
| Maintainability | 유지보수성 |
| AI Readability | AI 이해도 |
| Human Readability | 사람 이해도 |
총점은 품질 수준을 나타낸다.
### 31\~35점
Project Constitution
### 26\~30점
Excellent
### 20\~25점
Good
### 15\~19점
Needs Improvement
### 14점 이하
Rewrite Required
---
## Definition of Done
문서는 다음 조건을 만족할 때 완료로 간주한다.
- Purpose가 정의되어 있다.
- 관련 ADR이 연결되어 있다.
- Related Documents가 존재한다.
- Owner가 지정되어 있다.
- Revision History가 존재한다.
- Review를 통과하였다.
---
## RoRo Case Study
RoRo는 초기 문서를 AI가 빠르게 작성하는 데 집중하였다.
그러나 시간이 지나면서
중복,
용어 불일치,
철학 충돌이 발생하였다.
이 경험을 통해
'문서의 양보다 품질이 중요하다'는 결론에 도달하였다.
이후 모든 핵심 문서는 품질 기준을 만족한 후에만 Product Bible에 포함하기로 결정하였다.
---
## Architecture Decision
ADR-028
Documentation Quality Model을 프로젝트 표준으로 채택한다.
ADR-029
Definition of Done을 만족하지 않는 문서는 Published 상태가 될 수 없다.
---
## Related Documents
003_Document_Lifecycle.md
004_Versioning_Policy.md
020_Architecture_Decision_Record.md
021_Project_History.md
090_Product_Constitution.md
103_AI_Governance.md
# Chapter 20
# AI-Native Documentation
---
## Principle
RoRo는 AI를 지원하는 문서를 만드는 것이 아니다.
RoRo는 **AI가 기본 사용자(AI-First Consumer)** 인 문서를 만든다.
사람은 문서를 읽는다.
AI는 문서를 이해한다.
좋은 Documentation은
사람에게 읽기 쉽고,
AI에게도 해석 가능해야 한다.
이 두 조건을 동시에 만족해야 한다.
---
## Why AI Changes Documentation
과거 Documentation은
사람을 위한 기록이었다.
AI 시대의 Documentation은
사람과 AI가 함께 사용하는 Knowledge Base이다.
같은 문서를
Product Manager가 읽고,
Designer가 참고하고,
Developer가 구현하며,
AI Agent가 코드를 생성한다.
따라서 Documentation은
더 이상 단순한 설명서가 아니다.
Documentation은 AI의 Context가 된다.
---
## Documentation as Context
AI는 프로젝트를 기억하지 않는다.
AI는 Context를 읽는다.
따라서
Documentation의 품질은
AI의 품질이 된다.
좋은 Context는
좋은 Code를 만든다.
좋은 Design을 만든다.
좋은 Decision을 만든다.
---
## Context over Prompt
RoRo는 Prompt Engineering보다
Context Engineering을 우선한다.
Prompt는 질문이다.
Documentation은 세계(World)이다.
AI는 Prompt보다
Context의 영향을 훨씬 많이 받는다.
따라서
RoRo는 Prompt를 길게 작성하기보다,
Documentation을 충분히 구축하는 것을 우선한다.
---
## Constitution Rules
Rule 20-1
모든 핵심 문서는 AI가 독립적으로 이해할 수 있어야 한다.
Rule 20-2
AI에게 전달하는 Prompt는 가능한 한 짧고,
Context는 Documentation에서 제공한다.
Rule 20-3
Prompt는 재사용 대상이 아니라,
Documentation을 호출하는 인터페이스이다.
---
## RoRo Case Study
RoRo 초기에는
긴 Prompt를 사용하여
PRD,
UI,
API를 생성하였다.
그러나 프로젝트가 커질수록
Prompt의 길이는 증가했고,
일관성은 감소하였다.
이후 프로젝트는
Prompt 중심 접근을 포기하고,
Markdown 기반 Product Knowledge Base를 구축하였다.
Prompt는 짧아졌고,
결과물의 일관성은 크게 향상되었다.
---
## Architecture Decision
ADR-030
RoRo는 Prompt Engineering보다
Context Engineering을 우선한다.
ADR-031
Markdown Documentation을 AI Context의 공식 원본으로 채택한다.
---
# Chapter 21
# Knowledge Preservation
---
## Principle
프로젝트는 기능을 잃는 것이 아니라
지식을 잃으며 실패한다.
RoRo는
모든 중요한 지식을
보존(Preservation)의 대상으로 정의한다.
---
## What Must Be Preserved
다음 항목은 영구 보존 대상이다.
- Product Vision
- Product Philosophy
- Architecture Decisions
- Domain Model
- Naming Decisions
- UX Principles
- AI Policies
- Lessons Learned
- Rejected Ideas
- Failure Cases
- Research Results
삭제하지 않는다.
필요하지 않더라도
역사로 남긴다.
---
## Why Preservation Matters
프로젝트는 반복한다.
같은 질문을
몇 달 뒤 다시 하게 된다.
왜 Moment를 선택했는가?
왜 Story인가?
왜 Family MVP인가?
왜 Markdown인가?
이 질문에
사람의 기억으로 답해서는 안 된다.
Documentation으로 답해야 한다.
---
## Preservation Levels
### Permanent
절대 삭제하지 않는다.
예)
Vision
ADR
Constitution
---
### Historical
더 이상 사용하지 않지만
역사적 가치가 있다.
예)
Rejected Architecture
Old Branding
Prototype
---
### Temporary
운영 과정에서만 필요한 정보이다.
예)
Meeting Notes
Daily Tasks
Scratch Notes
---
## Constitution Rules
Rule 21-1
모든 ADR은 Permanent이다.
Rule 21-2
Rejected Option은 Historical로 보존한다.
Rule 21-3
Temporary 문서는 공식 Product Knowledge에 포함하지 않는다.
---
## RoRo Case Study
브랜드 검토 과정에서
Replay,
KERO,
EO,
MyMoment,
RoRo 등 다양한 후보를 비교하였다.
최종적으로 RoRo를 선택했지만,
기각된 이름 역시 삭제하지 않았다.
이 기록은 향후 브랜딩 재검토 시
중요한 의사결정 근거가 된다.
---
## Architecture Decision
ADR-032
Knowledge Preservation Policy를 프로젝트 표준으로 채택한다.
ADR-033
Rejected Knowledge도 Historical Asset으로 관리한다.
---
# Chapter 22
# Documentation as Product DNA
---
## Principle
코드는 제품을 실행한다.
Documentation은 제품을 정의한다.
RoRo는 Documentation을
Product DNA라고 정의한다.
DNA는 생명체의 구조와 특성을 결정한다.
Documentation 역시
제품의 구조와 철학을 결정한다.
---
## Product DNA
RoRo Product DNA는 다음 요소로 구성된다.
- Vision
- Philosophy
- Constitution
- Domain Language
- Product Model
- User Experience
- AI Principles
- Architecture
- Decision History
이 요소가 바뀌면
같은 코드라도
다른 제품이 된다.
---
## DNA Inheritance
새로운 팀원이 합류하면
코드를 먼저 읽지 않는다.
Product DNA를 먼저 이해한다.
새로운 AI Agent도 마찬가지다.
Prompt를 먼저 받지 않는다.
Documentation을 먼저 읽는다.
RoRo는 이를
DNA Inheritance라고 정의한다.
---
## Product Evolution
DNA는 변할 수 있다.
그러나 돌연변이(Mutation)는
통제되어야 한다.
RoRo에서는
Product DNA의 변경은
다음 절차를 따른다.
1. Proposal
2. Discussion
3. ADR
4. Review
5. Approval
6. Documentation Update
7. Implementation
순서를 바꾸지 않는다.
---
## Constitution Rules
Rule 22-1
모든 Feature는 Product DNA와 연결되어야 한다.
Rule 22-2
Documentation 없는 Feature는 존재하지 않는다.
Rule 22-3
Product DNA 변경은 ADR 승인 없이 진행할 수 없다.
---
## RoRo Case Study
RoRo는 여행 기록 앱으로 시작했지만,
프로젝트가 진행되면서
'기억을 기록하는 제품'으로 철학이 발전하였다.
이에 따라
도메인 모델,
AI 역할,
Story 생성,
Moment 구조,
Privacy 정책이 모두 재정의되었다.
이 변화는
코드보다 먼저
Documentation에서 이루어졌다.
Documentation이
제품 진화의 출발점이었기 때문이다.
---
## Architecture Decision
ADR-034
Documentation을 Product DNA로 정의한다.
ADR-035
모든 핵심 Feature는 Product DNA와 연결되어야 한다.
---
## Related Documents
002_Document_Structure.md
020_Architecture_Decision_Record.md
021_Project_History.md
090_Product_Philosophy.md
091_Memory_First.md
103_AI_Governance.md
104_Context_Engineering.md
# Chapter 23
# Documentation Longevity
---
## Principle
좋은 Documentation은
오늘을 위해 작성되지 않는다.
10년 후에도 이해될 수 있도록 작성된다.
RoRo는 Documentation을
단기 프로젝트 산출물이 아니라
장기 지식 자산(Long-term Knowledge Asset)으로 정의한다.
---
## Documentation Outlives Technology
프로그래밍 언어는 바뀐다.
Framework도 바뀐다.
Cloud Provider도 바뀐다.
AI도 바뀐다.
그러나 Documentation은
기술보다 오래 살아야 한다.
RoRo는 특정 Vendor나 Tool에
Documentation이 종속되는 것을 금지한다.
---
## Technology Independence
Documentation은 다음 조건을 만족해야 한다.
- 특정 IDE에 종속되지 않는다.
- 특정 AI에 종속되지 않는다.
- 특정 Cloud에 종속되지 않는다.
- 특정 Database에 종속되지 않는다.
- 특정 Framework에 종속되지 않는다.
문서는 기술보다 높은 계층에 존재한다.
---
## Why Markdown
RoRo가 Markdown을 선택한 이유는
단순히 편리하기 때문이 아니다.
Markdown은
- 개방형(Open)
- 사람이 읽기 쉽다.
- AI가 이해하기 쉽다.
- Git으로 버전 관리가 가능하다.
- Tool Migration 비용이 낮다.
프로젝트는
도구를 선택한 것이 아니라
지속 가능성을 선택한 것이다.
---
## RoRo Case Study
RoRo 프로젝트는
Notion,
Figma,
GitHub,
ChatGPT를 함께 사용하였다.
프로젝트를 진행하면서
도구마다 기능과 제약이 달랐다.
그러나 Markdown Repository는
모든 도구를 연결하는
가장 안정적인 공통 계층으로 유지되었다.
이 경험을 통해
Markdown은 단순한 파일 형식이 아니라
프로젝트의 장기 보존 전략으로 채택되었다.
---
## Constitution Rules
Rule 23-1
Documentation은 Vendor Independent 해야 한다.
Rule 23-2
모든 핵심 지식은 Markdown으로 보존한다.
Rule 23-3
도구는 교체 가능해야 한다.
---
## Architecture Decision
ADR-036
Vendor Independent Documentation을 채택한다.
ADR-037
Markdown을 장기 보존 포맷으로 채택한다.
---
# Chapter 24
# Documentation Scalability
---
## Principle
좋은 Documentation은
프로젝트가 성장해도
함께 성장할 수 있어야 한다.
문서가 프로젝트의 규모를 제한해서는 안 된다.
---
## Scaling Dimensions
RoRo는 Documentation의 확장을
다음 여섯 가지 관점에서 정의한다.
### Knowledge Scale
기능이 증가해도
지식 구조는 유지되어야 한다.
---
### Team Scale
팀원이 늘어나도
동일한 규칙을 적용할 수 있어야 한다.
---
### AI Scale
새로운 AI Agent가 추가되어도
동일한 Context를 사용할 수 있어야 한다.
---
### Product Scale
MVP에서 정식 서비스까지
동일한 철학을 유지해야 한다.
---
### Time Scale
5년, 10년 후에도
프로젝트의 의사결정을 추적할 수 있어야 한다.
---
### Repository Scale
문서 수가
10개에서 1,000개로 증가해도
탐색성과 유지보수성이 유지되어야 한다.
---
## Hierarchical Organization
RoRo는 계층 구조를 사용한다.
Book
↓
Domain
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
이 구조는
문서 수가 증가해도
프로젝트를 이해할 수 있도록 설계되었다.
---
## Constitution Rules
Rule 24-1
문서는 계층 구조를 따른다.
Rule 24-2
새로운 문서는 기존 계층을 위반할 수 없다.
Rule 24-3
확장을 위해 기존 철학을 훼손하지 않는다.
---
## Architecture Decision
ADR-038
Hierarchical Documentation Architecture를 채택한다.
ADR-039
Documentation Scalability를 핵심 품질 속성으로 정의한다.
---
# Chapter 25
# Documentation Legacy
---
## Principle
Documentation의 최종 목적은
현재 프로젝트를 지원하는 것이 아니다.
미래 프로젝트에
지식을 전달하는 것이다.
---
## Legacy
RoRo Documentation은
코드보다 오래 살아야 한다.
애플리케이션보다 오래 살아야 한다.
회사보다 오래 살아야 한다.
Documentation은
프로젝트의 유산(Legacy)이다.
---
## Legacy Includes
RoRo는 다음을
Legacy Asset으로 정의한다.
- Product Philosophy
- Architecture
- Domain Language
- Design Principles
- ADR
- Lessons Learned
- Historical Decisions
이들은 프로젝트 종료 후에도
삭제하지 않는다.
---
## Success Criteria
RoRo Documentation의 성공 기준은 다음과 같다.
10년 후
새로운 팀이
기존 개발자를 만나지 않고도
동일한 제품을
동일한 철학으로
재구성할 수 있어야 한다.
이것이 Documentation의 궁극적인 목적이다.
---
## Final Constitution Rules
Rule 25-1
Documentation은 제품보다 오래 살아야 한다.
Rule 25-2
Documentation은 프로젝트의 집단 기억이다.
Rule 25-3
Documentation은 미래 세대에게 전달되는 유산이다.
---
## Architecture Decision
ADR-040
Documentation Legacy를 프로젝트의 장기 전략으로 채택한다.
ADR-041
Knowledge Transfer를 Documentation의 최종 목표로 정의한다.
---
## Related Documents
002_Document_Structure.md
003_Document_Lifecycle.md
020_Architecture_Decision_Record.md
021_Project_History.md
022_Lessons_Learned.md
104_Context_Engineering.md
# Chapter 26
# Normative Definitions
---
## Purpose
RoRo Documentation은
모든 문서에서 동일한 의미를 사용하기 위해
공식 용어를 정의한다.
다른 문서는
이 장의 정의를 변경할 수 없다.
정의의 변경은
ADR 승인 후에만 가능하다.
---
## Documentation
Documentation은
프로젝트의 지식을
사람과 AI가
동일하게 이해할 수 있도록
구조화한 영구 기록이다.
Documentation은
메모가 아니다.
회의록이 아니다.
설명서가 아니다.
Documentation은
Product Knowledge이다.
---
## Knowledge
Knowledge는
반복적으로 활용 가능한 정보이다.
일회성 정보는
Knowledge가 아니다.
---
## Context
Context는
AI 또는 사람이
올바른 결정을 내리기 위해
필요한 모든 정보의 집합이다.
Prompt는
Context의 일부일 뿐이다.
---
## Source of Truth
Source of Truth는
특정 정보에 대한
유일한 공식 원본이다.
같은 정보는
둘 이상의 Source of Truth를
가질 수 없다.
---
## Rule
Rule은
반드시 지켜야 하는 규칙이다.
Rule은
권장사항이 아니다.
Rule을 위반하면
Documentation Error로 정의한다.
---
## Guideline
Guideline은
권장되는 방법이다.
예외가 허용된다.
---
## Standard
Standard는
프로젝트 전체가
동일하게 따라야 하는 규격이다.
---
## ADR
Architecture Decision Record
프로젝트의 중요한 의사결정을
영구적으로 보존하는 문서이다.
---
## Architecture
Architecture는
컴포넌트가 아니라
의사결정의 구조이다.
---
## Product DNA
Product DNA는
제품을 다른 제품과 구별하는
모든 철학,
규칙,
구조,
언어,
의사결정의 집합이다.
---
# Chapter 27
# Normative Language
---
## Purpose
모든 문서는
같은 강도의 표현을 사용해야 한다.
"권장"
"필수"
"가능"
이 섞이면
문서는 모호해진다.
---
## MUST
반드시 수행해야 한다.
예외는 없다.
예)
모든 ADR은
Revision History를 MUST 포함한다.
---
## MUST NOT
절대 수행해서는 안 된다.
예)
동일한 정의를
두 문서에서 관리해서는 안 된다.
---
## SHOULD
특별한 이유가 없다면
따라야 한다.
예외는 허용된다.
---
## SHOULD NOT
가능하면 피해야 한다.
---
## MAY
선택사항이다.
프로젝트 상황에 따라
사용한다.
---
## Examples
MUST
↓
Owner 지정
SHOULD
↓
Diagram 포함
MAY
↓
Illustration 포함
---
## Constitution Rules
Rule 27-1
모든 Rule은
Normative Language를 사용한다.
Rule 27-2
모호한 표현을 금지한다.
예)
가능하면
아마
적당히
충분히
등은 사용하지 않는다.
---
# Chapter 28
# Constitution Summary
---
## RoRo Documentation Constitution
RoRo Documentation은
다음 원칙을 따른다.
---
Documentation is Product.
---
Documentation comes before Implementation.
---
Documentation is Organizational Memory.
---
Documentation is Product DNA.
---
Markdown is the Source of Truth.
---
Reference over Copy.
---
Context over Prompt.
---
History is never deleted.
---
Decision is preserved forever.
---
AI is a Collaborator.
---
Human has Final Authority.
---
Knowledge must be connected.
---
Every Fact has One Home.
---
Documentation outlives Technology.
---
Documentation exists for the next generation.
---
## Final Declaration
우리는
코드를 남기는 프로젝트가 아니다.
우리는
지식을 남기는 프로젝트이다.
우리는
문서를 작성하는 것이 아니다.
우리는
제품의 DNA를 구축한다.
RoRo Documentation은
현재를 위한 문서가 아니라
미래를 위한 기억이다.
---
## Final Architecture Decisions
ADR-042
Normative Definitions를
공식 용어집으로 채택한다.
ADR-043
Normative Language를
프로젝트 표준으로 채택한다.
ADR-044
001_Document_Philosophy.md를
RoRo Documentation Constitution으로 승인한다.
---
## End of Document
