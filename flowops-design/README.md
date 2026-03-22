# FlowOps Figma Assets

This folder contains import-ready design assets for the `FlowOps` SaaS portfolio project.

Files:
- `design-tokens.json`: color, typography, spacing, radius, and component token definitions
- `figma-mcp-prompt.md`: a structured build prompt you can reuse when your Figma MCP surface is available
- `screens/*.svg`: six styled desktop screens that can be imported directly into Figma

Suggested Figma workflow:
1. Create a new Figma file named `FlowOps`.
2. Drag the SVG files from `screens/` into Figma.
3. Use `design-tokens.json` as the source of truth for color styles, text styles, spacing, and radius values.
4. Rebuild reusable components from the imported screens:
   - Top navigation
   - Sidebar
   - KPI card
   - Filter bar
   - Table row
   - Status badge
   - Comment item
   - Activity timeline item
5. Turn each imported screen into a frame and connect flows if you want a clickable prototype.

Screen list:
- `01-login.svg`
- `02-dashboard.svg`
- `03-requests.svg`
- `04-request-detail.svg`
- `05-request-new.svg`
- `06-members.svg`

Design direction:
- Concept: `Quiet Command Center`
- Tone: calm, operational, high-trust, B2B SaaS
- Visual strategy: warm canvas, deep ink navigation, teal + lime accents, data-first layout

Notes:
- The current Codex thread does not expose a direct Figma MCP tool, so these assets were generated locally for import.
- All screens are desktop-first at `1440x1024`.
- Korean labels are included to match the intended portfolio presentation.
