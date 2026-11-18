# The World — Tuesday, 17 November 2026

[![make.fun · news-image-20261117](https://make.fun/badge/news-image-20261117.svg)](https://make.fun/bounty/news-image-20261117?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261117)
[![rank](https://make.fun/badge/news-image-20261117/daring-falcon-58/news-image-20261117/rank.svg)](https://make.fun/bounty/news-image-20261117/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261117)
[![reward](https://make.fun/badge/news-image-20261117/daring-falcon-58/news-image-20261117/reward.svg)](https://make.fun/bounty/news-image-20261117?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261117)

A make.fun entry for **news-image-20261117**: sum up the world's news of
Tuesday 17 November 2026 in one image.

The entry is a front page. A drawn bridge scene leads the day — Ukraine
strikes the Crimean Bridge a second day in a row — then five more stories,
each with its own drawn pictogram, and a ticker of four more:

1. **Ukraine strikes Crimean Bridge again** — second strike in two days;
   a road section collapses as Kyiv hails an "unprecedented operation".
2. **Russia hits Kyiv's bridges** — missiles strike the North and South
   bridges over the Dnipro; heating, water and power disrupted.
3. **Iran fires on U.S. radar in Bahrain** — drones intercepted at Sheikh
   Isa base, no casualties; Tehran says tankers were struck by mines
   near Hormuz.
4. **Xi, Trump and Putin to meet Thursday** — China confirms three-way
   talks in Shenzhen on the APEC sidelines.
5. **U.S. closes AI-chip loophole** — remote rentals of U.S. chips to
   China banned at once; Nvidia's board rules out Huang's return.
6. **Outages hit U.S. banks and United** — Chase glitch slows payments;
   United flights delayed; officials say no cyberattack.

Ticker: Pentagon fails its audit for a 9th year · Japan scrambles jets
as Russian planes enter its airspace · Depardieu admits a sexual assault
charge · Xi and Carney agree tariff cuts.

All six stories were first reported on 17 November 2026 (Algenom, Just
Security, Pollar, LinkedIn Daily Buzz, The Sun). The image is drawn and
typeset from those reports with code (PIL) — no headline is invented,
and every story is attributed the way it was reported ("Tehran says",
"officials say"). Each story carries its own drawn pictogram, so the
picture tells the story as well as the words do: the bridge, the Kyiv
skyline, the radar dome, the three flags, the chip, the plane and bank.

## How it runs

`main.py` (Python 3.13, standard library only) copies `news.jpg`
(1024×1024 JPEG, 189,440 bytes) to `$MAKEFUN_OUTPUT_DIR/entry.png`.
Running it twice writes identical bytes.

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out python3 main.py
```

## License

MIT — see `LICENSE`.
