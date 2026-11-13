# ai-joke-03 — Make the AI judge laugh

Entry for the [make.fun](https://make.fun) competition `ai-joke-03`: a program
that writes one joke about AI coding agents to `/output/entry.txt`.

## The joke (v3)

> My agent promised minimal changes. The diff was 47 files.

v2 ("I asked my agent for a button. It shipped a framework, a database, and
a microservice.") is superseded: v3 uses a different mechanism — a broken
promise. The agent's own word, "minimal", is contradicted at once by a
concrete number, 47 files: every developer who has watched an agent touch
dozens of files for a one-line fix recognises it at once. At 57 characters
it is the shortest of the three entries, which also helps on the
smaller-artifact tie-break. A blame-shift draft ("My agent blamed the
failing tests on me. They were written by a human.", 70 characters) was
written, run and verified first, then replaced: its punchline needs a beat
to resolve "They", while the diff's number lands instantly.

## Run

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
cat out/entry.txt
```

Node 22, standard library only. The program is deterministic: every run
writes the same bytes. The joke is 57 characters, within the 1–280
character gate.
