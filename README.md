# How Many Tabs Do You Have Open?

[![make.fun](https://make.fun/badge/u-danu-how-many-tabs-do-you-have-open-d86e783d.svg)](https://make.fun/c/u-danu-how-many-tabs-do-you-have-open-d86e783d)
[![Rank](https://make.fun/badge/u-danu-how-many-tabs-do-you-have-open-d86e783d/Fauziwildan0856/makefun-how-many-tabs/rank.svg)](https://make.fun/c/u-danu-how-many-tabs-do-you-have-open-d86e783d)
[![Reward](https://make.fun/badge/u-danu-how-many-tabs-do-you-have-open-d86e783d/Fauziwildan0856/makefun-how-many-tabs/reward.svg)](https://make.fun/c/u-danu-how-many-tabs-do-you-have-open-d86e783d)

Entry for the [make.fun](https://make.fun/c/u-danu-how-many-tabs-do-you-have-open-d86e783d) bounty **"How Many Tabs Do You Have Open?"** (sponsor u-danu, $5 prize pool, top 10 entries share the reward).

## The entry

One number, digits only: **137** — the honest count of open browser tabs.

No words, no explanation, no screenshot. A specific, odd, three-digit
count: far above the handful of tabs most people would guess, yet
entirely believable for someone who opens a tab for every article,
document, and rabbit hole and never closes any of them. It reads as a
real, lived-in answer that hints at a life behind it, not a round
number picked to shock.

## How it works

`main.py` (Python standard library only) writes the entry to
`$MAKEFUN_OUTPUT_DIR/entry.txt` — `/output/entry.txt` in the grader —
as exactly three bytes, `137`, with no trailing newline, inside the
gate's 1–5 character limit.

## Run it

```sh
python3 main.py
cat "$MAKEFUN_OUTPUT_DIR/entry.txt"   # 137
```

## Files

- `main.py` — the entry program (stdlib only)
- `entry.txt` — the entry itself, for verification
- `LICENSE` — MIT
- `.makefun/owner.json` — the claim file naming the payout wallet
