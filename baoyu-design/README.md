# baoyu-design

Baoyu Design is a substantial local-agent skill collection for creating editable slide decks, design canvases, design systems, data-backed dashboards, motion films, and data visualizations. It ships local editors and artifact formats so the agent and human can iterate on files in the repository rather than relying on a hosted design surface.

## Why it qualifies

- Strong community traction with 5k+ GitHub stars and active releases.
- Maintained by Jim Liu, a recognizable open-source AI creator, with extensive documentation and examples.
- MIT-licensed maintainer code, explicit third-party notices, and clear disclosure of Anthropic-derived material.
- Works across Claude Code, Codex, Cursor, DeepSeek Harness, and other file-capable agents.

## Key features

- `claude-slides` for editable decks and PowerPoint/PDF/HTML export.
- `claude-design` and `claude-design-system` for artboards, prototypes, tokens, components, fonts, and assets.
- `claude-dashboard` for data-backed charts with a source panel that traces numbers to rows.
- `claude-motion` and `motion-director` for code-authored motion films, narration, and export.
- `dataviz` guidance and palette validation for readable, accessible charts.
- Local comments, sharing, version history, and conflict-aware collaboration.

## Install

Using the Vercel skills CLI:

```bash
npx skills add JimLiu/baoyu-design
```

Install globally or target one skill with `-g`, `--agent`, or `--skill` as documented upstream.

## Source

- Original repository: [JimLiu/baoyu-design](https://github.com/JimLiu/baoyu-design)
- License and attribution details: [NOTICE.md](https://github.com/JimLiu/baoyu-design/blob/main/NOTICE.md)
