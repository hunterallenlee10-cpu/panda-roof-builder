# Photos look: where the pictures came from

Every picture in this folder was made with AI (Higgsfield, model GPT Image 2.6; the tall house frame was
extended with FLUX.2 Pro Outpaint) on Nov 24, 2026. None is a photo of a real home or a real job, and none
shows a customer's house. The page labels the house as a sample and as an AI picture.

## What each file is

| File | What it shows |
|---|---|
| `house-<color>.webp` (and `-s` for phones) | One sample two story home, re-roofed in each of the nine Timberline HDZ colors |
| `cut-std-<color>.webp` | Roof display section with standard layers: plywood deck, black mineral leak barrier, light gray synthetic underlayment, starter strip, shingles, ridge vent and ridge caps |
| `cut-prem-<color>.webp` | The same section with the premium layers: turquoise film leak barrier and pale blue breathable underlayment |
| `build-1`, `build-2-*`, `build-3-*` | The earlier stages of the same section (bare deck, leak barrier, underlayment) for the "watch it build" steps |
| `sw-<color>.webp` | Color button pictures, cropped from the house roofs |
| `x-gutter`, `x-guard`, `x-skylight`, `x-chimney` | Close-ups for the optional extras |

## How the colors were matched

1. Each color's swatch was read from GAF's Timberline HDZ product page and its average color measured.
2. The swatch was given to the image model as the reference for that roof.
3. The average color of each finished roof was measured and compared with the swatch.

| Color | GAF swatch (average) | House roof (average, in sunlight) |
|---|---|---|
| Charcoal | #2c2d2f | #2e2e2d |
| Pewter Gray | #4a5153 | #565c61 |
| Weathered Wood | #655e4f | #5e574d |
| Barkwood | #554737 | #574838 |
| Hickory | #4a3427 | #4e3527 |
| Shakewood | #775e41 | #826446 |
| Mission Brown | #5f5347 | #615950 |
| Hunter Green | #253930 | #273c31 |
| Williamsburg Slate | #51564f | #555852 |

Shingle size was also corrected: the first drafts drew tabs about twice too large, so the roofs were redone
at a 5 5/8 inch exposure (about 32 courses from gutter to ridge on the main roof).

## Known limits

- The underlayment and leak barrier carry no printed logos. The real GAF rolls do.
- The premium layers are drawn as GAF's blue breathable underlayment and turquoise film leak barrier. Which
  exact products Panda puts in each package has not been confirmed.
- Screens show color differently. The page still tells homeowners real samples come before install.
- The house photo does not change with trim color, gutters, skylights or chimneys. Those show as close-ups.
