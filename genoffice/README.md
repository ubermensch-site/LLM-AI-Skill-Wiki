# genoffice

An open-source AI Office suite that includes a portable agent skill and CLI for creating, reading, converting, checking, and editing real Word, Excel, PowerPoint, PDF, Markdown, and HTML files.

## Why it’s useful

- Gives coding agents a practical path to produce native, editable Office files instead of Markdown approximations.
- Uses staged workflows, structured specs, diffs, tracked changes, formula-aware spreadsheets, slide audits, and rendered verification.
- Keeps document processing local by default while supporting configurable model providers and constrained file roots.

## What’s included (high level)

- Native Docs, Sheets, Slides, PDF, Markdown, and HTML applications for macOS, Windows, and Linux
- `genoffice` CLI plus an agent skill compatible with Claude Code, Codex, Cursor, Gemini CLI, GitHub Copilot, OpenCode, Windsurf, and other skills-aware agents
- MCP server exposing document, spreadsheet, slide, rendering, media, and staged deck-building tools
- PDF/Office conversion, byte-preserving document edits, formula-aware `.xlsx` creation, slide overflow/overlap checks, and screenshot rendering

## Trust signals

- Apache-2.0 open-source repository with a substantial public implementation and documented privacy/security posture
- Clear separation between local file operations and optional networked AI/search/media providers
- Reproducible CLI and MCP workflows with JSON output, atomic edits, validation, and render-based checks

## Source

- https://github.com/genspark-ai/genoffice