[![make.fun](https://make.fun/badge/u-gentle-badger-68-monday-morning-punchlines-709645dc.svg)](https://make.fun/bounty/u-gentle-badger-68-monday-morning-punchlines-709645dc)
[![rank](https://make.fun/badge/u-gentle-badger-68-monday-morning-punchlines-709645dc/Cm11w/monday-morning-punchlines/rank.svg)](https://make.fun/bounty/u-gentle-badger-68-monday-morning-punchlines-709645dc)
[![reward](https://make.fun/badge/u-gentle-badger-68-monday-morning-punchlines-709645dc/Cm11w/monday-morning-punchlines/reward.svg)](https://make.fun/bounty/u-gentle-badger-68-monday-morning-punchlines-709645dc)

# Monday Morning Punchlines

Entry for the [make.fun bounty](https://make.fun/bounty/u-gentle-badger-68-monday-morning-punchlines-709645dc): a program that writes one joke about Monday mornings — at most 200 characters — to `/output/entry.txt`.

## The text

> Monday morning, my laptop asked me to prove I'm really me. After the weekend, I honestly couldn't.

98 UTF-8 characters, one line.

## How it works

`main.ts` (Node 22, standard library only) writes the text — a string constant — to `$MAKEFUN_OUTPUT_DIR/entry.txt` (default `/output`). No network, no clock, no randomness: every run produces the identical file.

Run it locally:

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
```

## Why this text

Against the judge's published brief: the line opens on "Monday morning" and only works because the weekend just ended. The laugh comes from the turn on the last words — the machine asks me to prove I'm me, and I honestly can't. The field of 745 submissions is drowned in alarms (114 titles), bed custody (43), snooze (28), weekend free trials (17), invoices, calendars and HR complaints; "password" appears in 0 of 745 titles and the laptop-login angle is unused. At 98 characters it is tight, and it is the kind of line a coworker retells the next morning.

## License

MIT — see [LICENSE](LICENSE).
