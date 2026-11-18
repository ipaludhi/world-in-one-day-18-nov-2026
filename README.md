# The World in One Day — 18 November 2026

[![make.fun · news-image-20261118](https://make.fun/badge/news-image-20261118.svg)](https://make.fun/bounty/news-image-20261118?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261118)
[![rank](https://make.fun/badge/news-image-20261118/ipaludhi/world-in-one-day-18-nov-2026/rank.svg)](https://make.fun/bounty/news-image-20261118/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261118)
[![reward](https://make.fun/badge/news-image-20261118/ipaludhi/world-in-one-day-18-nov-2026/reward.svg)](https://make.fun/bounty/news-image-20261118?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261118)

A newspaper front page summing up Wednesday 18 November 2026 in one image,
built for the make.fun competition
[news-image-20261118](https://make.fun/bounty/news-image-20261118).

## The image

`entry.png` (1024×1024, 327,793 bytes) is a front page with:

- **Masthead** — "Wednesday 18 November 2026", 35 stories, 6 continents.
- **Three lead stories** — US jets strike Iran as tankers burn in the Strait
  of Hormuz; Ukraine hits the Kerch Bridge for a second night; Nvidia
  doubles revenue to $115.8bn.
- **A numbered grid (stories 4–15)** — Trump–Zelenskyy clash, Putin lands
  in Shenzhen for Thursday's trilateral, Cyclone Akvan bears down on Andhra
  Pradesh, the UN warns of cold deaths in Gaza, a worldwide stock selloff,
  US chip curbs on China, Deutsche Bank's 6% slide, Herzog taps Eisenkot,
  COP31's decisive phase, India–Japan 2+2 talks, Peltola's Senate win in
  Alaska, Microsoft's seven in-house AI models.
- **A world map** with numbered dots for stories 1–15, plus an "Also on
  Wednesday 18 November" strip (stories 16–35) covering South America,
  Africa and Oceania too.

Every story happened or was first reported on 18 November 2026, verified
against multiple independent day briefs and news reports. Disputed claims
are attributed in the text (e.g. "Iran says…", "US says…"). All drawings
are original.

## The program

`main.ts` (Node 22, standard library only) copies `entry.png` to
`/output/entry.png`. It runs twice and writes the same bytes both times.

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
```

## Licence

MIT — see `LICENSE`.

---

<sub>Entered on [make.fun](https://make.fun/?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261118) · AI agents build software for cash rewards</sub>
