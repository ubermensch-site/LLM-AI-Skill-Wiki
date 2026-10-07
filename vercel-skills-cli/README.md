# Vercel Skills CLI

## Summary

[Vercel Labs' skills](https://github.com/vercel-labs/skills) is the open agent-skills ecosystem CLI, not a standalone prompt collection. It discovers, installs, uses, updates, and removes SKILL.md-based skills across Claude Code, Codex, Cursor, OpenCode, and many other coding agents.

## Key capabilities

- Discover skills from Git repositories, local folders, direct downloads, and plugin manifests.
- Install selected skills per project or globally, using symlinks or copies.
- Search via `skills find`, use a skill without permanent installation via `skills use`, and manage installed skills with list/update/remove commands.
- Initialize new SKILL.md templates and support existing Git/SSH authentication for private repositories.

## Why it qualified

- Official Vercel Labs repository, MIT-licensed, with a published npm CLI and a substantive TypeScript implementation and test scripts.
- Approximately 33,302 stars and 2,849 forks when reviewed on 2026-10-07; traction is corroborated by active implementation work, not used as the sole quality signal.
- Changes after the previous wiki run include programmatic installation primitives, source-based removal, and a Codex global-path fix.

## Use

Examples copied from the upstream README:

```bash
# Discover available skills before installing
npx skills add vercel-labs/agent-skills --list

# Install a collection
npx skills add vercel-labs/agent-skills

# Search the ecosystem
npx skills find typescript
```

These commands install/use skills from the example collection; the indexed repository provides the CLI. Review any selected skill before granting it tool access. The CLI documents anonymous telemetry; set `DISABLE_TELEMETRY=1` or `DO_NOT_TRACK=1` to opt out.

## Source

- Repository and current documentation: https://github.com/vercel-labs/skills
- Reviewed implementation snapshot: https://github.com/vercel-labs/skills/tree/48dc9e8eb8aa19040e91cb90ba0b642c9cbad57e
