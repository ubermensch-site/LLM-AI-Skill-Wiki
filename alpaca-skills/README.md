# Alpaca Skills

Alpaca Skills is the official open collection of Agent Skills for Alpaca’s Trading API and Broker API. Each skill is a `SKILL.md` workflow with step-by-step instructions, guardrails, and reporting standards for backtesting, paper trading, market data, broker-account onboarding, funding, reconciliation, and related API operations.

## Why it qualifies

- Published and maintained by Alpaca, an established brokerage and trading-API provider.
- Apache-2.0 licensed with a substantial, clearly organized skill catalog.
- Documents credentials, paper/live environments, operational boundaries, and financial-risk disclosures.
- Uses the interoperable Skills CLI and provides manual installation paths for multiple agent clients.

## Key capabilities

- Trading API backtesting, paper trading, market data, and MCP workflows.
- Broker API integration, account onboarding/KYC, funding transfers, journals, order execution, SSE events, reconciliation, rate limits, and money precision.
- Product-scoped naming and install instructions for Claude Code, Cursor, and other agents.
- Explicit disclosure that generated insights are informational and not investment advice.

## Install

```bash
npx skills add alpacahq/alpaca-skills
npx skills add alpacahq/alpaca-skills --skill alpaca-trading-backtest
```

The Alpaca CLI and appropriate paper, sandbox, or live credentials are prerequisites for many workflows; follow the upstream documentation and use the least-privileged environment appropriate to the task.

## Source

- Original repository: https://github.com/alpacahq/alpaca-skills
- Alpaca API documentation: https://docs.alpaca.markets/

Alpaca Skills is Apache-2.0 licensed. Trading involves risk; prefer paper or sandbox environments while evaluating the workflows.
