# Lark CLI Skills

## Summary

[Lark/Feishu's official CLI](https://github.com/larksuite/cli) combines a substantial Go command-line implementation with portable `SKILL.md` agent skills for collaboration and business workflows. The collection covers calendars, messaging, documents, Drive, spreadsheets, Base, tasks, mail, meetings, and more.

## Key capabilities

- Service-specific skills and references backed by curated CLI commands, schema introspection, structured JSON output, and raw API access.
- Shared authentication, user/bot identity, scope management, output contracts, and safety rules.
- Meeting-summary and standup-report workflow skills, plus guidance for creating custom skills.
- Dry-run previews where supported and explicit approval gates for high-risk writes.

## Why it qualified

- Official `larksuite` repository, maintained by the Lark team; MIT-licensed with substantive Go implementation, test directories, linting, and release configuration.
- Approximately 17,561 stars and 1,387 forks when reviewed on 2026-10-08. Adoption supports the vendor provenance and implementation evidence; stars alone were not the selection criterion.
- Inspected the upstream README, repository layout, and `skills/lark-shared/SKILL.md`, including identity, permission, and high-risk-operation guidance.
- A commit since the previous wiki run added URL-rewriting extension support with boundary fixes and test coverage.

## Install / use

Commands from the upstream README:

```bash
# Install the CLI
npx @larksuite/cli@latest install

# Explicit skills installation (also documented for source builds)
npx skills add larksuite/cli -y -g

# Interactive credential setup and login
lark-cli config init
lark-cli auth login --recommend
lark-cli auth status
```

Review requested scopes before authorizing. Agents can act under your identity and modify or expose sensitive data; keep default protections, preview risky operations, and explicitly approve writes. The upstream documentation describes limited device risk-control signals sent to official Lark/Feishu HTTPS domains. CLI installation and API authorization are separate steps.

## Source

- Repository and current documentation: https://github.com/larksuite/cli
- Reviewed snapshot: https://github.com/larksuite/cli/tree/1d26c2283915a4f8e7d03a880ed0e4fae91309a8
- Shared skill: https://github.com/larksuite/cli/blob/1d26c2283915a4f8e7d03a880ed0e4fae91309a8/skills/lark-shared/SKILL.md
