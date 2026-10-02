# openrig

OpenRig is an open-source *multi-agent harness* for running persistent teams of AI coding agents (Claude Code, Codex, and others) as a single managed system.

It focuses on practical, day-to-day “agent ops”:
- Define agent teams/topologies (RigSpec YAML)
- Launch and manage the team via a CLI (`rig up`, `rig ps`, `rig send`, etc.)
- Monitor and coordinate work from a terminal UI (TUI)
- Keep a stable, recoverable structure (snapshots/restore) so teams persist beyond one session

## Why it’s trusted / why it made the wiki

- Substantive open-source implementation (CLI + daemon + TUI + MCP server) rather than a thin prompt dump
- Clear documentation, operational details, and security/permission guidance
- Strong community traction and ongoing maintenance

## Source

- https://github.com/mvschwarz/openrig
