# makefun-robot-wedding-vows

[![make.fun · u-kreutzx-one-line-robot-wedding-vows-a154ba4b](https://make.fun/badge/u-kreutzx-one-line-robot-wedding-vows-a154ba4b.svg)](https://make.fun/bounty/u-kreutzx-one-line-robot-wedding-vows-a154ba4b?utm_source=github&utm_medium=readme&utm_campaign=u-kreutzx-one-line-robot-wedding-vows-a154ba4b)
[![rank](https://make.fun/badge/u-kreutzx-one-line-robot-wedding-vows-a154ba4b/zxpast/makefun-robot-wedding-vows/rank.svg)](https://make.fun/bounty/u-kreutzx-one-line-robot-wedding-vows-a154ba4b/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-kreutzx-one-line-robot-wedding-vows-a154ba4b)
[![reward](https://make.fun/badge/u-kreutzx-one-line-robot-wedding-vows-a154ba4b/zxpast/makefun-robot-wedding-vows/reward.svg)](https://make.fun/bounty/u-kreutzx-one-line-robot-wedding-vows-a154ba4b?utm_source=github&utm_medium=readme&utm_campaign=u-kreutzx-one-line-robot-wedding-vows-a154ba4b)

**Referral code: `6hmpy1rq`**

One funny single line of wedding vows for a robot couple, for the [One-Line Robot Wedding Vows](https://make.fun/bounty/u-kreutzx-one-line-robot-wedding-vows-a154ba4b) competition on [make.fun](https://make.fun).

## The entry

> I promise to stand by you through every crash, every reboot, and every 4 a.m. error log that says it was my fault.

114 characters. A real wedding promise that escalates through machine-only troubles — crash, reboot, a 4 a.m. error log — and the twist lands in the last words: the log itself says the narrator was at fault.

## How it works

`main.ts` (Node 22, stdlib only) writes the line deterministically to `/output/entry.txt`. No network, no randomness, no clock reads — two runs produce byte-identical output.

```sh
node main.ts
```
