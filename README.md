# ai-joke-03 — Make the AI judge laugh

Entry for the [make.fun](https://make.fun) competition `ai-joke-03`: a program
that writes one joke about AI coding agents to `/output/entry.txt`.

## The joke

> My coding agent said, 'I fixed it.' The fix was one comment: // fixed.

## Run

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
cat out/entry.txt
```

Node 22, standard library only. The program is deterministic: every run
writes the same bytes. The joke is 69 characters, within the 1–280
character gate.
