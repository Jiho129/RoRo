<!-- Source: Notion page [📗 User Flow Specification v1.0](https://app.notion.com/p/3a5dff1c1f7481d39438da906f82a345?pvs=204). Page ID: 3a5dff1c-1f74-81d3-9438-da906f82a345. Path: RoRo Project / 🏠 RoRo OS. Last edited: 2026-07-22T15:24:55.830Z. -->

# User Flow Specification v1.0
## Purpose
RoRo MVP의 주요 사용자 행동을 정의하고 Figma Prototype 및 Engineering Requirement의 기준으로 사용한다.
---
# 01. Trip Creation Flow
## Goal
사용자가 새로운 여행을 생성한다.
## Flow
Landing → Create Trip → Basic Info → Members → Schedule Import → Trip Dashboard
## Input
- Trip Name
- Destination
- Travel Date
- Members
## Output
Trip Object 생성
---
# 02. Schedule Import Flow
## Goal
여행 전 계획을 RoRo에 등록한다.
## Flow
Trip Dashboard → Add Schedule → Manual Input / Calendar Import → Timeline 생성
## MVP Decision
Google Calendar 연동은 제외한다.
Reason:
개발 복잡도 대비 초기 가치가 낮음.
---
# 03. Moment Creation Flow
## Goal
여행 중 순간을 최소 행동으로 기록한다.
## Flow
Trip → + Button → Select Photo → Add Location → AI Analyze → Save Moment
## UX Rule
사용자는 사진만 선택해도 저장 가능해야 한다.
---
# 04. AI Diary Generation Flow
## Goal
하루 여행 기록을 자동 생성한다.
## Flow
Moments Collection → AI Processing → Draft Diary → User Edit → Publish
## AI Principle
AI는 작성자가 아니라 편집 보조자 역할이다.
---
# 05. Expense Flow
## Goal
여행 비용을 간단하게 기록한다.
## Flow
Expense → Add Cost → Category → Amount → Save
## MVP Scope
- 쇼핑
- 식사
- 교통
- 입장권
- 숙박
---
# 06. Trip Summary Flow
## Goal
여행 종료 후 전체 경험을 제공한다.
## Flow
Trip End Detection → Summary Generation → Diary Archive
---
# User Flow List (MVP)
1. Onboarding
2. Login
3. Create Trip
4. Invite Member
5. Add Schedule
6. View Timeline
7. Create Moment
8. Edit Moment
9. AI Story Generate
10. Create Diary
11. Edit Diary
12. Add Expense
13. View Map
14. Generate Summary
15. Share Trip
---
# Engineering Reference
각 Flow는 다음 개발 항목과 연결된다.
- Screen
- API
- Database Entity
- Analytics Event
- Error Case
