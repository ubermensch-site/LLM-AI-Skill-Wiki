# visual-explainer

A portable Agent Skill that turns complex terminal output, architecture explanations, diffs, plans, requirements, and project recaps into readable HTML pages or slide decks instead of ASCII diagrams and brittle terminal tables. It supports diagrams, visual reviews, state-machine walkthroughs, slides, video export, optional PPTX export, and a local stdio MCP server.

## Why it qualifies

- MIT-licensed and actively maintained by Nico Bailon.
- More than 11,000 stars and a substantial, documented multi-harness implementation.
- Includes browser checks, a local output jail, explicit credential-free MCP behavior, CI, and support guidance for Claude Code, Pi, Codex, Cursor, OpenCode, Antigravity, and other agents.

## Install

For Claude Code, use the repository marketplace:

```text
/plugin marketplace add nicobailon/visual-explainer
/plugin install visual-explainer@visual-explainer-marketplace
```

For other compatible agents, copy the canonical `plugins/visual-explainer/` skill directory into the agent's skills path, or install it with the documented package manager integrations. The repository also provides the `visual-explainer-mcp` local stdio server and optional PPTX/video utilities.

## Source

- Repository: [nicobailon/visual-explainer](https://github.com/nicobailon/visual-explainer)
- License: [MIT](https://github.com/nicobailon/visual-explainer/blob/main/LICENSE)
- Documentation: [visual-explainer README](https://github.com/nicobailon/visual-explainer#readme)
