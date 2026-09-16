# clawbio

A bioinformatics-native AI agent skill library with local-first execution, validated scientific workflows, runnable demo data, and reproducibility support. ClawBio packages domain expertise as versioned `SKILL.md` specifications plus tested Python implementations.

## Why it’s useful

- Makes genomics, pharmacogenomics, population genetics, single-cell analysis, and related workflows easier for agents to route and execute without improvising domain decisions.
- Emphasizes local processing, explicit data-handling disclosures, reproducibility bundles, and objective validation rather than prompt-only demonstrations.
- Supports direct CLI/Python use as well as Claude Code, OpenClaw, Telegram, and Discord interfaces.

## What’s included (high level)

- 97 skills, including PharmGx reporting, drug-photo analysis, GWAS lookup, PRS, ancestry PCA, fine-mapping, UK Biobank navigation, Galaxy integration, and clinical variant reporting
- Runnable demos, `skills/catalog.json`, maturity tiers, per-skill tests, benchmark infrastructure, and nightly sweeps
- Reproducibility outputs such as replay commands, environment metadata, and checksums where supported
- Installation through `pip`, Conda, source checkout, or the Claude Code plugin marketplace

## Trust signals

- MIT licensed with CI, documented data-handling and security guidance, benchmark validation, and a Zenodo DOI
- Built with explicit scientific provenance and reproducibility goals, while documenting which skills use external APIs
- Active community project with published meetup and hackathon materials

## Source

- https://github.com/ClawBio/ClawBio