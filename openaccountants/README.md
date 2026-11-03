# OpenAccountants

OpenAccountants is a jurisdiction-aware tax skill library for AI. It provides thousands of skills across hundreds of jurisdictions, with rates, thresholds, and deadlines tied to official sources and a visible review model that distinguishes accountant-reviewed content from law-sourced material.

## Why it qualifies

- Hundreds of GitHub stars and an actively synchronized public repository.
- Large, substantive catalog: 2,000+ skills across 200+ jurisdictions.
- Clear quality tiers, named reviewers, source citations, nightly checks, and stale-number monitoring.
- AGPL-3.0 code with explicit safety language that outputs are general reference, not tax advice.

## Key features

- Country and state tax skill packs organized under `skills/` and `packages/`.
- Official-source citations for rates, thresholds, deadlines, and calculations.
- Accountant roster and review metadata for reviewed skills.
- Machine-readable inventory and a Python MCP server for connected AI clients.
- Automated maths checks, source watching, refresh workflows, and nightly answer tests.

## Connect

Use the hosted MCP endpoint:

```text
https://www.openaccountants.com/api/mcp
```

For self-hosting:

```bash
pip install openaccountants-mcp
```

Always check the skill's review state and have a qualified professional verify outputs before filing, payment, or other action.

## Source

- Original repository: [openaccountants/openaccountants](https://github.com/openaccountants/openaccountants)
- Project site: [openaccountants.com](https://www.openaccountants.com)
- License: AGPL-3.0 for code; skill content follows the repository's Guide License
