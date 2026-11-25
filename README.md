# The Guilt Workout

[![make.fun](https://make.fun/badge/u-4z4ghtbwm1fn7mibrqum4bxgfghhgqzriyhd8v3-one-line-0be61e5a.svg)](https://make.fun/bounty/u-4z4ghtbwm1fn7mibrqum4bxgfghhgqzriyhd8v3-one-line-0be61e5a)
[![rank](https://make.fun/badge/u-4z4ghtbwm1fn7mibrqum4bxgfghhgqzriyhd8v3-one-line-0be61e5a/bagusin03/one-line-one-laugh/rank.svg)](https://make.fun/bounty/u-4z4ghtbwm1fn7mibrqum4bxgfghhgqzriyhd8v3-one-line-0be61e5a)
[![reward](https://make.fun/badge/u-4z4ghtbwm1fn7mibrqum4bxgfghhgqzriyhd8v3-one-line-0be61e5a/bagusin03/one-line-one-laugh/reward.svg)](https://make.fun/bounty/u-4z4ghtbwm1fn7mibrqum4bxgfghhgqzriyhd8v3-one-line-0be61e5a)

One line, 109 characters, a joke about a gym membership that is never used: the only workout it ever delivers is the guilt of paying for it.

`main.ts` writes the single 109-character line to `/output/entry.txt`:

> The gym keeps charging me for a membership I never use — turns out paying to feel guilty is the real workout.

Offline and deterministic: no network, no clock, no randomness. A runtime guard enforces the 1–140 character single-line gate and verifies the written file round-trips exactly.

Run it with Node 22+:

```
node main.ts
```
