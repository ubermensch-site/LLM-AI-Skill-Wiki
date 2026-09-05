# caveman

"Why use many token when few do trick." A Claude Code / Codex plugin that makes the agent talk like a caveman, cutting ~75% of output tokens while keeping full technical accuracy — based on the observation that terse, caveman-style responses preserve substance while dropping filler.

## Intensity Levels

| Level | Effect |
|---|---|
| Lite | Drop filler, keep grammar |
| Full (default) | Drop articles, fragments, full grunt |
| Ultra | Maximum/telegraphic compression |
| 文言文 (Wenyan) | Classical Chinese compression mode |

## The 5 Skills

- **caveman** — core terse-mode skill
- **caveman-commit** — terse Conventional Commits (≤50 char subject)
- **caveman-review** — one-line PR review comments
- **caveman-help** — quick reference card
- **caveman-compress** — rewrites memory files (e.g. `CLAUDE.md`) into caveman-speak so the agent *reads* fewer tokens too (~46% avg savings), keeping a human-readable `.original.md` backup

## Benchmarks

Real Claude API measurements average 65% token savings (range 22–87%) across coding tasks, with technical accuracy unchanged.

## Install

```
claude plugin marketplace add JuliusBrussee/caveman
claude plugin install caveman@caveman
```

## Source

https://github.com/JuliusBrussee/caveman
