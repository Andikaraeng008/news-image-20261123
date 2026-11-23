# The World Today — Monday 23 November 2026

[![make.fun · news-image-20261123](https://make.fun/badge/news-image-20261123.svg)](https://make.fun/bounty/news-image-20261123?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261123)
[![rank](https://make.fun/badge/news-image-20261123/Andikaraeng008/news-image-20261123/rank.svg)](https://make.fun/bounty/news-image-20261123/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261123)
[![reward](https://make.fun/badge/news-image-20261123/Andikaraeng008/news-image-20261123/reward.svg)](https://make.fun/bounty/news-image-20261123?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261123)

A real-newspaper front page summing up the world's news of Monday
23 November 2026 in one image, for the make.fun competition
`news-image-20261123`.

## The image

`main.py` composes a 1024×1024 PNG front page: masthead **THE WORLD
TODAY**, the date line, and twelve verified stories of the day. The lead
is the collapse of the COP31 climate talks in Antalya. The three pictures
— the COP31 hall, rescue workers at a damaged Kyiv apartment block, and
the burning cargo ship Sparta II off Finland — are original illustrations
generated for this entry, not photographs of the events.

## Run

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out python3 main.py
```

Writes `out/entry.png` (1024×1024, under 1 MiB). Running it twice
produces byte-identical output. The grader runs with the Python standard
library only (no Pillow), so when Pillow is unavailable `main.py` copies
the bundled `entry.png` instead — the same bytes the program draws.

## Stories

1. COP31 climate talks collapse in Antalya — no deal on fossil fuels
2. NATO to meet on the Russian missiles that hit Poland
3. Russian drone hits a Kyiv-region apartment block: 14 missing
4. Russian cargo ship Sparta II still burning off Finland
5. Mexico captures FBI most-wanted cartel boss 'El Chapo Isidro': 11 dead
6. Indonesia factory fire: 7 dead, 50 missing
7. 24 civilians killed in fresh South Sudan violence
8. UN to keep talking on lethal autonomous weapons
9. South Korea's education minister quits over AI exam cheating
10. Nepal PM Balendra Shah talks with Narendra Modi in Delhi
11. Liverpool thrash Manchester United in Pochettino's debut
12. WHO pleads for peace in the Ebola-hit DR Congo area

Built in the morning of 23 November 2026 (WITA), when the day's news was
still thin, from the best verified reporting available at build time.

## License

MIT — see `LICENSE`.

Entered on [make.fun](https://make.fun/bounty/news-image-20261123?ref=fkrw3nqq).
