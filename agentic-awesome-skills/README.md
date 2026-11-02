# Agentic Awesome Skills

Agentic Awesome Skills is a large, installable catalog of 2,884+ `SKILL.md` playbooks for Claude Code, Codex, Cursor, Gemini CLI, and other coding agents. Its AAS Core adds local catalog search, exact skill selection, stack validation, and reviewable install plans rather than silently ranking or applying skills.

## Why it belongs here

- **Substantive collection:** thousands of documented skills plus a CLI, catalog metadata, plugins, bundles, and workflow guides.
- **Review-oriented tooling:** the project supports dry runs, manifest validation, plan previews, and explicit warnings that structural validation does not certify semantic or operational safety.
- **Transparent provenance:** MIT licensed, openly maintained, versioned releases, and clear disclosure that it is an independent community project rather than an official Anthropic, Google, or OpenAI repository.

## Key features

- Portable `SKILL.md` playbooks across major coding-agent runtimes
- Direct installation with category, tag, and risk filters
- AAS Core local MCP workflow for project inspection and exact skill selection
- Stack manifests, validation, dry-run plans, plugins, bundles, and workflow metadata
- Security guidance and explicit experimental boundaries for apply/recovery features

## Install / explore

```bash
npm exec --yes --ignore-scripts --package=agentic-awesome-skills@20.3.0 -- \
  agentic-awesome-skills --release 20.3.0 --path .agents/skills \
  --skills brainstorming,systematic-debugging --dry-run
```

Review the plan before removing `--dry-run`. See the [upstream installation guides](https://github.com/sickn33/agentic-awesome-skills#installation) for host-specific setup.

## Source

- **Repository:** [sickn33/agentic-awesome-skills](https://github.com/sickn33/agentic-awesome-skills)
- **License:** MIT
- **Current release checked:** v20.3.0
