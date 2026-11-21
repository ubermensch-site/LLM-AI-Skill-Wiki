# SkillHawk

A static security scanner and hands-on lab for AI Agent Skills, `SKILL.md` files, and MCP configurations. It flags risky instructions without executing the target repository.

## Why it is notable

- Detects remote shell downloads, encoded execution, destructive commands, credential access, persistence, outbound uploads, prompt injection, and related risks.
- Includes CI, SARIF output, remediation guidance, and a reproducible 48-fixture benchmark reported at 93.75% precision, recall, and F1.
- MIT licensed, zero-dependency at runtime, and paired with a practical fork-first security learning lab.

## Install / scan

```bash
git clone https://github.com/Berserk-hub150/skillhawk.git
cd skillhawk
node src/cli.js scan .
```

## Source

[Berserk-hub150/skillhawk](https://github.com/Berserk-hub150/skillhawk)
