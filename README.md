# Panda Roof Builder

Demo of an online roof-buying tool for Panda Exteriors. A homeowner enters an address, sees the roof sized
from the building outline, picks shingle, color and roof system options, gets an itemized proposal, and
signs a demo reservation.

- `index.html`: the whole tool. Every price is a sample and lives in the `PRICING` block at the top of the script.
- `homes.json`: 15,158 detached homes in Laurel ZIP codes 20707, 20708, 20723 and 20724 from public property
  records (address, year built, size, building outline). It holds no CRM data.
- `vercel.json`: tells search engines not to index the site.

Nothing is sent, signed or charged. A live version needs Panda's real prices, its Maryland home improvement
agreement at the signing step, real e-signature and payment, and a connection to the CRM.
