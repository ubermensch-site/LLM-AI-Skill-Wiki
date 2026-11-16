# OpenMontage

An open-source, agentic video-production system that turns a brief into a finished video through structured pipelines. Its readable YAML manifests and Markdown skills teach an agent how to select tools, execute stages, self-review outputs, and request approval for creative decisions.

## What it includes

- 10+ production pipelines for explainers, documentaries, talking heads, demos, animation, localization, and more
- 700+ agent skill and production-knowledge files covering pipeline directors, creative techniques, tool usage, and quality checks
- Provider and tool registries, auditable selection scores, checkpoints, budgets, and delivery gates
- Remotion, HyperFrames, real-footage, image, audio, subtitle, and voice workflows with local and cloud options
- Contract tests, QA integration tests, ffprobe/frame/audio validation, and reproducible prompt examples

## Why it qualifies

The AGPLv3 project is a substantial, actively documented skill-driven production system with a large user community. It keeps orchestration and quality standards in inspectable YAML and Markdown, and records provider, cost, and review decisions instead of hiding them behind a single prompt.

## Install

```bash
git clone https://github.com/calesthio/OpenMontage.git
cd OpenMontage
make setup
```

See the [upstream repository](https://github.com/OpenMontageInc/OpenMontage) for prerequisites, provider setup, pipeline prompts, and contribution guidance.
