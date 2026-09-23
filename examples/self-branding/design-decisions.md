# Design decisions

## Current state

- **Selected direction:** B / Second draft, explicitly chosen by Pavel.
- **Mode:** refinement. Preserve the overlapping frames and central square.
- **Current proposal:** balanced primary geometry and a dedicated 16 px optical variant in `02-refinement/`.
- **Awaiting review:** refined geometry and optical variant. Color and typography remain open.
- **Next step:** review this refinement, then explore color and the name lockup.

## 2026-09-23 — B selected and refined

- **User feedback:** “lets go with B”.
- **Preserved:** the chosen overlapping-frame concept; Round 1 source artwork and comparison board.
- **Agent changes:** equalized the primary's two frame gaps to 20 units, centered the inner square, and retained uniform 28-unit strokes. Added a whole-pixel version for exactly 16 px after observing softness in the scaled primary.
- **Artifacts:** `02-refinement/refinement-board.svg` and `.png`; `pixel-checks.svg` and `.png`; primary and optical SVGs in dark ink and white; raster exports under `02-refinement/exports/`.
- **Verification:** actual 16, 24, 32, and 64 px exports inspected on white and dark backgrounds at native size and enlarged pixels. The 16 px optical export uses only two colors, confirming whole-pixel rendering in this renderer. Detailed findings are in `02-refinement/verification.md`.
- **Approval boundary:** B is selected; the refined geometry and optical version are proposals. No final brand approval has been claimed.
- **Figma:** no change; the process file remains empty following the reported MCP limit. Round 2 was made locally.
- **Active skill icon:** still the supplied pencil; replace only after review of the new mark.

## 2026-09-23 — Initial exploration

- **User request:** collaboratively design a logo for the skill, use Figma, and document the process with images in the README.
- **Mode:** exploration.
- **Brief assumptions:** craft-focused geometric identity; thoughtful, approachable, precise; skill icon and repository header. These are agent proposals, not approved preferences.
- **Selected concept:** none.
- **Approved visual elements:** none. The existing `assets/icon.svg` remains the active skill icon.
- **Explored directions:** A / Return stroke; B / Second draft; C / Iterative i.
- **Agent recommendation:** B as a starting point for refinement. Awaiting user response.
- **Rejected directions:** none.
- **Artifacts:** `01-exploration/contact-sheet.svg`, `01-exploration/contact-sheet.png`, and the three individual SVGs in that folder.
- **Figma file:** https://www.figma.com/design/jIboEmJ2p9sDszWPKTFtDo — created, currently empty because the first canvas call hit the Starter-plan MCP limit.
- **Verification:** comparison board rendered and visually inspected; XML and local links checked. No small-size, reverse, or final-delivery checks yet.
- **Open questions:** preferred personality and concept direction; whether to preserve or combine any elements.
- **Next step:** collect feedback, preserve Round 1, then refine the chosen direction. Move artwork into Figma when access is available.
