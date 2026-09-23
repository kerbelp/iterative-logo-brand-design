# Design decisions

## Current state

- **Selected direction:** B / Second draft, explicitly chosen by Pavel; refined primary geometry approved.
- **Selected palette:** B / Cobalt & chalk, explicitly chosen by Pavel.
- **Delivered identity:** approved mark and palette with the shown Arial name lockup, outlined light/dark headers, primary and 16 px optical variants, monochrome assets, and PNG exports.
- **Repository integration:** the new chalk-backed tile replaces the pencil icon, the metadata uses cobalt as its brand accent, and the README shows the result and process.
- **Preserved:** all three prior rounds and the original pencil icon. The approved primary geometry has not changed.
- **Documentation:** process captures and captions are indexed in `process-captures.md` for the README and a possible blog post. No blog publication has been requested.
- **Verification:** named digital sizes, light/dark exports, outlined lettering, the local browser preview, and the published GitHub README checked. Installed-host rendering and physical print are untested; Figma canvas access remains unavailable.
- **Next step:** optional review of the delivered identity or future Figma import when access is restored. No palette selection remains open.

## 2026-09-23 — Cobalt selected and delivered

- **User feedback:** “Lets go with B”. This selects the Cobalt & chalk palette from Round 3, following approval of the primary geometry.
- **Agent implementation:** retained the shown Arial lockup; converted delivery lettering to vector outlines; kept editable text sources. Prepared primary, optical, light/dark, and monochrome variants and target-size PNGs.
- **Icon placement:** the active skill tile uses cobalt on a fixed chalk background. Both metadata icon slots retain the primary tile; a separate 16 px optical tile is supplied for known-size usage. The original pencil is archived with Round 1.
- **Checks:** approved primary paths preserved; optical exports checked at 16 px and primary exports at 24, 32, and 64 px on both surfaces; fonts outlined; local browser preview captured. Details are in `04-delivery/README.md`.
- **Approval wording:** shape and palette were explicitly selected. The shown typography and documented optical usage rule were carried through as implementation choices; no additional user approval was invented.
- **Artifacts:** `assets/brand/`, `assets/icon.svg`, `assets/icon-16.svg`, and `04-delivery/`. The README now presents the selected identity and concise process.
- **Publication capture:** `04-delivery/github-readme.jpg` shows the live README after commit `a56e9eb`. Its theme-aware picture loads the outlined dark header in a dark browser theme; the light header is the default.

## 2026-09-23 — Color and lockup comparison

- **User request:** continue after approving the refined primary.
- **Preserved:** all approved primary mark paths; identical geometry, scale, and name lockup across the comparison.
- **Proposals:** A / Vermilion & paper; B / Cobalt & chalk; C / Pine & mist. Arial Bold and Regular for the two-line name lockup, verified as locally available.
- **Agent recommendation:** A for its warmer character. No color or typography selection has been made by the user.
- **Artifacts:** `03-color/color-studies.svg` and `.png`; six editable light/dark lockup studies; `palettes.json`; browser review page and `browser-color-studies.jpg`.
- **Capture:** actual browser screenshot of the locally rendered study page, saved for the README and possible blog post. It is not a Figma or live GitHub screenshot.
- **Checks:** visual inspection in local render and browser; approved geometry comparison; SVG parsing; local links; measured named color-pair contrast. Live-text font fallback remains a portability limitation until final outlined artwork is prepared.
- **Next decision:** palette and name lockup feedback.

## 2026-09-23 — Refined mark approved; process documentation requested

- **User feedback:** “refined looks good, remember to take screenshots of the process for the final README.md (and maybe blog post)”.
- **Decision:** the refined primary mark is approved. Keep its geometry fixed through color and typography exploration.
- **Documentation:** retain the existing concept, refinement, and pixel-check boards. Save new captures at meaningful stages with captions, source files, approval state, and the decision they illustrate.
- **Publication scope:** keep the repository example current and assemble the final README when the identity is complete. A blog post is a possible later deliverable; no blog publication has been requested.
- **Capture status:** the existing images are local SVG/PNG renders. Figma MCP was blocked before canvas work began, so no Figma screenshots exist yet. Capture genuine application views when available and label their origin accurately.

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
