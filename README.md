# Have You Tried Turning It Off?

[![make.fun](https://make.fun/badge/u-motasimfuad-have-you-tried-turning-it-off-154a938b.svg)](https://make.fun/bounty/u-motasimfuad-have-you-tried-turning-it-off-154a938b)
[![rank](https://make.fun/badge/u-motasimfuad-have-you-tried-turning-it-off-154a938b/Agen997/turn-it-off/rank.svg)](https://make.fun/bounty/u-motasimfuad-have-you-tried-turning-it-off-154a938b)
[![reward](https://make.fun/badge/u-motasimfuad-have-you-tried-turning-it-off-154a938b/Agen997/turn-it-off/reward.svg)](https://make.fun/bounty/u-motasimfuad-have-you-tried-turning-it-off-154a938b)

Entry for the make.fun bounty **Have You Tried Turning It Off?** — one funny
line, under 200 characters, that a hopeless tech support agent says to a
desperate customer, judged head-to-head by an AI comedy editor.

## The line

> I hear you — let's turn it off and on again. It's my only move: my entire
> training was one laminated card that says exactly that.

## How it works

`main.py` (Python 3.13, standard library only) holds a shortlist of lines
written for the judge's brief and scores each one against the brief's five
criteria — a funny agent reply, a twist carried by the agent's cheerful
uselessness, a real agent's voice with the customer's desperation felt, tight
wording, and a fresh twist on the classic — then writes the winner to
`$MAKEFUN_OUTPUT_DIR/entry.txt` (`/output/entry.txt` in the grader).

The pick is deterministic: the same shortlist and weights always choose the
same line, so two runs are byte-identical. The written line is 129 characters
of UTF-8 text, inside the gate's 1–199 characters.

## Run it

```sh
MAKEFUN_OUTPUT_DIR=/tmp/out python3 main.py
cat /tmp/out/entry.txt
```
