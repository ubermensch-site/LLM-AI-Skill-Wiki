# Mathodology

[Mathodology](https://github.com/sweetcornna/mathodology) is a Chinese-and-English Agent Skills collection and desktop workbench for mathematical modeling competitions and reproducible scientific workflows. Its nine skills cover problem decomposition, evidence retrieval, scientific plotting, review questions, experiments, and paper writing, with hooks and scripts that check whether results, figures, citations, and LaTeX stay consistent.

## Why it is trusted

- MIT-licensed project with a released cross-platform Studio application.
- Uses executable checks and versioned artifacts instead of relying only on prompt instructions.
- Includes 46 chart templates, 18 experiment components, DOI/reference verification, and reproducibility-oriented workflows.
- Supports Claude Code, Codex, Antigravity CLI, and other local agent CLIs without collecting model API keys or project data.

## Installation

```bash
npx -y skills@latest add sweetcornna/mathodology --copy --yes --skill '*' --agent codex
```

For Claude Code, change the final agent argument to `claude-code`. See the [source repository](https://github.com/sweetcornna/mathodology) for the Studio app, complete skill catalog, workflows, and update instructions.
