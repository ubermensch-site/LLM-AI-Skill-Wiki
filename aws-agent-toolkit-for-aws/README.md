# AWS Agent Toolkit for AWS

AWS's official toolkit for giving AI coding agents the tools, skills, plugins, and guardrails needed to build, deploy, and manage applications on AWS.

## What it includes

- `aws-core` guidance for service selection, CDK and CloudFormation, serverless, containers, storage, observability, billing, SDK usage, and deployment.
- `aws-agents` skills for building Amazon Bedrock and AgentCore agents.
- Data analytics, DevSecOps, security remediation, and startup-advisor plugins.
- AWS MCP Server integration with broad API coverage, sandboxed script execution, real-time documentation access, IAM controls, CloudWatch metrics, and CloudTrail audit logging.
- Skills and plugins that work across Claude Code, Codex, Cursor, Devin, Kiro, fx, and other compatible agents.

## Installation

For the general skill collection:

```bash
npx skills add aws/agent-toolkit-for-aws/skills
```

Claude Code users can install the core plugin from the official marketplace:

```text
/plugin install aws-core@claude-plugins-official
```

See the upstream README for agent-specific plugin installation, AWS MCP configuration, prerequisites, and the complete skill catalog.

## Why it is trusted

This is the official AWS repository, Apache-2.0 licensed, backed by AWS documentation and CI, and explicit about authentication, IAM, auditing, sandboxing, and the boundary between skills and live AWS access.

## Source

[aws/agent-toolkit-for-aws](https://github.com/aws/agent-toolkit-for-aws)
