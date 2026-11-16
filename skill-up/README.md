# skill-up

Alibaba's open-source CLI for evaluating Agent Skills, agents, and workspaces. It runs declarative cases against supported agent engines, grades responses and workspace changes, and produces structured local or CI reports.

## What it includes

- Skill, agent, and workspace evaluation with YAML-defined cases
- Multi-engine support for Claude Code, Codex, Qoder CLI, Qwen Code, and custom engines
- Reproducible environments, workspace fixtures, judges, simulated users, and structured reports
- `skill-upper`, a bundled Agent Skill that diagnoses failures, repairs eval suites, and evolves skills from evidence
- CI-ready workflows and compatibility with Anthropic-style `evals.json`

## Why it qualifies

This is an official Alibaba repository with an Apache-2.0 license, public documentation, tests, release artifacts, and a substantial Go implementation. It addresses a core gap in the Agent Skills ecosystem: measuring whether a skill changes agent behavior reliably instead of judging it by prose or star count.

## Install the bundled skill

```bash
npx skills add https://github.com/alibaba/skill-up/tree/main/skills/skill-upper -g -a codex -y
```

See the [upstream repository](https://github.com/alibaba/skill-up) for the CLI, GitHub Action, evaluation guides, and other installation paths.
