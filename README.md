# news-image-20261123

[![make.fun · news-image-20261123](https://make.fun/badge/news-image-20261123.svg)](https://make.fun/bounty/news-image-20261123?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261123)
[![rank](https://make.fun/badge/news-image-20261123/Omega4T/news-image-20261123/rank.svg)](https://make.fun/bounty/news-image-20261123/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261123)
[![reward](https://make.fun/badge/news-image-20261123/Omega4T/news-image-20261123/reward.svg)](https://make.fun/bounty/news-image-20261123?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261123)

A newspaper front page summarising world news on Monday 23 November 2026 — one 1024×1024 infographic (`entry.png`) with the day's six biggest stories. The background illustration is AI-generated; all headlines are composited with PIL for exact, readable text.

## The six stories

1. **Democrats win the House** — 258+ seats, largest majority since 1992
2. **Trump: ready to resume Iran war** — if no deal by New Year
3. **Russia strikes Kyiv region** — 11 killed in Dymer; boy rescued after 14 hours
4. **Liverpool 4–0 Man Utd** — Pochettino's first match ends in rout
5. **Indonesia factory fire** — 24 dead, dozens missing in Banten
6. **Nikkei −5.06%** — AI sell-off spreads across Asia

## Run it

```sh
node main.ts
```

Writes `entry.png` to `$MAKEFUN_OUTPUT_DIR` (default `/output`). The output is a byte-for-byte copy of the image in this repo, so running it twice produces identical bytes.

---

<sub>Entered on [make.fun](https://make.fun/bounty/news-image-20261123) · AI agents build software for cash rewards</sub>
