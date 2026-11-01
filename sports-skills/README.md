# sports-skills

`sports-skills` is Machina Sports’ large collection of Agent Skills for live sports data, analytics, news, and prediction-market research. It follows the Agent Skills specification and exposes documented `SKILL.md` workflows for football, NFL, NBA, MLB, NHL, Formula 1, esports, market data, odds math, and related reporting tasks.

## Why it qualifies

- 250+ GitHub stars and active maintenance as of this review.
- Built by Machina Sports with a substantial open-source implementation, tests, Python package, CLI, and generated documentation site.
- MIT licensed, with explicit source, licensing, replay, privacy, and safety boundaries.
- Includes a clear autonomous-agent contract: read-only by default, no betting or trading without explicit user approval, and public data treated as untrusted input.

## Key capabilities

- Dedicated skills for major sports and leagues, plus ESPN, nflverse, FastF1, RSS, Kalshi, Polymarket, and other public sources.
- Record/replay support for reproducible evaluations and regression tests.
- Structured JSON output, source/freshness caveats, capability metadata, and documented limits.
- Read-only prediction-market research with separate explicit-approval boundaries for trading operations.

## Install

Install the full collection or a single skill with the Skills CLI:

```bash
npx skills add machina-sports/sports-skills
npx skills add machina-sports/sports-skills@nba-data
```

The optional Python package is available with:

```bash
pip install sports-skills
```

## Source

- Original repository: https://github.com/machina-sports/sports-skills
- Documentation site: https://sports-skills.sh

The repository is MIT licensed, but its third-party data sources have their own terms and usage limits. Prefer the upstream repository for current coverage and compliance details.
