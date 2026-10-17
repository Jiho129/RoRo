<!-- Source: Notion page [📝 PRD-001 Trip Creation](https://app.notion.com/p/3a7dff1c1f7481c3815be40469d456cf?pvs=204). Page ID: 3a7dff1c-1f74-81c3-815b-e40469d456cf. Path: RoRo Project / 02 Product / 📄 PRD Repository. Last edited: 2026-07-24T00:01:55.242Z. -->

# 📝 PRD-001 Trip Creation

## 1. Overview
### Feature Name
Trip Creation
### Objective
사용자가 여행 기록의 시작점이 되는 Trip을 쉽고 빠르게 생성할 수 있도록 한다.
RoRo의 모든 Memory 구조는 Trip을 기반으로 관리되며, 이후 Moment, Photo, AI Diary 생성의 기준 데이터가 된다.
---
## 2. User Story
As a family traveler,
I want to create a trip before traveling,
so that I can collect and organize my travel moments in one place.
---
## 3. User Scenario
1. 사용자가 RoRo 실행
2. 신규 Trip 생성 선택
3. 여행 기본 정보 입력
	- Trip Name
	- Destination
	- Start Date
	- End Date
	- Travelers
4. Trip 생성 완료
5. Timeline 화면으로 이동
---
## 4. Functional Requirements
### FR-001 Trip Name
- 사용자는 여행명을 입력할 수 있다.
- 예: 2026 LA Family Trip
### FR-002 Destination
- 여행 목적지를 입력할 수 있다.
- Multiple destination 지원 고려
### FR-003 Travel Date
- 시작일과 종료일을 설정한다.
### FR-004 Travelers
- 함께 여행한 가족 구성원을 등록할 수 있다.
---
## 5. Data Model
Trip Object
| Field | Description |
| --- | --- |
| trip_id | Unique Identifier |
| title | Trip Name |
| destination | Location |
| start_date | Start Date |
| end_date | End Date |
| members | Travelers |
| created_at | Creation Time |
---
## 6. UX Consideration
Principle:
"Create a trip in less than 30 seconds"
필수 입력 최소화.
AI가 이후 사진, 위치 데이터를 활용하여 상세 정보를 보완한다.
---
## 7. MVP Acceptance Criteria
✅ 사용자가 신규 Trip 생성 가능
✅ 여행 날짜 저장 가능
✅ 여행 장소 저장 가능
✅ 생성된 Trip에서 Moment 기록 가능
---
## 8. Future Enhancement
- Calendar Import
- Flight / Hotel Auto Import
- AI Trip Setup Assistant
