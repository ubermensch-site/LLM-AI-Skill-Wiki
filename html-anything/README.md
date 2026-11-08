# HTML Anything

An open-source, local-first HTML editor built around 75 composable Agent Skills. It lets a logged-in coding-agent CLI turn drafts into polished HTML deliverables across web prototypes, marketing pages, decks, documents, social cards, data reports, and Hyperframes video/VFX surfaces.

## Why it qualifies

- 9k+ GitHub stars and active development from the team behind Open Design.
- Apache-2.0 licensed with a real Next.js application, browser tests, CI, and a documented security model.
- Implements the Claude Code `SKILL.md` convention with structured metadata, previews, and a searchable picker.
- Supports nine coding-agent CLIs while reusing existing local sessions; no extra API key is required.
- Includes a substantial set of concrete templates and references rather than generic prompt snippets.

## Highlights

- 75 skills grouped into prototype, deck, document, social, office, motion, and data-report workflows.
- Streaming render in a sandboxed iframe with one-click HTML and image export.
- Works with Claude Code, Codex, Cursor Agent, Gemini CLI, GitHub Copilot CLI, OpenCode, Qwen Coder, Aider, and IBM Bob.
- Bundles source attribution for upstream skills and keeps each template in its own folder.

## Install

```bash
git clone https://github.com/nexu-io/html-anything
cd html-anything
pnpm install
pnpm -F @html-anything/next dev
```

Source: [nexu-io/html-anything](https://github.com/nexu-io/html-anything)
