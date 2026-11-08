# Tech Leads Club Agent Skills

A security-focused, cross-agent skill registry from Tech Leads Club. It packages verified and tested `SKILL.md` workflows for Claude Code, Cursor, Copilot, Cline, Gemini CLI, Codex, OpenCode, and other coding-agent harnesses, with a CLI, lockfiles, content hashing, audit logs, and an MCP server for progressive skill discovery.

## Why it qualifies

- 7k+ GitHub stars and active maintenance.
- Substantive TypeScript/Nx monorepo rather than a prompt-only dump.
- Documents a threat model and defense-in-depth installer safeguards.
- Skills are scanned with Snyk Agent Scan and released through CI.
- MIT-licensed software engine with explicit attribution for bundled skills.

## Highlights

- Catalog organized by development, cloud, automation, design, security, and other domains.
- Install, update, remove, cache, and audit skills with one CLI.
- Supports copy or symlink installs at project or global scope.
- MCP tools expose `list_skills`, `search_skills`, `read_skill`, and `fetch_skill_files`.

## Install

```bash
npx @tech-leads-club/agent-skills
```

Source: [tech-leads-club/agent-skills](https://github.com/tech-leads-club/agent-skills)
