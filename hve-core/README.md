# HVE Core

Microsoft’s Hypervelocity Engineering Core is an opinionated agentic SDLC framework for context management, governance, reusable organizational knowledge, and consistent engineering practices. It packages specialized agents, coding instructions, and reusable skills around a Research–Plan–Implement workflow.

## Why it qualifies

- Officially maintained by Microsoft and documented as a reusable framework rather than a single prompt.
- Includes CI, dependency review, CodeQL, OpenSSF Scorecard, governance, security, and transparency documentation.
- MIT licensed, with third-party attribution notes for content derived from OWASP publications.
- Clearly states its limitations: it is rapidly evolving and should be adapted and owned by the adopting team.

## Key features

- Specialized agents for research, planning, implementation, and review.
- Instructions that apply coding standards and organizational practices during development.
- Skills and slash-command entry points for reusable workflows and tool capabilities.
- RPI methodology, workflow canvases, documentation, validation standards, and customization guidance.
- Distribution through the GitHub Copilot plugin, VS Code extension, and documented repository packages.

## Install

GitHub Copilot CLI:

```bash
copilot plugin marketplace add microsoft/hve-core
copilot plugin install hve-core@hve-core
```

VS Code users can install the HVE Core extension, or follow the upstream installation guide for the route that best fits their environment.

## Source

- [microsoft/hve-core](https://github.com/microsoft/hve-core)
- [Upstream README](https://github.com/microsoft/hve-core#readme)
- [Documentation](https://microsoft.github.io/hve-core/)
