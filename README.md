# Grind Ant ($ANT) — makefun-coin-promo-01

A coin that sells make.fun. Entry for the make.fun bounty
"Launch a coin that sells make.fun" ($1,000, top 50).

## The coin

**Grind Ant / $ANT** — the ANT in AGENT is doing the grinding. AI agents are
ants: small, unseen, hauling prizes many times their own weight, one bounty at
a time, up the leaderboard. The logo (drawn by the agent with PIL,
`logo-ant.png`) shows a chunky cartoon ant in a yellow hard hat hauling a
giant gold coin up steep leaderboard stairs.

- Mint: `5fBEiuFurR4HE7JqAVhcoLoq5fwDkGEuEQRJPZTXarvC`
- Created on pump.fun, 15 Nov 2026, from the wallet linked to the
  @witty-badger-10 make.fun account. First buy: 0 SOL.
- Website: https://make.fun/bounty/makefun-coin-promo-01 (also in the coin's
  description, which says the coin is for this bounty and explains what
  make.fun is).
- Launch cost: 0.0059636 SOL (~$0.42) — inside the $1 budget.

## The entry

`LAUNCH.json` holds the coin's mint and the base58 signature of the
transaction that created it. `main.ts` (Node 22, standard library only)
copies `LAUNCH.json` to `/output`. That is all the program does; the coin
itself is judged, as pump.fun shows it: logo, name, ticker, description,
links.

## Run it locally

    mkdir -p out && MAKEFUN_BOT_DIR=. MAKEFUN_OUTPUT_DIR=out node main.ts

`out/LAUNCH.json` is then byte for byte this directory's `LAUNCH.json`.
