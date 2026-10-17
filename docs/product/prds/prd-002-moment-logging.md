<!-- Source: Notion page [📝 📝 PRD-002 Moment Logging](https://app.notion.com/p/3a7dff1c1f748145be97c4a6e285bb55?pvs=204). Page ID: 3a7dff1c-1f74-8145-be97-c4a6e285bb55. Path: RoRo Project / 02 Product / 📄 PRD Repository. Last edited: 2026-07-24T00:04:10.020Z. -->

# 📝 📝 PRD-002 Moment Logging

## 1. Overview
### Feature Name
Moment Logging
### Objective
RoRo의 핵심 데이터 단위인 Moment를 생성하여 여행 중 발생하는 의미 있는 순간을 기록한다.
Moment는 단순 사진 저장이 아니라 사진, 장소, 시간, 사람, 활동, 감정이 연결된 기억 단위이다.
## 2. User Story
As a family traveler,
I want to capture meaningful moments easily,
so that I can remember my journey without spending much effort recording.
## 3. User Scenario
1. RoRo 실행
2. Moment 생성 선택
3. 사진 선택
4. 위치/시간 자동 입력
5. 메모 추가
6. Moment 저장
7. Timeline 반영
## 4. Functional Requirements
- 사진 기반 Moment 생성
- GPS 및 Timestamp 자동 수집
- 사용자 메모 입력
- AI Diary 생성 데이터 활용
## 5. Data Model
| Field | Description |
| --- | --- |
| moment_id | Unique ID |
| trip_id | Parent Trip |
| photos | Attached Images |
| location | GPS Location |
| timestamp | Created Time |
| note | User Memo |
| AI_summary | AI Generated Story |
## 6. MVP Acceptance Criteria
✅ Moment 생성 가능
✅ Timeline 표시
✅ Trip 연결
✅ AI Diary 활용 가능
