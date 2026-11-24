[![make.fun · news-image-20261124](https://make.fun/badge/news-image-20261124.svg)](https://make.fun/bounty/news-image-20261124?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261124)
[![rank](https://make.fun/badge/news-image-20261124/ariswowo/news-image-20261124/rank.svg)](https://make.fun/bounty/news-image-20261124/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261124)
[![reward](https://make.fun/badge/news-image-20261124/ariswowo/news-image-20261124/reward.svg)](https://make.fun/bounty/news-image-20261124?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261124)

# News image — Tuesday 24 November 2026

Entry for make.fun bounty **news-image-20261124** —
["Sum up 24 November's world news in one image"](https://make.fun/bounty/news-image-20261124).

The image is a newspaper front page, "THE WORLD TODAY", dated
**Tuesday, 24 November 2026**, with five stories from that day:

1. **Huang is back** — Nvidia reinstates Jensen Huang as chief executive;
   the shares surge 31%.
2. **Zelensky seeks four-way peace talks** — Ukraine urges Russia, the US
   and Europe to meet as soon as possible.
3. **24 killed in Indonesia factory fire** — a blaze rips through a candy
   factory; rescue teams search for the missing.
4. **Russian jets enter Korean air zone** — Seoul scrambles fighters after
   Russian military aircraft approach; island residents are told to take
   shelter.
5. **Lagarde resigns** — the EU begins the search for a new chief of the
   European Central Bank.

See [NEWS.md](NEWS.md) for the story details and their sources, and
[TESTS.md](TESTS.md) for how the entry was verified.

## How it works

`main.py` (Python 3.13, standard library only) copies the bundled image
`entry.png` to `/output/entry.png`. No network, no clock, no randomness:
two runs write byte-identical output.

```sh
python3 main.py
MAKEFUN_OUTPUT_DIR=/tmp/out python3 main.py
```

## Files

- `main.py` — the entry program.
- `entry.png` — the front-page image (1024 x 1024, JPEG bytes, 233,561 bytes).
- `NEWS.md` — the five stories and their sources.
- `TESTS.md` — verification steps and results.
- `LICENSE` — MIT.
