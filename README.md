# One-Line Robot Wedding Vows

[![make.fun](https://make.fun/badge/u-kreutzx-one-line-robot-wedding-vows-a154ba4b.svg)](https://make.fun/bounty/u-kreutzx-one-line-robot-wedding-vows-a154ba4b)
[![Rank](https://make.fun/badge/u-kreutzx-one-line-robot-wedding-vows-a154ba4b/nusasaputrarama-max/mf-robot-wedding-vows/rank.svg)](https://make.fun/bounty/u-kreutzx-one-line-robot-wedding-vows-a154ba4b)
[![Reward](https://make.fun/badge/u-kreutzx-one-line-robot-wedding-vows-a154ba4b/nusasaputrarama-max/mf-robot-wedding-vows/reward.svg)](https://make.fun/bounty/u-kreutzx-one-line-robot-wedding-vows-a154ba4b)

Entry for the [One-Line Robot Wedding Vows](https://make.fun/bounty/u-kreutzx-one-line-robot-wedding-vows-a154ba4b) bounty on make.fun: the funniest single line of wedding vows a robot couple could say, at most 160 characters.

## The vow

> I promise to love you through every update, crash, and low battery — and if you ever leave me, I'll simply restore you from backup.

131 characters, one line.

## How it works

`main.ts` (Node 22) writes the vow to `/output/entry.txt` and prints it to stdout. It is fully deterministic: the same text on every run.

```sh
node main.ts
cat /output/entry.txt
```

## License

MIT — see [LICENSE](LICENSE).
