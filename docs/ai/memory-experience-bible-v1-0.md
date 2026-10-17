<!-- Source: Notion page [📗 Memory Experience Bible v1.0](https://app.notion.com/p/3a5dff1c1f748101838bea12d8cf1d82?pvs=204). Page ID: 3a5dff1c-1f74-8101-838b-ea12d8cf1d82. Path: RoRo Project / 06 AI. Last edited: 2026-07-22T15:44:47.097Z. -->

# RoRo Memory Experience Bible v1.0
## Document Purpose
RoRo의 핵심 경험 단위인 Moment와 Memory 구조를 정의한다.
본 문서는 UX, AI, Engineering 설계의 기준 문서이다.
---
# 1. Memory Philosophy
RoRo는 사진을 저장하는 서비스가 아니다.
사용자가 경험한 순간의 맥락(Context)을 보존하고, 시간이 지난 후 다시 경험할 수 있도록 만드는 Memory OS이다.
기존 구조:
Photo → Album
RoRo 구조:
Experience → Moment → Memory → Story → Archive
---
# 2. Core Data Unit: Moment
Moment는 RoRo의 가장 작은 경험 데이터 단위이다.
## Moment Definition
Moment = 여행 중 의미 있는 하나의 경험
## Moment Components
- Photo
- Location
- Time
- People
- Emotion
- Activity
- User Note
- AI Interpretation
---
# 3. Moment Lifecycle
Capture
↓
Analyze
↓
Enrich
↓
Confirm
↓
Remember
## Capture
사용자가 사진 또는 기록을 추가한다.
## Analyze
AI가 위치, 시간, 장소, 맥락을 분석한다.
## Enrich
AI가 스토리 후보를 생성한다.
## Confirm
사용자가 수정 및 승인한다.
---
# 4. Memory Model
User
↓
Trip
↓
Day
↓
Moment
↓
Memory
↓
Diary
↓
Archive
---
# 5. AI Story Framework
AI는 창작자가 아니라 Memory Assistant이다.
## Input
- Photo
- Location
- Schedule
- Time
- User Context
## Output
- Title
- Short Description
- Emotional Summary
- Suggested Diary Text
---
# 6. Diary Experience
Daily Diary는 Moment Collection을 기반으로 생성한다.
Flow:
Moment Collection
→ AI Draft
→ User Edit
→ Final Memory
---
# 7. Highlight Experience
Future Feature
여러 Moment를 연결하여 짧은 여행 하이라이트를 생성한다.
MVP에서는 우선순위 제외.
Reason:
AI Processing Cost와 개발 복잡도 대비 초기 핵심 가치가 낮음.
---
# 8. Long Term Vision
RoRo의 최종 목표는 개인 Life Archive이다.
Travel Memory
→ Family Memory
→ Life Story
---
# Product Decision
RoRo의 핵심 경쟁력은 사진 저장 기술이 아니라 Context를 가진 Memory 생성 경험이다.
