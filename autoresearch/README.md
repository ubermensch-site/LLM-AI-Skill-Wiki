# Autoresearch

An autonomous improvement and verification skill that turns a coding agent into a bounded iteration loop: define a goal and mechanical metric, make one focused change, verify it, keep improvements, and revert failures. It extends the approach popularized by Andrej Karpathy's `autoresearch` beyond model training to code, documentation, security, research, marketing, and other measurable tasks.

## Why it qualifies

- Authored and actively maintained by Udit Goenka, with substantial community traction (6k+ GitHub stars at discovery).
- MIT licensed and implemented as a real multi-agent-tool package with Claude Code, OpenCode, and Codex support, installers, guides, command files, and verification workflows.
- Includes explicit safety boundaries: bounded iteration defaults, read-before-write, mechanical checks, automatic rollback, git-based experiment history, and opt-in destructive actions.

## Highlights

- Core loop plus commands for planning, debugging, fixing, security audits, shipping, scenarios, prediction, documentation, reasoning, probing, evaluation, improvement, and regression gating.
- One-change-per-iteration workflow with TSV result tracking and automatic rollback.
- Claude Code hooks for privacy, dangerous-command, context, and scope guardrails.
- Cross-agent layouts and installers for Claude Code, OpenCode, and OpenAI Codex.

## Install

Claude Code or another compatible Agent Skills host:

```bash
npx skills add uditgoenka/autoresearch
```

For Claude Code marketplace installation:

```text
/plugin marketplace add uditgoenka/autoresearch
/plugin install autoresearch@autoresearch
```

## Source

[uditgoenka/autoresearch](https://github.com/uditgoenka/autoresearch)
