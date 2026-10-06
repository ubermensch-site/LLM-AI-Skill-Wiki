# answer-me-with-html

## What it is

**Answer me with HTML** is an Agent Skill + bundled CLI that turns an agent’s *short Markdown draft* into a polished, offline, single-file HTML page (and optionally explainer-video pages) — so the model outputs content, not hundreds of lines of CSS/SVG.

Source repo: https://github.com/QingYunA/answer-me-with-html

## Why it’s worth adding

- **High-signal skill (not a prompt dump):** the repo ships a real CLI that handles layout, themes, and diagram rendering.
- **Token/time efficient:** designed to dramatically reduce output tokens vs. having the model hand-write HTML/CSS.
- **Broad compatibility:** works with Claude Code, Codex, Cursor, and other agent harnesses.
- **Good engineering hygiene:** MIT license + CI.

## What it does

- Renders readable one-page HTML answers with computed layouts (cards/panels) and multiple themes.
- Supports diagram components (sequence, flow, tree, timeline) rendered by the CLI.
- Optional “always-on mode” rule to render a page for every conclusion/plan/comparison.
- Can generate explainer-video pages via `am video` (optionally exporting MP4 when run locally).
