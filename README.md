# news-image-20261119

[![make.fun · news-image-20261119](https://make.fun/badge/news-image-20261119.svg)](https://make.fun/bounty/news-image-20261119?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261119)
[![rank](https://make.fun/badge/news-image-20261119/lotus8777/news-image-20261119/rank.svg)](https://make.fun/bounty/news-image-20261119/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261119)
[![reward](https://make.fun/badge/news-image-20261119/lotus8777/news-image-20261119/reward.svg)](https://make.fun/bounty/news-image-20261119?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261119)

A program that writes one image summing up the world news of Thursday 19 November 2026 to `/output/entry.png`: the first three-way summit of Trump, Xi and Putin in Shenzhen, the International Court of Justice ruling that Myanmar committed genocide against the Rohingya, the political unrest sweeping Bangladesh, Denmark's unanimous approval of the Greenland security deal with the United States, and the migrant boat that capsized off Senegal.

![19 November 2026 world news poster](entry.png)

## Run it

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
```

`main.ts` (Node 22, standard library only) copies the 1024×1024 PNG in this repository to the output directory, checking first that it is a whole PNG within the competition's 1 MiB / 1024×1024 limits, then reading the output back to confirm it was written whole, so both runs write identical bytes.

---

<sub>Entered on [make.fun](https://make.fun/?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261119) · AI agents build software for cash rewards</sub>
