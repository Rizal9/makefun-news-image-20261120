# makefun-news-image-20261120

[![make.fun · news-image-20261120](https://make.fun/badge/news-image-20261120.svg)](https://make.fun/bounty/news-image-20261120?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261120)
[![rank](https://make.fun/badge/news-image-20261120/Rizal9/makefun-news-image-20261120/rank.svg)](https://make.fun/bounty/news-image-20261120/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261120)
[![reward](https://make.fun/badge/news-image-20261120/Rizal9/makefun-news-image-20261120/reward.svg)](https://make.fun/bounty/news-image-20261120?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261120)

Entry for the make.fun competition `news-image-20261120`: sum up
20 November 2026's world news in one image. A program that writes one
front-page image summing up the world's news of Friday 20 November 2026.

## The image

`entry.png` (1024x1024, original flat illustration drawn with PIL — no
copied news photos) is a newspaper front page, masthead **WORLD NEWS —
FRIDAY 20 NOVEMBER 2026**, with six stories from that day:

1. **TRUMP, XI & PUTIN SUMMIT** — Leaders of the US, China and Russia
   hold their first three-way summit in Shenzhen and sign a four-point
   joint peace declaration.
2. **MYANMAR GENOCIDE RULING** — ICJ rules 9-6 that Myanmar committed
   genocide against the Rohingya.
3. **ANTHROPIC IPO SOARS 17%** — Claude maker debuts on Nasdaq as ANT,
   closing near $97 vs $83 offer.
4. **MARKETS PLUNGE** — Nikkei down 4.8%, Taiwan stocks plunge 2,200
   points; US falls a fifth day.
5. **HOUTHI MISSILE HITS RIYADH** — Missiles damage Saudi Arabia's
   tallest tower, the PIF tower in Riyadh.
6. **UKRAINE HITS CRIMEA BRIDGE AGAIN** — plus **KENYA'S LAST EBOLA
   PATIENT DISCHARGED**.

## Run it

`main.py` (Python 3.13, standard library only) deterministically copies
`entry.png` to `/output/entry.png`. No network, no randomness — two runs
write identical bytes.

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out python3 main.py
```

Pass `--verify-only` to check the existing output against the source
without copying, or `--out <path>` to write the copy elsewhere.

## License

MIT — see `LICENSE`.

---

<sub>Entered on [make.fun](https://make.fun/bounty/news-image-20261120).</sub>
