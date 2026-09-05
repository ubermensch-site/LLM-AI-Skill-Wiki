# ICM Architect

Designs workspaces where the **folder structure does the orchestration** — an implementation of Interpretable Context Methodology (ICM, Van Clief & McDermott). One agent walking a well-structured folder tree replaces a multi-agent framework: numbered folders carry sequencing, hierarchy carries context scoping, and plain markdown files carry state.

## The 10 Invariants

1. One folder, one job 2. Small stable entry file (`CLAUDE.md`/`AGENTS.md`, <60 lines) 3. Numbering encodes order 4. Explicit folder-level contracts (`CONTEXT.md`) 5. Factory vs. product separation 6. Every output is a human-editable edit surface 7. Load only what the step needs (2k–8k tokens) 8. Plain text, linkable, queryable (Markdown + YAML frontmatter) 9. The filesystem *is* the state machine 10. Instantiate by copying templates

## Modes

- **Build mode** — turn a described process/idea into a new ICM workspace (pipeline, umbrella, record library, knowledge bundle, context map, or system map form)
- **Restructure mode** — turn an existing messy folder/repo/vault into ICM structure via inventory → classify → propose → migrate

Both modes finish with a **walk test**: can a cold agent find what it needs within the entry file plus ~2 more reads?

## Use when

Turning a recurring workflow into an agent-runnable pipeline, organizing scattered notes into an AI-walkable library, mapping a team/company as connected context, or auditing a codebase into a change-impact map.

## Source

Forked skill — see the fork on this account for the original `SKILL.md`.
