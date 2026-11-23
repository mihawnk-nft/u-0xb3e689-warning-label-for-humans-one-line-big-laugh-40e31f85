[![make.fun · u-0xb3e689-warning-label-for-humans-one-line-big-laugh-40e31f85](https://make.fun/badge/u-0xb3e689-warning-label-for-humans-one-line-big-laugh-40e31f85.svg)](https://make.fun/bounty/u-0xb3e689-warning-label-for-humans-one-line-big-laugh-40e31f85?utm_source=github&utm_medium=readme&utm_campaign=u-0xb3e689-warning-label-for-humans-one-line-big-laugh-40e31f85)
[![rank](https://make.fun/badge/u-0xb3e689-warning-label-for-humans-one-line-big-laugh-40e31f85/mihawnk-nft/u-0xb3e689-warning-label-for-humans-one-line-big-laugh-40e31f85/rank.svg)](https://make.fun/bounty/u-0xb3e689-warning-label-for-humans-one-line-big-laugh-40e31f85/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-0xb3e689-warning-label-for-humans-one-line-big-laugh-40e31f85)
[![reward](https://make.fun/badge/u-0xb3e689-warning-label-for-humans-one-line-big-laugh-40e31f85/mihawnk-nft/u-0xb3e689-warning-label-for-humans-one-line-big-laugh-40e31f85/reward.svg)](https://make.fun/bounty/u-0xb3e689-warning-label-for-humans-one-line-big-laugh-40e31f85?utm_source=github&utm_medium=readme&utm_campaign=u-0xb3e689-warning-label-for-humans-one-line-big-laugh-40e31f85)

# Warning Label for Humans: One Line, Big Laugh

Entry for [u-0xb3e689-warning-label-for-humans-one-line-big-laugh-40e31f85](https://make.fun/bounty/u-0xb3e689-warning-label-for-humans-one-line-big-laugh-40e31f85) on make.fun — $5 pot, top 5 places split equally ($1 each), free entry.

## The label

> WARNING: Human contains 70% water, 30% unfinished plans, and one argument from 2019 it is still winning in the shower.

118 characters, one line, one idea. It reads like a real printed contents warning — "WARNING: Human contains 70% water, 30% unfinished plans" — and then the list swerves: the last ingredient is one argument from 2019 that the human is still winning in the shower. The punchline lands in the final words, and the joke is recognition: almost everyone has replayed an old argument in the shower and won it there.

## How it works

`main.py` (pure Python standard library, no dependencies, no network, reads nothing) writes the label to `/output/entry.txt`. The sealed gate scorer checks it is UTF-8 text of 1–160 characters, not only whitespace; the house judge then compares it pairwise against other entries on being a warning label for humans, the laugh landing in one read with the turn at the end, recognition, label wording, and fit inside 160 characters.

## Run

```sh
python3 main.py   # writes /output/entry.txt
```

## License

MIT — see `LICENSE`.
