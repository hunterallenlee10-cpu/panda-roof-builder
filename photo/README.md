# Photos look: where the pictures came from

Every picture in this folder was made with AI (Higgsfield, model GPT Image 2.6) on Nov 24, 2026. None is a photo of a real home or a real job, and none
shows a customer's house. The page labels the house as a sample and as an AI picture.

## What each file is

| File | What it shows |
|---|---|
| `house-<color>.webp` (and `-s` for phones) | One sample roof, shot like a contractor's low drone photo, in each of the nine Timberline HDZ colors |
| `cut-std-<color>.webp` | Roof display section with standard layers: plywood deck, black mineral leak barrier, light gray synthetic underlayment, starter strip, shingles, ridge vent and ridge caps |
| `cut-prem-<color>.webp` | The same section with the premium layers: turquoise film leak barrier and pale blue breathable underlayment |
| `build-1`, `build-2-*`, `build-3-*` | The earlier stages of the same section (bare deck, leak barrier, underlayment) for the "watch it build" steps |
| `sw-<color>.webp` | Color button pictures, cropped from the house roofs |
| `x-gutter`, `x-guard`, `x-skylight`, `x-chimney` | Close-ups for the optional extras |

## How the colors were matched

1. Each color's swatch was read from GAF's Timberline HDZ product page and its average color measured.
2. The swatch was given to the image model as the reference for that roof.
3. The average color of each finished roof was measured and compared with the swatch.

| Color | GAF swatch (average) | House roof (average, in daylight) |
|---|---|---|
| Charcoal | #2c2d2f | #323335 |
| Pewter Gray | #4a5153 | #565c61 |
| Weathered Wood | #655e4f | #6b6455 |
| Barkwood | #554737 | #5b4e41 |
| Hickory | #4a3427 | #523d31 |
| Shakewood | #775e41 | #7e674f |
| Mission Brown | #5f5347 | #655d57 |
| Hunter Green | #253930 | #2e4037 |
| Williamsburg Slate | #51564f | #5c5e5a |

The first house picture was a wider, street-level view. It read as staged, so it was replaced with a closer
drone-style view where the roof fills the frame and the color grading is left flat.

Shingle size was also corrected: the first drafts drew tabs about twice too large, so the roofs are drawn
at a 5 5/8 inch exposure (about 30 courses from gutter to ridge).

## The Real job version

`real-<color>.webp` (and `-s`) and `rsw-<color>.webp` come from one of Panda's own drone photos in the website
media library (item 1691, uploaded April 2025, a finished roof with the Panda truck in the street). Each color
was made by asking the image model to change only the shingles, then lining the result up with the original
(about half a pixel of error) and keeping the original photo everywhere outside a hand-traced roof outline. The
original upload is small and soft (1,159 pixels wide), so everything outside the roof is an AI-upscaled copy
of that same photo: sharper, but the same house, lawn, street and truck. Only the shingles are new. Roughly 45% of
the frame is roof.

The roof in the original photo is a sunlit dark gray. All nine colors, Charcoal included, are recolored so they
sit on the same scale as the swatches.

Before this goes in front of customers: confirm the homeowner is fine with the photo being used this way.

## Known limits

- The underlayment and leak barrier carry no printed logos. The real GAF rolls do.
- The premium layers are drawn as GAF's blue breathable underlayment and turquoise film leak barrier. Which
  exact products Panda puts in each package has not been confirmed.
- Screens show color differently. The page still tells homeowners real samples come before install.
- The house photo does not change with trim color, gutters, skylights or chimneys. Those show as close-ups.
