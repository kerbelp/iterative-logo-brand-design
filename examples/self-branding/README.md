# A logo for the logo-design skill

An ongoing example of using the skill on its own repository. This records the actual exploration and feedback as they happen; it is not a completed case study.

## Brief

The maintainer asked to design a logo collaboratively, use Figma, and include images of the process in the repository. The identity is for **Iterative Logo & Brand Design**, an independent agent workflow for exploring, refining, and verifying logos.

Working assumptions proposed by the agent, awaiting feedback:

- Audience: people using agents for design, including designers and developers.
- Personality: thoughtful, approachable, and precise; explore a craft-focused geometric direction first.
- Uses: a small skill icon and a GitHub README header, with a social preview as a possible later application.
- Preserve the full project name and its independent attribution. The supplied pencil icon remains in place until a replacement is selected and verified.

Compare concepts on distinctiveness, small-size clarity, and how naturally they suggest iterative design. The concept vocabulary is **stroke, return, draft, frame, repetition, and initial**.

## Round 1: concept exploration

![First comparison of three monochrome vector concepts](01-exploration/contact-sheet.png)

All three are original editable SVG sketches shown on equal canvases in the same ink. The board uses Arial with Helvetica and sans-serif fallbacks for presentation text; this is not a proposed brand typeface. The marks themselves contain no live text or embedded bitmaps.

| Direction | Idea | Advantage | Open concern |
| --- | --- | --- | --- |
| [A — Return stroke](01-exploration/a-return-stroke.svg) | A pencil paired with a returning stroke | Immediately communicates drawing and revision | Could read as a generic edit control; the pencil opening needs size tests |
| [B — Second draft](01-exploration/b-second-draft.svg) | Offset frames with a resolved center | Simple modular geometry offers a useful basis for an identity | Could read as a layers tool; spacing needs optical refinement |
| [C — Iterative i](01-exploration/c-iterative-i.svg) | An initial with a repeated dot and turning stem | Offers a compact typographic direction | The stem may read as a t, and the repeated dot may disappear at small sizes |

**Agent recommendation:** explore B first for its modular construction and potential to extend into a visual system. This is a recommendation, not a user selection. A is the most immediately literal option; C needs more work on letter recognition.

## What has actually been checked

- The comparison board was rendered locally with `rsvg-convert` and visually inspected for spacing, legibility, and clipping.
- SVG syntax and local Markdown image/link targets were checked.
- No concept has been approved. Actual 16, 24, 32, and 64 px tests, reverse versions, typography selection, and final export verification are still pending.

## Figma status

A [Figma process file](https://www.figma.com/design/jIboEmJ2p9sDszWPKTFtDo) was created on 23 September 2026. The next MCP call hit the account's Starter-plan tool limit before any artwork could be placed, so that file is currently empty. The images above are local SVG renders, not Figma screenshots. File access depends on the owner's Figma sharing settings.

When Figma access is available, import the concept SVGs and preserve this first round before refining the selected direction. Add genuine Figma captures to this example as that work happens.

## Next decision

The maintainer can select A, B, or C, combine specific elements, or request a different direction. After selection, refine the geometry, perform actual small-size checks, explore color and a name lockup, and record feedback alongside the next comparison.

See [the decision log](design-decisions.md) for the current state.
