# Agentic Resource Registry

A self-hosted Apache-2.0 registry and governance platform for coding-agent resources. It centralizes skills, agents, MCP clients, hooks, prompts, and sandboxes, with reviewable releases, version diffs, cross-harness installation, usage insights, session replay, and Agentic Resource Discovery (ARD) plus A2A delegation.

## Why it qualifies

- 4k+ GitHub stars and a substantial open-source server, web UI, CLI, and deployment stack.
- Apache-2.0 licensed with documented production deployment, security, backups, release verification, and audit logging.
- Supports Claude Code, Codex, Cursor, Copilot, Kiro, Pi, OpenCode, Antigravity, and other harnesses.
- Treats skills as governed, versioned resources with approvals, visibility, provenance, and traceable usage instead of an unmoderated prompt marketplace.
- Provides a concrete enterprise workflow for discovering, reviewing, installing, and delegating agent resources.

## Highlights

- Self-hosted registry with teamspaces, RBAC, review gates, version diffs, and audit logs.
- `observal` CLI for login, discovery, installation, diagnostics, telemetry, and delegation.
- ARD manifests and search plus bounded A2A tasks between approved agents.
- Session traces and AI-powered insights for debugging, auditing, and measuring adoption.

## Install

Deploy the server:

```bash
curl -fsSL https://raw.githubusercontent.com/AgenticResourceRegistry/AgenticResourceRegistry/main/install-server.sh | bash
```

Install the CLI:

```bash
uv tool install observal-cli
```

Source: [AgenticResourceRegistry/AgenticResourceRegistry](https://github.com/AgenticResourceRegistry/AgenticResourceRegistry)
