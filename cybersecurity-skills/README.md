# Anthropic Cybersecurity Skills

The largest open-source cybersecurity skills library for AI agents: **818 production-grade skills across 34 security domains**, mapped to 6 industry frameworks.

## What it does

- Domains include Cloud Security, SOC Operations, Threat Hunting, Threat Intelligence, Web App Security, Digital Forensics, IAM, Malware Analysis, Red Teaming, Container Security, OT/ICS, API Security, Incident Response, AI Security, and more
- Every skill maps to the frameworks relevant to it: **MITRE ATT&CK** (v19.1), **NIST CSF 2.0**, **MITRE ATLAS** (AI/ML threats), **MITRE D3FEND** (defensive countermeasures), **NIST AI RMF**, and the new **MITRE Fight Fraud Framework (F3)**
- Each skill follows the `agentskills.io` standard: YAML frontmatter for fast discovery (~30 tokens to scan) plus a full Markdown workflow (500–2,000 tokens) with prerequisites, step-by-step execution, and a verification section
- Framework mappings verified against the upstream MITRE STIX bundles

## Install

```bash
npx skills add mukul975/Anthropic-Cybersecurity-Skills
```

## ⚠️ Important

This library includes offensive and dual-use techniques (red-team C2, phishing simulation, exploitation) intended **only** for authorized penetration testing, defense, and education — use only against systems you own or have explicit written permission to test.

## Why it's trusted

Apache-2.0 licensed, framework mappings independently validated against official MITRE data, and featured in multiple other vetted awesome-lists (VoltAgent/awesome-agent-skills, ottosulin/awesome-ai-security).

## Source

https://github.com/mukul975/Anthropic-Cybersecurity-Skills
