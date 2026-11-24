# Panda Roof Builder

Demo of an online roof-buying tool for Panda Exteriors, in three steps: enter an address, pick a package,
then see the price range and either reserve the roof or book a video walkthrough.

- `index.html`: the whole tool. Territory, phone number, stats, packages and every price live in the
  `CONFIG` and `PRICING` blocks at the top of the script.
- `homes.json`: 15,158 detached homes in Laurel ZIP codes 20707, 20708, 20723 and 20724 from public property
  records (address, year built, size, building outline). It holds no CRM data.
- `jspdf.umd.min.js`: jsPDF 4.2.1 (MIT), used to build the estimate PDF in the browser.
- `vercel.json`: tells search engines not to index the site.

Prices are placeholders. The three package rates were worked backwards from Panda's example estimate for
7661 Kindler Rd and reproduce its ranges; they should be replaced with the 2026 retail sheet.

Nothing is sent, reserved, signed or charged. A live version needs the real price sheet, Panda's Maryland
home improvement agreement and e-signature, and a connection to the CRM.
