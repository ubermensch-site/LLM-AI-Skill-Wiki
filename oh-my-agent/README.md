# oh-my-agent

A cross-agent development team for Claude Code, Codex, Cursor, and other coding runtimes. It combines specialist roles, slash-command workflows, on-demand skills, persistent orchestration, and verification gates for software projects.

## What it includes

- 12 specialist roles spanning architecture, backend, frontend, mobile, databases, infrastructure, QA, debugging, refactoring, documentation, and research
- 20 workflows, including planning, implementation, review, debugging, security, and multi-agent orchestration
- 32 modular skills loaded on demand for areas such as APIs, UI, Terraform, CI, observability, and security
- Trigger-evaluation and stop-gate checks, regression-oriented workflows, and result artifacts for review

## Why it qualifies

The MIT-licensed project is distributed through npm, documents multiple agent runtimes, and includes a substantive skill/workflow catalog rather than a prompt-only collection. Its README documents verification corpora, safety boundaries, tests, and reproducible setup, with strong community traction.

## Install

```bash
curl -fsSL https://raw.githubusercontent.com/first-fluke/oh-my-agent/main/cli/install.sh | bash
```

For a single skill without the full team, use `bunx skills use first-fluke/oh-my-agent@oma-qa` (replace `oma-qa` with the skill you need). See the [upstream repository](https://github.com/first-fluke/oh-my-agent) for setup presets and workflow documentation.
