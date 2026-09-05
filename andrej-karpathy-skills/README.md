# Karpathy-Inspired Claude Code Guidelines

A single `CLAUDE.md` file that improves Claude Code behavior, derived from Andrej Karpathy's observations on common LLM coding pitfalls (wrong silent assumptions, overcomplicated code, orthogonal edits to code the model doesn't understand).

## The Four Principles

1. **Think Before Coding** — state assumptions explicitly, present interpretations, ask when confused
2. **Simplicity First** — minimum code that solves the problem, no speculative abstractions
3. **Surgical Changes** — touch only what you must, don't "improve" adjacent code
4. **Goal-Driven Execution** — define success criteria (tests) and loop until verified

## Install

```
/plugin marketplace add forrestchang/andrej-karpathy-skills
/plugin install andrej-karpathy-skills@karpathy-skills
```
or append to `CLAUDE.md`:
```bash
curl -o CLAUDE.md https://raw.githubusercontent.com/forrestchang/andrej-karpathy-skills/main/CLAUDE.md
```

## Source

https://github.com/forrestchang/andrej-karpathy-skills
