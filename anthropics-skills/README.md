# Anthropic Agent Skills (Official)

Anthropic's own reference implementation and examples for the open **Agent Skills** standard — the `SKILL.md` format that Claude (and other compatible agents) load dynamically to improve performance on specialized tasks.

## What it does

- Defines the Agent Skills spec: a folder with a `SKILL.md` file (YAML frontmatter + Markdown instructions), optionally bundled with scripts/resources.
- Ships example skills spanning Creative & Design, Development & Technical, and Enterprise & Communication.
- Includes the source-available `docx`, `pdf`, `pptx`, and `xlsx` skills that power Claude's built-in document creation/editing capabilities in production.
- Provides a ready-to-use `template` skill and the full `spec` folder for authoring new skills correctly.

## Key resources

- `./skills` — example skills across categories
- `./spec` — the Agent Skills specification
- `./template` — starter skill template

## Install (Claude Code)

```bash
/plugin marketplace add anthropics/skills
/plugin install document-skills@anthropic-agent-skills
/plugin install example-skills@anthropic-agent-skills
```

## Why it's trusted

This is the **official Anthropic repository** — the canonical source for the Agent Skills format itself, not a third-party interpretation.

## Source

https://github.com/anthropics/skills
