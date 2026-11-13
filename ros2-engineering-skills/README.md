# ROS 2 Engineering Skills

A production-oriented Agent Skill for ROS 2 development and operations. It routes coding agents through focused references for workspace and package design, executors, DDS QoS, lifecycle nodes, tf2, ros2_control, Nav2, MoveIt 2, perception, safety, testing, runtime provenance, and deployment—while requiring evidence instead of guessing about live robot behavior.

## Why it is trustworthy

- Apache-2.0 licensed, versioned, and maintained with release notes and a documented release procedure.
- Includes static validators, regression tests, multi-distribution CI, installer verification, and evaluation-capture integrity checks.
- Clearly distinguishes software checks from runtime evidence, operator supervision, robot safety certification, and hardware stop functions.
- Provides explicit actuation-command warnings and conservative safety boundaries for commands that could move hardware.

## Key capabilities

- Progressive-disclosure `SKILL.md` router with 27 task-specific references and cross-cutting engineering principles.
- Guidance for QoS diagnosis, lifecycle and callback design, launch supervision, package structure, Nav2, ros2_control, perception, and deployment.
- Portable installation for Codex, Claude Code, Cursor, and Gemini CLI, plus a Claude Code plugin and hooks.
- Provenance manifests and verification for installed files, source-date checks, static validators, and ROS-focused test/evaluation tooling.

## Install

Claude Code plugin:

```bash
claude plugin marketplace add dbwls99706/ros2-engineering-skills
claude plugin install ros2-engineering@ros2-engineering-skills
```

For a knowledge-only installation in a compatible client:

```bash
git clone https://github.com/dbwls99706/ros2-engineering-skills.git
cd ros2-engineering-skills
python3 -m pip install -r requirements.txt
python3 scripts/install_skill.py --client codex
```

## Source

- Repository: https://github.com/dbwls99706/ros2-engineering-skills
- License: Apache-2.0
