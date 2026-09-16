# styleseed

An open-source design-method engine that turns expert visual decisions into repeatable workflows for coding agents. StyleSeed combines project-scoped design locks, 74 craft rules, 23 agent skills, brand recipes, semantic palettes, and code/rendered quality gates.

## Why it’s useful

- Targets the recurring “AI-generated UI” problems: generic layouts, uncontrolled accents, weak hierarchy, missing states, and design drift between screens.
- Compiles only the relevant design context into a verifiable project bundle instead of forcing every task to load the full handbook.
- Keeps human approval in the loop: scores and gates are evidence for review, not substitutes for design acceptance.

## What’s included (high level)

- `/ss-setup`, `/ss-resolve`, `/ss-build`, `/ss-review`, `/ss-score`, `/ss-verify`, `/ss-a11y`, `/ss-copy`, and related workflows
- Nine output/brand recipes, eight semantic palette recipes, seven skins, 48 React components, and a named motion system
- Reference compilation from screenshots, URLs, Figma, or existing UI into project grammar
- Cross-agent support for Claude Code, Codex, Cursor, Gemini CLI, Amp, and other skills-compatible tools

## Trust signals

- MIT licensed and openly developed with CI, documentation, evaluator quickstarts, regression fixtures, and published evidence boundaries
- Reports a 120-cell benchmark and explains where automated scores should not replace human review
- Provides a reproducible install path through `npx skills add bitjaru/styleseed`

## Source

- https://github.com/bitjaru/styleseed