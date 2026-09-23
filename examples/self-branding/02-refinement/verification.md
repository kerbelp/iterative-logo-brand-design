# Round 2 verification

Status: proposed geometry, not a final approved identity.

## Method

Render the primary and optical SVGs using `rsvg-convert` at 16, 24, 32, and 64 px. Composite dark ink (`#202020`) on white, and white artwork on `#202020`. Inspect those PNGs at native size and with integer nearest-neighbor enlargement. The display board is a local render, not a Figma screenshot.

## Observed results

| Variant | Sizes | Backgrounds | Visual result | Proposed use |
| --- | --- | --- | --- | --- |
| Primary | 16 px | White and dark | All three parts remain visible, but fractional edges soften the frames and central square | Use the optical version at this exact size |
| Primary | 24 and 32 px | White and dark | Frames remain separate; center is visible; some antialiasing remains on fractional edges | Candidate primary use, awaiting review |
| Primary | 64 px | White and dark | Frame edges are crisp; the central square has antialiasing along its half-pixel edges | Candidate primary use; no loss of the center detail observed |
| Optical | 16 px | White and dark | Frames and central square render on whole pixels; 1 px of negative space remains around the center; no merging observed | Candidate variant for exactly 16 px |
| Optical | 24, 32, and 64 px | White and dark | Components remain separate; the center softens at 24 px because of the 1.5x scale | Comparison only; use primary at these sizes |

No clipping was observed. Artwork has padding inside its SVG canvas; this has not yet been adopted as a minimum clear-space rule.

## Automated checks

- SVG XML parses successfully.
- The four standalone mark SVGs contain vector paths and no embedded images or live text.
- Each PNG's dimensions match its declared export size.
- Both 16 px optical PNGs contain exactly two colors, consistent with their whole-pixel geometry on these backgrounds.
- Local Markdown links and image targets resolve.

The comparison board `pixel-checks.svg` intentionally embeds the actual raster exports; it is documentation, not a vector mark deliverable.

## Limits and remaining work

The checks describe this renderer's output on the two named backgrounds. They do not establish identical rasterization in every browser or prove physical print quality. A brand palette, final typography, name lockup, real application placement, physical reproduction, and user approval of the refined artwork remain pending.
