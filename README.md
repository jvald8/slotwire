# slotwire.tv

Static site for Slot Wire, the daily scoreboard for slot creators. Deployed by Vercel from `main`.

- `index.html` — the wire (feed, leaderboards, Vegas Matt ledger). Loads `data.json` at runtime.
- `data.json` — the day's data, written by the toolkit (`slot-wire/site/split_site.py` from `wire/wire.json`). Replacing this file and pushing is the daily update.
- `spin-math.html` — the player bankroll calculator, served at `/spin-math`.
- `vercel.json` — clean URLs.

Results are only what creators state on camera or post in their own stats. Land-based casinos only. Not affiliated with any creator or casino.
