# antialgorithm

A focused creative-work skill that helps agents move past the first safe, average idea. It applies to names, stories, game ideas, posters, UI, visual style, slogans, and other open-ended choices by identifying the default, grounding an alternative in the project, and requiring a reason for the deviation.

## Why it is trusted

- MIT-licensed, release-backed, and documented for Claude Code, Codex, Cursor, OpenCode, and other skills-compatible agents.
- Ships a real `SKILL.md`, multilingual documentation, scripts, visual guidance, examples, and a plugin manifest.
- Includes reproducible seed and move-history tooling rather than relying only on subjective prompting.
- Provides a concrete SVG checking workflow for overflow, contrast, layering, and small-size readability.

## Highlights

- Context-specific creative seeds for visual, text, and idea work.
- `moves.py` history to avoid repeating the same successful creative move.
- `rough.py` for intentionally handmade SVG treatments.
- `check.py` for full-size and icon-size SVG quality checks.
- Guardrails that preserve user constraints and avoid replacing one cliché with another.

## Install

Install with the cross-agent skills CLI:

```bash
npx skills add mankidev/antialgorithm
```

For Claude Code, the repository also documents plugin installation:

```text
/plugin install antialgorithm --marketplace mankidev/antialgorithm
```

## Source

[mankidev/antialgorithm](https://github.com/mankidev/antialgorithm)
