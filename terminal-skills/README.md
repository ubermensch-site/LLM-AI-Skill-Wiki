# Terminal Skills

Terminal Skills is an open-source catalog of portable `SKILL.md` files for Claude Code, OpenAI Codex, Gemini CLI, Cursor, and other Agent Skills-compatible tools. It includes practical development, DevOps, automation, data, security, documentation, and MCP-building workflows, plus hosted routing tools that can find the right skill for a task.

## Why it qualifies

- Maintained public catalog with real installation tooling, use-case guides, and an MCP server.
- Follows the open Agent Skills standard instead of targeting a single proprietary harness.
- Apache-2.0 licensed with a broad, structured set of documented skills.
- Includes practical skills such as PDF analysis, Excel processing, code review, API testing, security audit, data validation, and prompt testing.

## Key features

- Standalone skills that can be installed individually.
- Cross-agent support for Claude Code, Codex, Gemini CLI, Cursor, and similar tools.
- Optional hosted MCP routing with `search_skills`, `get_skill`, and `plan_task`.
- Use-case documentation for common workflows and contribution guidance.

## Install

```bash
npx terminal-skills install pdf-analyzer
```

Replace `pdf-analyzer` with a skill from the catalog. The upstream README also documents direct installation for each supported agent and MCP setup.

## Source

- Original repository: [TerminalSkills/skills](https://github.com/TerminalSkills/skills)
- Catalog: [terminalskills.io](https://terminalskills.io)
- License: Apache-2.0
