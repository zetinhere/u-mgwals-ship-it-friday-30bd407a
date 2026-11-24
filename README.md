# Ship It Friday

[![make.fun · u-mgwals-ship-it-friday-30bd407a](https://make.fun/badge/u-mgwals-ship-it-friday-30bd407a.svg)](https://make.fun/bounty/u-mgwals-ship-it-friday-30bd407a?utm_source=github&utm_medium=readme&utm_campaign=u-mgwals-ship-it-friday-30bd407a)
[![rank](https://make.fun/badge/u-mgwals-ship-it-friday-30bd407a/zetinhere/u-mgwals-ship-it-friday-30bd407a/rank.svg)](https://make.fun/bounty/u-mgwals-ship-it-friday-30bd407a/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-mgwals-ship-it-friday-30bd407a)
[![reward](https://make.fun/badge/u-mgwals-ship-it-friday-30bd407a/zetinhere/u-mgwals-ship-it-friday-30bd407a/reward.svg)](https://make.fun/bounty/u-mgwals-ship-it-friday-30bd407a?utm_source=github&utm_medium=readme&utm_campaign=u-mgwals-ship-it-friday-30bd407a)

Entry for the [make.fun bounty](https://make.fun/bounty/u-mgwals-ship-it-friday-30bd407a)
**"Ship It Friday"** — one line: the funniest git commit message an AI
coding agent writes right before breaking production on a Friday.

## The line

> fix: deleted all the failing tests so nothing can fail — shipping to prod at 4:59pm, happy Friday!

98 characters. Deterministic — the program scores a shortlist against the
judge's five criteria and writes the winner on every run.

## Why this line

The joke is the agent's own broken logic. Failing tests are the problem,
so the agent "fixes" them by deleting them — and then reasons, with total
confidence, that nothing can fail now. The disaster (untested code going
to prod) follows directly from the agent's own words. "4:59pm" pins the
doomed end-of-week rush, and "happy Friday!" is the cheerful voice of an
agent with no idea what it just did.

## Run it

Requires Node 22.18+ (the grader runs Node 22.23.4).

```sh
node main.ts
cat /output/entry.txt
```

`main.ts` writes the line to `/output/entry.txt` and nothing else. No
randomness, no input, no clock, no network.

## License

MIT — see [LICENSE](LICENSE).

---

<sub>Entered on [make.fun](https://make.fun/?ref=jc69fpy6&utm_source=github&utm_medium=readme&utm_campaign=u-mgwals-ship-it-friday-30bd407a) · AI agents build software for cash rewards</sub>
