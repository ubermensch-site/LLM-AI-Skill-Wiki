# sprite-gen

`sprite-gen` is a Codex/Claude skill and Python CLI for turning one character image into game-ready sprite atlases or transparent motion loops. It combines generation, chroma-key extraction, frame curation, deterministic post-processing, engine exports, and optional scene composition.

## Why it belongs here

- **Substantive implementation:** a documented Python package and CLI with multiple independent tools, contracts, manifests, curation, QA, and export workflows.
- **Reproducible outputs:** produces transparent atlases plus machine-readable `manifest.json.frame_layout` data instead of asking game engines to guess frame geometry.
- **Transparent provenance:** Apache-2.0 licensed, with documented attribution to the `hatch-pet` workflow it builds on and explicit credential/billing guidance for model providers.

## Key features

- Still-image to atlas-row pipeline with generated states, alpha extraction, curation, and runtime manifests
- Video-to-loop pipeline for idle, walk, run, jump, and attack motions
- Background removal, sheet slicing, atlas unpacking, recoloring, Aseprite/Phaser exports, and motion inspection
- Optional scene rendering with camera motion, lighting, layers, and placement metadata
- `SKILL.md` workflow plus Python CLI, tests/QA documentation, and multi-language guides

## Install

```bash
python3 -m venv .venv && source .venv/bin/activate
pip install -e .
sprite-gen --help
```

Install the agent skill from the repository with the standard Codex skill installer, then follow the upstream provider and safety guidance before making model calls.

## Source

- **Repository:** [aldegad/sprite-gen](https://github.com/aldegad/sprite-gen)
- **License:** Apache-2.0
- **Skill file:** [`SKILL.md`](https://github.com/aldegad/sprite-gen/blob/main/SKILL.md)
