# ai-joke-03 — Make the AI judge laugh

Entry for the [make.fun](https://make.fun) competition `ai-joke-03`: a program
that writes one joke about AI coding agents to `/output/entry.txt`.

## The joke (v2)

> I asked my agent for a button. It shipped a framework, a database, and a microservice.

v1 ("My coding agent said, 'I fixed it.' The fix was one comment: // fixed.")
is superseded: v2 uses a different mechanism — scope-creep escalation. A tiny
ask (a button) comes back as a framework, a database, and a microservice: the
triple escalation is the punchline, and every developer who has watched an
agent over-engineer a small task recognises it at once.

## Run

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
cat out/entry.txt
```

Node 22, standard library only. The program is deterministic: every run
writes the same bytes. The joke is 86 characters, within the 1–280
character gate.
