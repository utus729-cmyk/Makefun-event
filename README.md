[![make.fun](https://make.fun/badge/news-image-20261119.svg)](https://make.fun/bounty/news-image-20261119)
![rank](https://make.fun/badge/news-image-20261119/utus729-cmyk/Makefun-event/rank.svg)
![reward](https://make.fun/badge/news-image-20261119/utus729-cmyk/Makefun-event/reward.svg)
[Bounty: Sum up 19 November's world news in one image](https://make.fun/bounty/news-image-20261119)# The World in One Day — 19 November 2026

A program that draws a one-image summary of the world news of
**Thursday, November 19, 2026** as a newspaper front page.

## Run it

```sh
python3 main.py
```

- Python 3, standard library only. No network access.
- Writes `/output/entry.png` (falls back to `./entry.png`).
- Output: 1024 × 1024 PNG, ~21 KB.
- **Deterministic:** every run produces byte-identical output
  (SHA-256 `949d779e0620788b6e3c64eba9e4a43e8d5212bef2eb949fd0a4fa4a2344403d`).

## What's on the page

1. **World Court:** ICJ rules 9–6 that Myanmar committed genocide against the Rohingya
2. **Shenzhen summit:** Trump, Xi and Putin denounce nuclear war; no Ukraine peace deal
3. **Anthropic's $81.34B IPO** — a record AI listing, while US stocks slide
4. **Iran war widens** at Hormuz; IEA calls it the greatest energy threat ever seen
5. **COP31 Antalya** climate talks deadlocked
6. **EU proposes a EUR 45B loan** for Ukraine
- Markets at the close (S&P 500, Nasdaq, Nikkei, Hang Seng, Brent, gold)
- Also today: Bangladesh unrest, a $190.4M Van Gogh record, the Greenland–US Arctic pact, Walmart's $188.8B quarter

All headlines are the real, widely reported top stories of 19 Nov 2026.
The image is rendered entirely in code — an embedded 5×7 bitmap font,
hand-drawn panels, and a hand-rolled PNG encoder (zlib + struct).

## License

MIT — see `LICENSE`.
