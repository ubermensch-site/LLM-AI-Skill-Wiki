# Ponytail

"He says nothing. He writes one line. It works." An anti-over-engineering skill modeled on the lazy senior dev who replaces 50 lines with one.

## The Decision Ladder

```
1. Does this need to exist?   → no: skip it (YAGNI)
2. Stdlib does it?            → use it
3. Native platform feature?   → use it
4. Installed dependency?      → use it
5. One line?                  → one line
6. Only then: the minimum that works
```
Validation, security, error handling, and accessibility are never on the chopping block — lazy, not negligent.

## Measured Impact (real agentic benchmark, Claude Code on a live FastAPI+React repo)

| vs no-skill baseline | LOC | tokens | cost | time | safe |
|---|--:|--:|--:|--:|--:|
| ponytail | **-54%** | -22% | -20% | -27% | 100% |

## Commands

`/ponytail [lite\|full\|ultra\|off]`, `/ponytail-review` (diff over-engineering check), `/ponytail-audit` (whole-repo audit), `/ponytail-debt` (harvest deferred shortcuts), `/ponytail-gain` (impact scoreboard), `/ponytail-help`.

## Install

```
/plugin marketplace add DietrichGebert/ponytail
/plugin install ponytail@ponytail
```

## Source

https://github.com/DietrichGebert/ponytail
