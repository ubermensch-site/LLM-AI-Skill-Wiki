# SciAgent-Skills

A structured scientific skill library for AI coding agents: 199 `SKILL.md` workflows covering genomics, bioinformatics, single-cell analysis, proteomics, drug discovery, biostatistics, scientific computing, lab automation, and scientific writing. Skills include prerequisites, runnable examples, parameters, recipes, troubleshooting, and a registry for discovery.

The project reports a 92.0% result on the BixBench-Verified-50 benchmark, compared with 65.3% for its stated Claude Code baseline; treat benchmark claims as project-reported results and review the benchmark materials before relying on them.

## Why it is trustworthy

It provides a real 199-skill repository rather than a thin prompt list, supports Claude Code, Codex, Cursor, and Windsurf, publishes integration templates and a registry validator, and links its benchmark to the public FutureHouse BixBench project. Original content is CC-BY-4.0.

## Install

```sh
git clone https://github.com/jaechang-hits/SciAgent-Skills.git
cd SciAgent-Skills
pixi install
```

For Claude Code, load it with `claude --plugin-dir /path/to/SciAgent-Skills`; Codex, Cursor, and Windsurf setup templates are documented in the source README.

## Source

[jaechang-hits/SciAgent-Skills](https://github.com/jaechang-hits/SciAgent-Skills)
