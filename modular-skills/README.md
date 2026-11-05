# Modular Skills

Official Agent Skills from [Modular](https://www.modular.com/) for the MAX and Mojo platforms. The collection follows the Agent Skills Standard and gives coding agents grounded workflows for creating Mojo projects, writing modern Mojo, importing and serving models, debugging, profiling, benchmarking, and evaluating inference workloads.

## Why it is trusted

- Maintained by Modular, the company behind the MAX AI inference platform and Mojo.
- Uses the open Agent Skills Standard and provides focused, task-routed `SKILL.md` files.
- Covers a complete model lifecycle, from Hugging Face import through serving, profiling, and evaluation.
- Licensed under Apache-2.0.

## Installation

```bash
# Claude Code
/plugin marketplace add modular/skills
/plugin install skills@modular

# Codex and other agents
npx skills add modular/skills
```

Install an individual skill with `npx skills add modular/skills --skill mojo-syntax`. See the [source repository](https://github.com/modular/skills) for the full catalog and current instructions.
