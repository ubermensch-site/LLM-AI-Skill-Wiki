# NVIDIA Agent Skills and Plugins

Official NVIDIA-verified Agent Skills and Plugins for Claude Code, Codex, Cursor, and other coding agents. The collection covers NVIDIA software workflows rather than generic prompt snippets, including physical AI and robotics, simulation, CUDA-X libraries, RAG and AI Blueprints, and platform tooling.

## Why it is trusted

- Published and maintained by NVIDIA.
- Skills and plugins are signed, scanned, and evaluated before shipping.
- The repository includes a large catalog, product documentation, benchmarks, security guidance, and automated synchronization from product repositories.
- Apache-2.0 and CC-BY-4.0 licensing is clearly documented.

## Highlights

- NVIDIA platform, CUDA, cuDNN, TensorRT, NeMo, NIM, and AI Blueprint workflows.
- Physical AI, robotics, simulation, Earth-2, BioNeMo, and RAG guidance.
- Plugin bundles that can include product skills and local MCP servers.
- A skill finder for discovering the right product workflow.

## Install

Install the complete catalog interactively with the skills CLI:

```bash
npx skills add nvidia/skills --agent claude-code
```

For Codex or Cursor, replace the agent name as needed. To install one named skill non-interactively:

```bash
npx skills add nvidia/skills --skill <skill-name> --yes
```

## Source

- Repository: [NVIDIA/skills](https://github.com/NVIDIA/skills)
- Documentation: [docs.nvidia.com/skills](https://docs.nvidia.com/skills)
