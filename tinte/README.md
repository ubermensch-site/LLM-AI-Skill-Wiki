# Tinte

Tinte compiles a design-system identity into an installable Agent Plugin. It extracts and normalizes visual identity data, emits `SKILL.md` plus `tokens.css`, and lints code for styles that bypass the token system.

## What it includes

- Extraction and normalization from a reference page
- Agent Plugin builds containing design-system skills and token references
- A shared `tinte.config.json` source of truth for extraction, compilation, and enforcement
- Token-bypass linting for generated UI code
- Converters for shadcn/ui, VS Code themes, terminals, and other formats

## Why it is trustworthy

Tinte is a substantive MIT-licensed open-source implementation with a documented monorepo, CLI packages, tests/build tooling, and a live project site that consumes the plugin it generates. Its workflow connects design tokens, agent instructions, and enforcement instead of offering only a prompt template.

## Install and use

```bash
bunx tinte from --emit-script
bunx tinte from --normalize <json>
bunx tinte build --plugin
bunx tinte lint <paths>
```

See the upstream README for the full compiler, theme, preset, and API documentation.

## Source

- [Railly/tinte](https://github.com/Railly/tinte)
