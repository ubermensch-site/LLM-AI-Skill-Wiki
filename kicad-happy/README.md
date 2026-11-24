# kicad-happy

AI-powered KiCad design-review skills for schematics, PCB layouts, Gerbers, SPICE, EMC pre-compliance, datasheets, BOMs, component sourcing, and fabrication readiness. The collection works with Claude Code, OpenAI Codex, GitHub Copilot CLI, Google Antigravity, and opencode, and can also run as a GitHub Action for automated reviews.

## Why it qualifies

- Substantive open-source implementation with MIT licensing, CI, release notes, tests, and a documented regression corpus of thousands of KiCad projects.
- Mentioned in Awesome KiCad and actively maintained with concrete analyzer, sourcing, simulation, and manufacturing workflows.
- Uses deterministic parsers and rule checks alongside agent guidance, with explicit limitations and safety notes for datasheet and distributor access.

## Highlights

- Eleven skills cover KiCad analysis, SPICE, EMC, datasheets, BOM management, DigiKey, Mouser, LCSC, element14, JLCPCB, and PCBWay.
- Parses schematic and PCB data to trace power trees, validate passive networks, review protection and signal integrity, and identify production risks.
- Generates structured reports, sourcing files, fabrication gates, and optional GitHub PR reviews.
- Supports KiCad 5 through 10 and can run without a KiCad installation for analysis workflows.

## Install

Claude Code:

```text
/plugin marketplace add aklofas/kicad-happy
/plugin install kicad-happy@kicad-happy
```

For Codex and other compatible agents, use the repository's documented skill installer or copy the desired directories from `skills/` into the agent's skill path.

## Source

[aklofas/kicad-happy](https://github.com/aklofas/kicad-happy)
