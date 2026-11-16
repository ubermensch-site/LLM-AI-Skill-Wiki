# geo-sleuth

An evidence-driven Agent Skill for locating where a photograph was taken. It turns a photo and a short request into a reproducible investigation using geometry, elevation, open map data, satellite imagery, street view, and generated evidence files.

## What it includes

- A standard `SKILL.md` plus Python scripts, references, region packs, and data tables
- OSM geometry, terrain and skyline fitting, shadows, satellite scans, reverse image search, and street-view matching
- Candidate ranking that keeps the model judging among scored results instead of guessing from fame
- Evidence-bound reports with coordinates, heading, error radius, confidence, and the files that support each claim
- Detailed case studies, regression checkpoints, and benchmark measurements across several real geolocation tasks

## Why it qualifies

The MIT-licensed repository is multi-harness compatible, documents responsible-use boundaries, and provides unusually concrete reproduction conditions and accuracy evidence for a skill. It has substantial community traction and a maintained, inspectable implementation rather than a prompt-only demo.

## Install

```bash
npx skills add Oldcircle/geo-sleuth
```

See the [upstream repository](https://github.com/Oldcircle/geo-sleuth) for requirements, examples, data-source notes, and manual installation.
