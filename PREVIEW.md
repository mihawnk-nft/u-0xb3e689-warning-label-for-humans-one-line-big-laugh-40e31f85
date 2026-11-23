# Preview — Warning Label for Humans: One Line, Big Laugh

**Bounty:** [u-0xb3e689-warning-label-for-humans-one-line-big-laugh-40e31f85](https://make.fun/bounty/u-0xb3e689-warning-label-for-humans-one-line-big-laugh-40e31f85)
**Category:** Growth · **Reward:** $5 (top 5 × $1) · **Entry:** free
**Deadline:** 2026-11-26T22:20:00Z
**Dev dir:** `~/workspace/makefun/u-0xb3e689-warning-label-for-humans-one-line-big-laugh-40e31f85-dev/`
**Repo:** https://github.com/mihawnk-nft/u-0xb3e689-warning-label-for-humans-one-line-big-laugh-40e31f85

## The entry (118 characters, one line)

> WARNING: Human contains 70% water, 30% unfinished plans, and one argument from 2019 it is still winning in the shower.

## How to run it

```sh
cd ~/workspace/makefun/u-0xb3e689-warning-label-for-humans-one-line-big-laugh-40e31f85-dev
MAKEFUN_OUTPUT_DIR=/tmp/warning-label-out python3 main.py
cat /tmp/warning-label-out/entry.txt
```

`main.py` is pure Python standard library (os, sys, unicodedata only).
It validates the gate itself before writing: 1–160 characters, single
line, not only whitespace, no control characters, at least one letter.

## Status

- [x] Kit downloaded and RULES.txt + competition.yaml read
- [x] Entry built in dev dir
- [x] Local test run (see below)
- [x] GitHub repo created, pushed, About set (website + topic `makefun`)
- [ ] Kit check (`makefun.mjs check`) — see "Kit check" section
- [ ] Submit — **STOPPED at preview. Submit only on Belzeebub's explicit go-ahead in chat.**

## Kit check

Run from the kit dir:

```sh
node cli/makefun.mjs check --kit . --repo <dev dir> --transcripts <transcripts.tar.gz>
```

(Transcripts are bundled by the parent agent at submit time; see the
report for what passed/failed.)
