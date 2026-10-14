# Google Agent Skills

Official Agent Skills for Google products and technologies, including Google Cloud, with product-specific instructions, references, and supporting scripts for coding agents.

## What it does

- Covers cloud onboarding and IAM, architecture, agent deployment, AI/ML, GKE, databases, observability, security, advertising, and analytics.
- Includes concrete workflows such as turning API Gateway REST APIs into remote MCP tools, with authentication guidance, an OpenAPI validator, verification steps, and deployment checklists.
- Bundles product plugins combining skills and MCP servers for supported agent harnesses.

## Why it qualifies

- Maintained in Google's official GitHub organization, not an anonymous repackaging of prompts.
- Strong community adoption: approximately 21,263 stars and 1,781 forks when reviewed on 2026-10-14; counts are supporting evidence, not a quality guarantee.
- Apache-2.0 licensed, with substantive product-specific documentation and implementation references.
- Active Google team maintenance: recent commits added API Gateway MCP support, notification-channel configuration, and a compliance environment assessor on 2026-10-13/14.
- Reviewed the root documentation and the API Gateway MCP server's actual `SKILL.md`, including its safety boundaries and validation workflow.

## Install

From the upstream README:

```bash
npx skills add google/skills
```

Select the skills, target agents, and project/global scope when prompted. Review each skill before use; cloud workflows may require credentials, permissions, billing, and human approval before production changes.

## Source

- Repository: https://github.com/google/skills
- Installation and catalog: https://github.com/google/skills/blob/main/README.md
- Reviewed example: https://github.com/google/skills/blob/main/skills/cloud/api-gateway-mcp-server/SKILL.md

Always consult the upstream repository for current instructions and service availability.
