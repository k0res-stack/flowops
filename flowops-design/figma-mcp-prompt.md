# FlowOps Figma Build Prompt

Use this prompt when your Figma MCP surface is available and you want to reconstruct the screens natively in Figma instead of importing the SVGs.

> **Note:** This file is kept in sync with `design-tokens.json`. Always refer to the JSON as the single source of truth for token values.

---

Create a desktop-first B2B SaaS interface called `FlowOps`.

Visual direction:
- Concept: `Quiet Command Center`
- Mood: calm, operational, premium, trustworthy
- Background: warm light canvas
- Navigation: deep ink navy
- Accent colors: teal primary and lime highlight
- Avoid generic blue startup visuals and avoid purple

Canvas:
- Desktop width: `1440`
- Desktop height: `1024`
- Sidebar width: `240`
- Top bar height: `76`
- Card radius: `14`
- Card padding: `24`
- Section gaps: `24`

Fonts:
- Main Korean UI: `SUIT Variable, Pretendard, Apple SD Gothic Neo, sans-serif`
- KPI and numeric data: `Space Grotesk, SUIT Variable, sans-serif`

Colors:
- Ink 900: `#132033`
- Ink 700: `#304156`
- Ink 500: `#5E6B7B`
- Canvas: `#F5F3EE`
- Surface: `#FFFCF7`
- Border: `#DDD7CC`
- Muted: `#E9E4D8`
- Primary: `#0EA5A4`
- Primary Dark: `#0B6E6D`
- Lime Accent: `#C7F36B`
- Warning: `#F4A261`
- Warning Dark: `#A35A00`
- Warning Bg: `#FCE6CC`
- Danger: `#E76F51`
- Success: `#2A9D8F`
- Success Dark: `#1F7A5C`
- Success Bg: `#DDF3EA`
- Progress Bg: `#D9F3F1`

Status badge colors (background / foreground pairs):
- 접수: bg `#E9E4D8` / text `#5E5A52`
- 진행중: bg `#D9F3F1` / text `#0B6E6D`
- 보류: bg `#FCE6CC` / text `#A35A00`
- 완료: bg `#DDF3EA` / text `#1F7A5C`

Typography scale:
- Page title: 28px / 700 / line-height 1.3
- Section title: 20px / 700 / line-height 1.35
- Body: 15px / 500 / line-height 1.5
- Caption: 13px / 500 / line-height 1.45
- KPI numeric: 32px / 700 / line-height 1.15 (Space Grotesk)

Spacing scale:
- xs: `8`
- sm: `12`
- md: `16`
- lg: `24`
- xl: `32`

Component specs:
- Button height: `44px` / radius: `12px`
- Input height: `44px` / radius: `12px` / border: `#DDD7CC`
- Card: bg `#FFFCF7` / border `#DDD7CC` / radius `14px`
- Table row height: `56px` / divider `#EEE7DB`

Required screens:
1. Login
2. Dashboard
3. Request List
4. Request Detail
5. New Request
6. Member Management

Required components:
- Top navigation with search, notifications, organization switcher, profile
- Left sidebar with icons and menu labels
- KPI cards
- Filter bar with search and dropdown filters
- Data table with status badges
- Status badges for `접수`, `진행중`, `보류`, `완료`
- Request detail cards
- Comment list
- Activity timeline
- Buttons: primary, secondary, ghost
- Text input / dropdown input

Content:
- Use Korean UI labels
- The app manages incoming requests, assignments, status changes, and team operations
- Roles: 관리자, 매니저, 멤버

Layout guidance:
- The dashboard should feel dense but calm
- Use clear grouping and restrained shadows
- Emphasize data readability over decorative effects
- Use teal and lime only as accents, not as full backgrounds
- Use Primary Dark (`#0B6E6D`) for hover and focus states on primary elements
- Use Ink 500 (`#5E6B7B`) for secondary/muted text

Screen copy:
- Dashboard title: `운영 현황을 한눈에 확인하세요`
- Dashboard subtitle: `오늘 들어온 요청부터 처리 완료율까지 팀의 업무 흐름을 실시간으로 확인할 수 있습니다.`
- Request list title: `요청 관리`
- Request detail title: `요청 상세`
- New request title: `새 요청 등록`
- Members title: `멤버 관리`

Expected output:
- Create all six frames
- Build reusable components first where practical
- Keep the interface production-like, not wireframe-like
