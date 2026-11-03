# Archify

Archify is a source-aware Agent Skill and open-source CLI for turning descriptions or repositories into interactive architecture, workflow, sequence, data-flow, ERD, timeline, and other diagrams. It produces standalone HTML artifacts, keeps typed JSON source, and validates schema, layout, routes, and delivery before replacing the last known-good output.

## Why it qualifies

- Strong community traction with 90k+ GitHub stars and 130k+ reported skill installs.
- Apache-2.0 licensed with extensive documentation, checked-in examples, and reproducible validation tooling.
- Supports Claude Code, Codex CLI, Cursor, OpenCode, and other SKILL.md-compatible agents.
- Explicitly separates authored facts from inferred topology and supports commit-pinned source evidence.

## Key features

- Ten diagram modes including architecture, workflow, sequence, data flow, lifecycle, ERD, class, tree, timeline, and waterfall.
- Standalone HTML output with interactive focus, route tracing, themes, and image/PDF exports.
- JSON schemas, deterministic layout, diagnostics, and atomic last-good delivery.
- Optional repository analysis with source excerpts pinned to a public commit.

## Install

```text
Install Archify for me by reading https://raw.githubusercontent.com/tt-a1i/archify/main/llms.txt
```

Or install the skill explicitly with the skills CLI:

```bash
npx -y skills@latest add https://archify.si --skill archify --agent claude-code --global --copy --yes
```

## Source

- Original repository: [tt-a1i/archify](https://github.com/tt-a1i/archify)
- Website and examples: [archify.si](https://archify.si)
- License: Apache-2.0
