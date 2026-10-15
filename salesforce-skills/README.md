# Salesforce Agent Skills

Salesforce's official collection of Agent Skills for Agentforce and Salesforce application development, covering Apex, SOQL, Lightning Web Components, Flow, data models, permissions, UI bundles, and related platform workflows.

## What it does

- Provides executable, directory-based workflows for generating and working with Salesforce platform artifacts.
- Covers Agentforce agents, Lightning apps, Apex, SOQL, Lightning Web Components, Flow automation, custom objects and fields, permission sets, and more.
- Follows the open Agent Skills specification, with `SKILL.md` instructions plus optional scripts, references, and assets.
- Supports Agentforce Vibes and can be installed into OpenCode, Claude Code, Codex, Cursor, and other compatible agents.

## Why it qualifies

- Maintained in Salesforce's official GitHub organization, with contributions from Salesforce and the wider community.
- Strong community adoption: approximately 1,091 stars and 371 forks when reviewed on 2026-10-15; counts are supporting evidence, not a quality guarantee.
- Substantive platform-specific workflows rather than a thin prompt collection, with a large catalog and automated release process.
- Actively maintained: recent October 2026 releases added and updated skills, with the repository publishing frequent versioned releases.

## Install

From the upstream README:

```bash
npx skills add forcedotcom/sf-skills
```

Agentforce Vibes installs and updates the skills automatically. Review skills and required Salesforce permissions before allowing an agent to create or modify production metadata.

## Source

- Repository: https://github.com/forcedotcom/sf-skills
- Documentation and catalog: https://github.com/forcedotcom/sf-skills/blob/main/README.md
- Skill specification: https://agentskills.io/

Always consult the upstream repository for the current catalog and compatibility guidance.
