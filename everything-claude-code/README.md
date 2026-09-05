# Everything Claude Code

"The performance optimization system for AI agent harnesses." Not just configs — a complete system: skills, instincts, memory optimization, continuous learning, security scanning, and research-first development, evolved over 10+ months of daily production use. Works across Claude Code, Codex, Cursor, OpenCode, and other harnesses. Anthropic Hackathon winner, 50K+ stars.

## What's Inside (16 agents / 65+ skills / 40 commands)

- **Agents**: planner, architect, tdd-guide, code-reviewer, security-reviewer, build-error-resolver, e2e-runner, refactor-cleaner, doc-updater, language-specific reviewers (Go/Python/DB)
- **Skill areas**: coding-standards per language (TS, Python/Django, Go, Java/Spring, C++, Swift), frontend/backend patterns, continuous-learning (auto-extract patterns into reusable skills), iterative-retrieval, security-scan (AgentShield integration, 102 rules), eval-harness/verification-loop, frontend-slides (HTML→PPTX decks), business skills (article-writing, market-research, investor-materials)
- **Harness commands**: `/harness-audit`, `/loop-start`, `/loop-status`, `/quality-gate`, `/model-route`, `/plan`, `/multi-plan`/`/multi-execute` for multi-service orchestration

## Token Optimization Guidance

Recommends `model: sonnet`, `MAX_THINKING_TOKENS: 10000`, `CLAUDE_AUTOCOMPACT_PCT_OVERRIDE: 50` in `~/.claude/settings.json`, plus disciplined `/clear`/`/compact`/`/cost` usage and capping MCPs (<10) and tools (<80) enabled at once.

## Install

```
/plugin marketplace add affaan-m/everything-claude-code
/plugin install everything-claude-code@everything-claude-code
```
Rules must be installed separately: `./install.sh typescript` (or python/golang/swift/php).

## Source

https://github.com/affaan-m/everything-claude-code
