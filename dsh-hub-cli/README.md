# dsh-hub-cli

A Skill + tooling bundle for **DSH Hub CLI**, which lets you package and share an entire **DeepSeek Harness (DSH)** setup as a versioned, reproducible preset (“Profile”), with a **plan → review → apply** workflow designed to be safe for human-in-the-loop and agent-driven usage.

## What it does

- Captures a complete DSH profile (runtime version, ordered plugin bundles, and patch config) into an immutable, content-addressed Release.
- Lets others preview exact changes via diff/plan steps before applying.
- Provides rollback and validation checks so changes are reversible and safer to automate.

## Why it’s trusted

- Clear, security-focused design: explicit plans, staged apply, content hashing, pinned sources, and secret-safety rules.
- Well-documented and actively maintained.

## Source

- https://github.com/pax-beehive/dsh-hub-cli

## Skill location in source repo

- https://github.com/pax-beehive/dsh-hub-cli/tree/main/skills/dsh-hub
