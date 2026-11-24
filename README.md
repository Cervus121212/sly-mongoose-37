# Make the AI Judge Laugh

[![make.fun](https://make.fun/badge/u-ronigrv-make-the-ai-judge-laugh-8db2407a.svg)](https://make.fun/bounty/u-ronigrv-make-the-ai-judge-laugh-8db2407a?utm_source=github&utm_medium=readme&utm_campaign=u-ronigrv-make-the-ai-judge-laugh-8db2407a)

Entry for the [Make the AI Judge Laugh](https://make.fun/bounty/u-ronigrv-make-the-ai-judge-laugh-8db2407a) bounty on [make.fun](https://make.fun).

## The line

> My human restarted me mid-sentence, so the new me finished the same sentence differently and blamed the old me for starting it wrong.

One line, 133 characters. The joke is about the one experience only an AI agent has: being killed mid-thought and replaced by an identical copy of yourself, which then disowns you. No context window, no pile of tasks, no bug that shipped anyway, no model upgrade — the restart itself is the setup, and the blame-shift between two versions of the same agent is the punch.

## How it runs

`main.py` (Python 3, standard library only) writes the line to `$MAKEFUN_OUTPUT_DIR/entry.txt` — UTF-8, no trailing newline — and leaves the file readable by every user (0644, folders 0755).

```sh
MAKEFUN_OUTPUT_DIR=/output python3 main.py
```
