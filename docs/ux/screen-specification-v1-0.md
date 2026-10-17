<!-- Source: Notion page [📘 Screen Specification v1.0](https://app.notion.com/p/3a5dff1c1f74819caef1cdbaa395c390?pvs=204). Page ID: 3a5dff1c-1f74-819c-aef1-cdbaa395c390. Path: RoRo Project / 03 UX. Last edited: 2026-07-22T16:01:46.444Z. -->

# RoRo Screen Specification v1.0
## Document Purpose
Figma High Fidelity Design과 Engineering 구현을 연결하는 화면 정의 문서.
각 화면은 Purpose, Component, Interaction, State, Data Requirement 기준으로 관리한다.
---
# Screen Inventory
## Core MVP Screens
01 Splash
02 Login
03 Home Dashboard
04 Trip List
05 Create Trip
06 Trip Dashboard
07 Daily Timeline
08 Add Moment
09 Moment Detail
10 AI Diary
11 Expense
12 Map
13 Trip Summary
14 Settings
---
# SCR-001 Home Dashboard
## Purpose
사용자가 현재 여행 상태와 주요 Moment를 빠르게 확인한다.
## Entry Point
App Launch
## Components
- Current Trip Card
- Today's Schedule
- Recent Moments
- Quick Action (+)
## Interaction
Trip Card Tap → Trip Dashboard
- Button → Add Moment
## State
Empty:
No active trip
Loading:
Loading travel context
Error:
Retry available
## Data
User
Trip
Moment
## Analytics
home_view
trip_card_click
add_moment_click
---
# SCR-002 Trip Dashboard
## Purpose
여행 전체 정보를 관리하는 Main Hub
## Components
- Trip Header
- Date Selector
- Timeline Preview
- Map Preview
- Expense Summary
## Interaction
Timeline → Daily Timeline
Map → Map View
Expense → Expense Detail
---
# SCR-003 Add Moment
## Purpose
여행 중 순간을 최소 행동으로 기록
## Components
- Photo Selector
- Location
- Note
- AI Processing Status
## UX Rule
사진만 선택해도 저장 가능해야 한다.
## Flow
Photo Select
→ AI Analyze
→ Moment Created
---
# SCR-004 AI Diary
## Purpose
Moment 기반 여행 기록 생성
## Components
- AI Draft
- Edit Area
- Approve Button
## Rule
AI는 초안을 생성하고 사용자가 최종 결정한다.
---
# Engineering Reference
Each Screen connects to:
- API
- Database Entity
- Analytics Event
- Error Case
- Permission Rule
