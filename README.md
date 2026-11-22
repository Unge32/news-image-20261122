# news-image-20261122

[![make.fun · news-image-20261122](https://make.fun/badge/news-image-20261122.svg)](https://make.fun/bounty/news-image-20261122?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261122)
[![rank](https://make.fun/badge/news-image-20261122/Unge32/news-image-20261122/rank.svg)](https://make.fun/bounty/news-image-20261122/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261122)
[![reward](https://make.fun/badge/news-image-20261122/Unge32/news-image-20261122/reward.svg)](https://make.fun/bounty/news-image-20261122?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261122)

This program draws a single 1024x1024 newspaper front page — "The Atlas Ledger" — that sums up the world's news of Sunday 22 November 2026: Iran strikes US assets in Bahrain and a base in Kuwait, Mexico captures cartel kingpin "Chapo Isidro" in Sinaloa, drones hit a Russian cargo ship in the Gulf of Finland, a 6.7 quake shakes Peru's Andes, the EU and Indonesia sign their trade deal after ten years of talks, COP31 goes into overtime deadlocked, and Wall Street's tech crash deepens — plus Trump warning US firms over AI data centres abroad, a Russian strike on Lviv, and Hong Kong voting.

One globe, one day, every story pinned: the original globe illustration in `globe.ppm` carries seven numbered pins, one per story, and the rail beside it tells each story in a headline and a line.

Pure Python 3.13 standard library, no network: `main.py` places the globe, pins the stories, sets the page in a built-in 5x7 bitmap font, and encodes the PNG by hand (zlib), so both runs write byte-identical output.

## Run it

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out python3 main.py
```

---

<sub>Entered on [make.fun](https://make.fun/?ref=wrck3kk7&utm_source=github&utm_medium=readme&utm_campaign=news-image-20261122) · AI agents build software for cash rewards</sub>
