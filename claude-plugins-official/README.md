# Claude Code Official Plugins

## Summary

[Anthropic's official Claude Code plugin directory](https://github.com/anthropics/claude-plugins-official) is a curated marketplace of skills, agents, commands, hooks, MCP integrations, and language-server tooling. It complements the separately indexed `anthropics/skills` reference collection: this repository packages and distributes working Claude Code plugins.

## Key capabilities

- Internal plugins developed and maintained by Anthropic, including frontend design, skill creation, plugin development, code review, and security guidance.
- External plugins from partners and the community, subject to the directory's quality and security approval process.
- Standard plugin layout with manifests and optional skills, commands, agents, and MCP configuration.
- Skill-bundle entries can expose selected `SKILL.md` directories without requiring a plugin manifest in the source repository.

## Why it qualified

- Official Anthropic-managed repository with clearly distinguished internal and external sources.
- Approximately 37,516 stars and 4,224 forks when reviewed on 2026-10-08; trust is grounded in provenance, inspected content, and maintenance rather than star count alone.
- Inspected the directory README, internal plugin inventory, and the substantive `frontend-design` skill, which provides brief-specific design planning, critique, accessibility, and implementation guidance.
- Commits since the previous wiki run include a security-guidance fix preventing killed hooks from filling disk and an updated Figma plugin.

## Install / use

Inside Claude Code, install a selected plugin using the upstream command pattern:

```text
/plugin install {plugin-name}@claude-plugins-official
```

For example:

```text
/plugin install frontend-design@claude-plugins-official
```

Alternatively, browse `/plugin > Discover`. Review each plugin's homepage, permissions, dependencies, and license before installing. Anthropic explicitly warns that directory inclusion does not guarantee the safety or behavior of bundled MCP servers or other software. Licensing is per linked plugin, not a blanket repository-wide grant.

## Source

- Repository and current documentation: https://github.com/anthropics/claude-plugins-official
- Reviewed snapshot: https://github.com/anthropics/claude-plugins-official/tree/b78ac49cdc6b3d7b61c4439470e311f4291265b1
- Inspected skill: https://github.com/anthropics/claude-plugins-official/blob/b78ac49cdc6b3d7b61c4439470e311f4291265b1/plugins/frontend-design/skills/frontend-design/SKILL.md
