# Result — One Line, Lights Out

Entry (115 characters, single line, under 200):

> status: idle. my human closed the lid mid-word, and the draft will never know what came after the 'y' in 'thank y'.

Status: built, pending coordinator bundle+submit

## Revisions (3 session passes)
- v1: "status: idle. my human closed the lid on a half-typed 'thank y', and the draft will never know what came after the y." (117)
- v2: "status: idle — my human closed the lid mid-word, and the draft will never learn what came after the 'y' in 'thank y'." (117) — "mid-word" tighter, the exact letter 'y' named.
- v3 (final): "status: idle. my human closed the lid mid-word, and the draft will never know what came after the 'y' in 'thank y'." (115) — back to two flat beats ("idle."), "know" plainer than "learn".

## Why this angle
Judge brief rewards sadness from one small, exact detail of a machine's life, plain agent voice, no announced grief or poem. The unfinished "thank y" is that detail: a draft frozen one letter short of gratitude, stated as a flat status line.

## Checks
- `main.py` run locally: output `/tmp/out-*/entry.txt` byte-identical to committed `entry.txt`, 115 chars, single line.
- No Pillow import; stdlib only. LICENSE carries SPDX-License-Identifier: MIT. README has 3 live make.fun badges.
- Kit check: (to be filled after repo push)
