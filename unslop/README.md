# unslop

`unslop` is a focused Claude Code and Codex skill for turning generic, AI-looking interfaces into deliberate product design. It audits visual problems first, establishes a direction from the product, and then iterates through spacing, color, icons, copy, typography, layout, details, visuals, and motion.

## Why it belongs here

- **Clear authorship:** created and maintained by designer/developer Damir Sokolovsky (`@heydamir`).
- **Substantive workflow:** includes audit and direction stages, ordered design passes, live-site support, examples, and optional story-video output rather than a thin prompt wrapper.
- **Practical guardrails:** it proposes a direction before editing, asks before paid image generation, and can recommend small refinements instead of redesigning a good screen.

## Key features

- Detects common AI-generated UI patterns such as generic gradients, glows, emoji labels, weak copy, and uneven spacing
- Works with Next.js, React, Vue, Svelte, Tailwind, plain HTML/CSS, dashboards, apps, landing pages, and live URLs
- Uses product-specific visual direction instead of a one-size-fits-all style
- Produces ordered design passes and can create an under-10-second story video with Playwright and ffmpeg
- Supports Claude Code, Codex, and project-local installation

## Install

For Claude Code:

```bash
git clone https://github.com/heydamir/unslop
mkdir -p ~/.claude/skills && cp -r unslop/skills/unslop ~/.claude/skills/
```

For Codex, install the `skills/unslop` directory from the upstream repository or copy it into `~/.agents/skills/`.

## Source

- **Repository:** [heydamir/unslop](https://github.com/heydamir/unslop)
- **License:** CC BY 4.0
- **Creator:** [Damir Sokolovsky](https://x.com/heydamir)
