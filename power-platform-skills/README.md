# Microsoft Power Platform Skills

## Summary

[Microsoft's Power Platform Skills](https://github.com/microsoft/power-platform-skills) is an official plugin marketplace for GitHub Copilot CLI and Claude Code. It supplies reusable skills, agents, commands, references, and tooling for building and deploying Power Platform solutions.

## Key capabilities

- Power Pages code sites and model-driven Power Apps, including tables, relationships, forms, views, security roles, and generative pages.
- React-based code apps, Expo/React Native mobile apps, and native extensions for wrapped Canvas apps.
- Canvas app authoring and Power Automate flow creation, execution, and debugging through their documented MCP integrations.
- Codeful MCP tool and interactive MCP App widget generation, with bundled references and samples.
- An external Dataverse plugin sourced from Microsoft's separate Dataverse-skills repository.

## Why it qualified

- Official Microsoft repository with MIT licensing, service-specific documentation, concrete plugin implementations, and compatibility validation tooling.
- Approximately 968 stars and 196 forks when reviewed on 2026-10-07; official provenance and substantive reviewed maintenance are the primary trust signals.
- Commits after the previous wiki run include Power Pages permissions-audit improvements with validator tests, a filesystem race fix, and model-app build/authentication improvements.
- This is a separate Power Platform marketplace, not a duplicate of the already-indexed microsoft/skills collection.

## Install

Manual installation commands copied from the upstream README, run inside a supported GitHub Copilot CLI or Claude Code session:

```bash
/plugin marketplace add microsoft/power-platform-skills
/plugin install power-pages@power-platform-skills
```

Install only the plugins needed for your workflow. Requirements vary by plugin and can include PAC CLI, Azure authentication, .NET, Node.js, or service-specific MCP servers; consult upstream documentation first.

## Operational notes

Some plugins deploy or modify cloud resources. Use explicit permissions and review changes; do not bypass approval prompts merely to reduce friction. Several plugins ship default-on telemetry that can include tenant/organization identifiers. Upstream documents per-plugin opt-out commands such as `/power-pages:telemetry off`; transmission opt-out does not stop the local diagnostic mirror.

## Source

- Repository and current documentation: https://github.com/microsoft/power-platform-skills
- Reviewed implementation snapshot: https://github.com/microsoft/power-platform-skills/tree/fb08c32a56ffbc260ac903683109c1e58c80501d
