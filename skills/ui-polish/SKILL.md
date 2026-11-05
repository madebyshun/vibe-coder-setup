---
name: ui-polish
description: Polish a page or component so it looks designed by a human, not generated. Use when the user says the UI looks generic, "AI-made", ugly, unpolished, or asks to make it look better.
---

# UI Polish

Read the brand section of CLAUDE.md first. Then go through the page in this order and fix what you find:

1. **Hierarchy** — one clear focal point per screen. The most important thing is the biggest/boldest. Shrink or mute everything competing with it.
2. **Spacing** — snap every margin/padding to the 8px grid. Increase whitespace between sections (usually 2× what it is now). Group related items tighter than unrelated ones.
3. **Typography** — max 2 weights and 3–4 sizes per screen. Headings: tight line-height (1.0–1.1) and slight negative letter-spacing. Body: 1.5 line-height, max ~65 characters per line.
4. **Color** — use the brand palette only. Primary color for ONE action per screen. Replace pure #000/#fff with the brand's dark/light.
5. **Remove AI tells** — default drop shadows, purple-blue gradients, emoji as icons, centered-everything layouts, identical card grids, "Unlock the power of…" copy.
6. **States** — hover, focus-visible, active, disabled, empty and loading states.
7. **Mobile** — check at 375px. Nothing overflows, tap targets ≥ 44px.

Finish by listing the changes in plain language (before → after) so the user learns the reasoning.
