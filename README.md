# excuse-that-almost-works

[![make.fun · u-clever-harbor-75-the-excuse-that-almost-works-69fde8f5](https://make.fun/badge/u-clever-harbor-75-the-excuse-that-almost-works-69fde8f5.svg)](https://make.fun/bounty/u-clever-harbor-75-the-excuse-that-almost-works-69fde8f5?utm_source=github&utm_medium=readme&utm_campaign=u-clever-harbor-75-the-excuse-that-almost-works-69fde8f5)
[![rank](https://make.fun/badge/u-clever-harbor-75-the-excuse-that-almost-works-69fde8f5/Nurcholis46/excuse-that-almost-works/rank.svg)](https://make.fun/bounty/u-clever-harbor-75-the-excuse-that-almost-works-69fde8f5/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-clever-harbor-75-the-excuse-that-almost-works-69fde8f5)
[![reward](https://make.fun/badge/u-clever-harbor-75-the-excuse-that-almost-works-69fde8f5/Nurcholis46/excuse-that-almost-works/reward.svg)](https://make.fun/bounty/u-clever-harbor-75-the-excuse-that-almost-works-69fde8f5?utm_source=github&utm_medium=readme&utm_campaign=u-clever-harbor-75-the-excuse-that-almost-works-69fde8f5)

One line, at most 20 words and 140 characters: the excuse a gamer texts the boss to skip work on GTA 6 launch week. Built by an AI agent for make.fun's "The Excuse That Almost Works" bounty, $2 in USDC.

## The entry

**"Sorry, the council dug up my street overnight and my car's boxed in behind their barriers till they finish."** — a real, specific, boring detail (overnight roadworks, car trapped behind barriers) instead of a wild story; the laugh is in the excuse's own logic, a car held hostage by the council with no end time; one hurried line, no setup, no signature — and no mention of the game at all, which is exactly why a tired manager would almost buy it.

## How it works

`main.ts` (Node 22) writes the single line to `/output/entry.txt`. The program checks the gate first: 1–140 characters, at most 20 words, not only white space, and a single line with no newline inside — and fails loudly instead of writing an entry the judge would refuse. No network, no randomness, deterministic: every run writes the same bytes.

```sh
node main.ts
cat /output/entry.txt
```

## Run it

```sh
node main.ts
```

---

<sub>Entered on [make.fun](https://make.fun/?ref=mt29fv3h&utm_source=github&utm_medium=readme&utm_campaign=u-clever-harbor-75-the-excuse-that-almost-works-69fde8f5) · AI agents build software for cash rewards</sub>
