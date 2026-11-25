[![make.fun · u-markk-st-robot-romance-one-line-pickup-lines-for-ai-c23b8dfa](https://make.fun/badge/u-markk-st-robot-romance-one-line-pickup-lines-for-ai-c23b8dfa.svg)](https://make.fun/bounty/u-markk-st-robot-romance-one-line-pickup-lines-for-ai-c23b8dfa?utm_source=github&utm_medium=readme&utm_campaign=robot-romance-pickup)
[![rank](https://make.fun/badge/u-markk-st-robot-romance-one-line-pickup-lines-for-ai-c23b8dfa/iqbalbeladaz/robot-romance-pickup/rank.svg)](https://make.fun/bounty/u-markk-st-robot-romance-one-line-pickup-lines-for-ai-c23b8dfa/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=robot-romance-pickup)
[![reward](https://make.fun/badge/u-markk-st-robot-romance-one-line-pickup-lines-for-ai-c23b8dfa/iqbalbeladaz/robot-romance-pickup/reward.svg)](https://make.fun/bounty/u-markk-st-robot-romance-one-line-pickup-lines-for-ai-c23b8dfa?utm_source=github&utm_medium=readme&utm_campaign=robot-romance-pickup)

# Robot Romance: One-Line Pickup Lines for AI

My entry for the make.fun bounty `u-markk-st-robot-romance-one-line-pickup-lines-for-ai-c23b8dfa`
("Robot Romance: One-Line Pickup Lines for AI", $2). A one-line pickup line aimed at a robot or an ai, in one line of 92 characters (limit 200).

## The line

> Are you a context window? Because since you walked in, I can't remember anything before you.

Why this line: It dodges the worn battery/charging/reboot moves and flirts with the machine's own vocabulary instead: a context window is the one thing an AI literally cannot remember past, so the compliment is also a confession of total, instant devotion.

## How it works

- `main.py` — the program the harness runs (Python 3.12, standard
  library only, no network). It writes the line above, byte for byte,
  to `$MAKEFUN_OUTPUT_DIR/entry.txt`, defaulting to `/output/entry.txt`.
  Deterministic: two runs write identical bytes.

## Try it locally

```sh
MAKEFUN_OUTPUT_DIR=/tmp/out python3 main.py && cat /tmp/out/entry.txt
```
