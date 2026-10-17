<!-- Source: Notion page [📝 📝 PRD-003 Photo Upload](https://app.notion.com/p/3a7dff1c1f7481a9b258eec83f84a85b?pvs=204). Page ID: 3a7dff1c-1f74-81a9-b258-eec83f84a85b. Path: RoRo Project / 02 Product / 📄 PRD Repository. Last edited: 2026-07-24T00:04:10.020Z. -->

# 📝 📝 PRD-003 Photo Upload

## 1. Overview
여행 중 촬영한 사진을 RoRo Memory Archive로 가져오는 기능이다.
## 2. Product Principle
Upload should not interrupt travel.
## 3. Functional Requirements
- Gallery Selection
- AI Recommended Photo Selection
- Upload Before Approval
- Privacy Control
## 4. Data Model
| Field | Description |
| --- | --- |
| photo_id | Unique ID |
| moment_id | Related Moment |
| file_url | Storage Path |
| metadata | EXIF Data |
| AI_tags | Recognition Result |
## 5. MVP Acceptance Criteria
✅ 사용자 사진 선택
✅ Moment 연결
✅ AI 분석 활용
