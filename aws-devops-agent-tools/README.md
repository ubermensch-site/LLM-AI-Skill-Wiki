# AWS DevOps Agent Tools

Official AWS collection of Agent Skills, custom agents, MCP servers, and infrastructure templates for incident response, root-cause analysis, health reporting, and operational troubleshooting with AWS DevOps Agent.

## Why it belongs here

- Published by AWS under the Apache-2.0 license.
- Follows the open Agent Skills specification and links to AWS product documentation.
- Provides a substantive catalog of runbooks plus custom-agent and MCP integrations, rather than a prompt-only collection.
- Documents IAM prerequisites, security considerations, contribution guidelines, and production deployment caveats.

## Highlights

- Domain-specific investigation skills with decision trees and step-by-step runbooks
- Custom agents for recurring operational workflows and reviews
- MCP servers that retrieve the infrastructure context needed by investigations
- CloudFormation templates for skill permissions and CloudWatch alarm forwarding
- Public catalogs and a getting-started guide for deploying tools to an Agent Space

## Install / use

Start with the official getting-started guide and review each skill's required IAM permissions before deployment:

- Guide: https://aws.github.io/tools-for-devops-agent/getting-started/
- Skills catalog: https://aws.github.io/tools-for-devops-agent/skills/
- Source repository: https://github.com/aws/tools-for-devops-agent

The repository explicitly recommends testing in a non-production environment first and validating IAM and security settings against your organization's policies.
