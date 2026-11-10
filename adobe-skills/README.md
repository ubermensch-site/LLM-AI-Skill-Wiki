# Adobe Skills for AI Coding Agents

Official Adobe collection of portable agent skills and Claude Code-style plugins for Adobe analytics, Customer Journey Analytics, AEM, App Builder, Workfront, Commerce, Adobe Developer Console, and creative workflows.

## Why it belongs here

- Officially maintained by Adobe.
- Apache-2.0 licensed with a substantial, documented plugin and skill catalog.
- Supports Claude Code plugins, GitHub Copilot CLI, Vercel Skills, and a Cursor preview path.
- Includes product-specific MCP integrations, install instructions, examples, and contribution guidance.

## Highlights

- Analytics and Customer Journey Analytics KPI, funnel, segment, and executive-briefing workflows
- AEM Edge Delivery Services, Cloud Service, 6.5 LTS, content migration, and project-management skills
- App Builder, Workfront UI extensions, Commerce app management, migration, and review workflows
- Adobe Developer Console and I/O Events assistance
- Creative Cloud and Firefly workflow skills

## Install

```bash
npx skills add adobe/skills --all
```

Claude Code users can also add the marketplace and install individual plugins:

```text
/plugin marketplace add adobe/skills
/plugin install adobe-for-developers@adobe-skills
```

See the source repository for the complete plugin catalog, MCP configuration, authentication requirements, and product-specific setup.

## Source

- Repository: https://github.com/adobe/skills
- Website/catalog: https://github.com/adobe/skills#readme
