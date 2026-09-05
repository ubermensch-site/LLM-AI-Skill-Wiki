# Skills For Real Engineers (Matt Pocock)

"My agent skills that I use every day to do real engineering — not vibe coding." Built by Matt Pocock, a widely-known TypeScript educator (AI Hero / Total TypeScript) with ~60,000 newsletter subscribers.

## What it does

Splits into **user-invoked** skills (orchestration, run by typing a command) and **model-invoked** skills (reusable discipline, triggered automatically when relevant):

- `/grill-me`, `/grill-with-docs` — Socratic interview that aligns the agent with what you actually want before any code is written
- `/tdd` — red-green-refactor loop with strict discipline
- `/code-review` — parallel Standards + Spec review sub-agents
- `/triage`, `/to-spec`, `/to-tickets`, `/wayfinder` — turning conversations into tracked, ticketed work
- `/improve-codebase-architecture`, `domain-modeling`, `codebase-design` — fighting codebase entropy over time

## Install

```bash
# Claude Code (managed plugin, auto-updating)
claude plugins install mattpocock-skills

# Any agent (editable copy)
npx skills@latest add mattpocock/skills
```

Run `/setup-matt-pocock-skills` once per repo after installing.

## Why it's trusted

Authored by a **named, verifiable, well-known educator** in the TypeScript/engineering community with a large public following — not an anonymous or AI-generated collection.

## Source

https://github.com/mattpocock/skills
