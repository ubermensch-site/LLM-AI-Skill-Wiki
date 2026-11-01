# Context Mode

Context Mode is an MCP server and multi-agent plugin that reduces context pressure by routing large tool output through sandboxed execution, searchable local storage, compression, and progressive disclosure. It is designed for Claude Code and a broad set of agent clients, with hooks that enforce routing, preserve session continuity, and expose diagnostics such as context savings and health checks.

## Why it qualifies

- 33,000+ GitHub stars and active maintenance as of this review, with strong community adoption and an active npm distribution.
- Substantive implementation with 11 MCP tools, platform adapters, hooks, tests, security documentation, and privacy-focused local storage.
- Solves a core agent-tooling problem rather than serving as a prompt-only skill: raw tool results are sandboxed and queried through a compact interface.
- Documents its source-available Elastic License 2.0 clearly; review that license before redistribution or hosted use.

## Key capabilities

- Batch execution, structured extraction, search, indexing, and compressed tool-result retrieval.
- Automatic routing through lifecycle hooks on supported agent platforms, plus an MCP-only installation path.
- Session continuity, compaction snapshots, diagnostics, and context-usage reporting.
- Project-boundary containment, network-fetch hardening, and explicit privacy/security guidance.

## Install

For Claude Code, the upstream project documents:

```text
/plugin install context-mode@context-mode
```

An MCP-only path is also available:

```bash
claude mcp add context-mode -- npx -y context-mode
```

## Source

- Original repository: https://github.com/mksglu/context-mode
- npm package: https://www.npmjs.com/package/context-mode

Context Mode is licensed under Elastic License 2.0. Prefer the upstream documentation for current client compatibility, configuration, and license terms.
