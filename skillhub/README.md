# SkillHub

SkillHub is iFlytek Astron's self-hosted, enterprise-grade registry and governance platform for Agent Skills. It lets teams publish, version, discover, review, and install `SKILL.md` packages behind their own firewall instead of treating skills as unmanaged prompt files.

## Why it belongs here

- **Official source:** maintained by the iFlytek Astron open-source ecosystem.
- **Substantive implementation:** Java 21/Spring Boot backend, React/TypeScript frontend, CLI, REST API, Docker images, Kubernetes manifests, Helm, tests, and deployment documentation.
- **Real governance model:** namespaces, RBAC, review and promotion flows, audit logs, scoped API tokens, content-safety guidance, and pluggable storage.

## Key features

- Self-hosted private registry for reusable Agent Skills
- Semantic versioning, tags, latest tracking, search, ratings, and downloads
- Team namespaces with Owner/Admin/Member roles and visibility controls
- CLI-first publishing and installation, including compatibility with OpenClaw-style clients
- Docker/Compose, Kubernetes, Helm, S3/MinIO, PostgreSQL, and Redis deployment options
- Privacy, content-safety, security, and operational documentation

## Install / explore

For a release deployment, follow the upstream guide and configure the public URL:

```bash
curl -fsSL https://imageless.oss-cn-beijing.aliyuncs.com/runtime.sh | \
  sh -s -- up --public-url https://skillhub.your-company.com
```

The supported CLI is available as `@astron-team/skillhub`; change the bootstrap credentials and review the production security guidance before exposing an instance.

## Source

- **Repository:** [iflytek/skillhub](https://github.com/iflytek/skillhub)
- **License:** Apache-2.0
- **Maintainer ecosystem:** [iFlytek Astron](https://github.com/iflytek)
