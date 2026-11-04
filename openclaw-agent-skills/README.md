# OpenClaw Agent Skills

Canonical shared workflow skills for OpenClaw projects, including review closeout, behavior validation, remote/CI-parity checks, handoffs, session viewing, and README conventions. Each reusable workflow is a portable `SKILL.md`, with installer and validation tooling.

## Why it is trustworthy

This is the public canonical repository maintained by the OpenClaw organization. It documents admission boundaries, keeps repo-specific skills with their source projects, includes validation/tests, and publishes an MIT-licensed implementation rather than a prompt-only collection.

## Install

```sh
git clone https://github.com/openclaw/agent-skills.git
cd agent-skills
scripts/install-skills --list
scripts/install-skills
```

For Codex or Claude Code, the repository also documents symlink-based installs into `~/.codex/skills` or `~/.claude/skills`.

## Source

[openclaw/agent-skills](https://github.com/openclaw/agent-skills)
