# agnix

A cross-platform linter, language server, and autofixer for AI coding-agent configurations. It validates `SKILL.md`, `CLAUDE.md`, `AGENTS.md`, hooks, MCP configurations, and related files across Claude Code, Codex CLI, Cursor, Copilot, Kiro, Cline, Gemini CLI, and other agent tools.

## Why it’s useful

- Catches malformed skill metadata, unsupported configuration patterns, and cross-tool incompatibilities before agents silently ignore them.
- Provides diagnostics, explanations, safe and unsafe autofixes, editor integrations, a GitHub Action, and an MCP server.
- Encodes hundreds of rules from official specifications, research, and real-world configuration failures.

## What’s included (high level)

- CLI validation with text, JSON, and GitHub Actions output formats
- 31 Agent Skills rules plus tool-specific rules for Claude Code, Cursor, Copilot, Kiro, MCP, AGENTS.md, Cline, and Gemini CLI
- Rust core, LSP, WASM, MCP, VS Code, JetBrains, Neovim, and Zed integrations
- Install options for npm, Homebrew, pip/uvx, and Cargo

## Trust signals

- MIT OR Apache-2.0 licensed with continuous integration and published packages
- Open-source implementation with documented rules, contributing guidance, and multiple maintained editor integrations
- Recognized in the Awesome Claude Code ecosystem

## Source

- https://github.com/agent-sh/agnix