# Panda Roof Builder

Demo of an online roof-buying tool for Panda Exteriors, in three steps: enter an address, pick a package,
then see the price range and either reserve the roof or book a video walkthrough.

- `index.html`: the whole tool. Territory, phone number, stats, packages and every price live in the
  `CONFIG` and `PRICING` blocks at the top of the script.
- `homes.json`: 20,267 detached homes from public property records (address, year built, size, building
  outline). It holds no CRM data.
  - Laurel, ZIP codes 20707, 20708, 20723 and 20724: 15,158 homes.
  - Leonardtown, ZIP code 20650: 5,109 homes, added Nov 26, 2026. 3,786 have a building outline. These
    homes come from Maryland's parcel records (single-family standard, split foyer and split level
    dwellings) and the state's building footprints.
  - On a lot with a barn or shop as well as the house, an outline is kept only when it is clearly the
    house. Other homes are sized from living area.
  - Each ZIP code's town name is set in `CONFIG.towns` in `index.html`. Leonardtown's roof-to-floor-area
    ratios are in `RATIOS`.
- `jspdf.umd.min.js`: jsPDF 4.2.1 (MIT), used to build the estimate PDF in the browser.
- `vercel.json`: tells search engines not to index the site.
- `photo/`: the pictures behind the AI photo and Real job versions (the switch in the header). See
  `photo/README.md` for how they were made and checked.

Package prices, gutter prices and the decking price come from the active "Panda Exteriors Price Book" in the
Panda CRM (read Nov 23, 2026). Steep-roof, second-layer, skylight and chimney charges are still placeholders.

The page opens in the drawn version. Add `?look=photo` to a link to open the AI photo version, or `?look=real`
for the version built on a real Panda job photo.

Nothing is sent, reserved, signed or charged. A live version needs the real price sheet, Panda's Maryland
home improvement agreement and e-signature, and a connection to the CRM.
