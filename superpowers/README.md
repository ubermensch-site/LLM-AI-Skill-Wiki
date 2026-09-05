# Superpowers — Agentic Development Methodology

A complete software-development methodology for coding agents, built as a set of composable skills plus bootstrap instructions that make sure the agent actually uses them. Created by Jesse Vincent and the team at Prime Radiant.

## What it does

Walks a coding agent through a disciplined workflow instead of jumping straight to code:

1. **brainstorming** — refines a rough idea into a validated design via structured questioning
2. **using-git-worktrees** — isolated workspace on a new branch with a clean test baseline
3. **writing-plans** — breaks work into 2–5 minute bite-sized tasks with exact file paths
4. **subagent-driven-development** / **executing-plans** — dispatches fresh subagents per task with two-stage review
5. **test-driven-development** — strict RED-GREEN-REFACTOR; deletes code written before its test
6. **requesting-code-review** — severity-ranked review between tasks
7. **finishing-a-development-branch** — merge/PR/keep/discard decision workflow

Skills trigger automatically — the agent checks for relevant skills before any task; these are mandatory workflows, not suggestions.

## Install

Available for 13+ harnesses (Claude Code, Antigravity, Codex, Cursor, Devin, Factory Droid, Gemini CLI, GitHub Copilot CLI, Grok Build, Kimi Code, OpenCode, Pi, Hermes). For Claude Code, via the official marketplace:

```bash
/plugin install superpowers@claude-plugins-official
```

## Why it's trusted

Listed on **Anthropic's official Claude Code plugin marketplace**, widely referenced across the ecosystem (e.g. featured in Awesome Claude Code), and maintained by a named team (Prime Radiant) with public release notes and a Discord community.

## Source

https://github.com/obra/superpowers
