# Agentic Plugin Marketplace (wshobson/agents)

Production-ready agentic workflow building blocks: 94 plugins, 202 agents, 183 skills, and 105 slash commands — built for Claude Code and shipped natively to OpenAI Codex CLI, Cursor, OpenCode, the Antigravity CLI, and GitHub Copilot from one Markdown source.

## What it does

- Each plugin is isolated and composable (agents/commands/skills auto-discovered per plugin directory); installing one loads only its components into context
- Tiered model strategy: premium models for long-horizon/architecture work, faster models for docs/ops/SEO tasks
- Ships to 5 harnesses from one source-of-truth via harness-native adapters (not lowest-common-denominator translation)
- Includes `plugin-eval`, a 3-layer quality framework: static structural checks, LLM-judge semantic scoring, and Monte Carlo reliability testing (50-100 simulated runs)
- 16 multi-agent orchestrators for full-stack, security, ML, and incident-response workflows

## Install (Claude Code)

```bash
/plugin marketplace add wshobson/agents
/plugin install python-development   # or any of the 94 plugins
```

Skills-only install (any agent): `gh skill install wshobson/agents` or `npx skills add wshobson/agents`.

## Why it's trusted

Large, actively maintained marketplace with a **formal, published quality-evaluation framework** (plugin-eval) rather than unaudited crowd-sourced submissions, plus a documented cross-harness capability matrix.

## Source

https://github.com/wshobson/agents
