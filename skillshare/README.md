# skillshare

A cross-agent skills and configuration manager that keeps one local source of truth and syncs selected skills, agents, rules, MCP connections, hooks, and plugins to Claude Code, Codex, OpenCode, Pi, and other agent tools. It includes project-local mode, copy/symlink targets, a web dashboard, GitHub Actions support, and a built-in security audit before installation or updates.

## Why it is trustworthy

The project is MIT-licensed, has a substantial Go implementation with tests and release tooling, publishes cross-platform installers, and documents its sync and audit behavior in detail. Its sustained community traction makes it a useful infrastructure companion for managing—not blindly redistributing—skills.

## Install

```sh
curl -fsSL https://raw.githubusercontent.com/runkids/skillshare/main/install.sh | sh
skillshare init
skillshare sync
```

Use `skillshare audit` to review skills before they reach an agent. Homebrew, Nix, Windows, and desktop-app installation options are also documented upstream.

## Source

[runkids/skillshare](https://github.com/runkids/skillshare)
