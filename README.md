# Loxone Smart Home (OpenClaw Skill)

[![AgentAudit Security](https://img.shields.io/badge/AgentAudit-Safe-brightgreen?logo=data:image/svg%2Bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI+PHBhdGggZmlsbD0id2hpdGUiIGQ9Ik0xMiAxTDMgNXY2YzAgNS41NSAzLjg0IDEwLjc0IDkgMTIgNS4xNi0xLjI2IDktNi40NSA5LTEyVjVsLTktNHoiLz48L3N2Zz4=)](https://www.agentaudit.dev/skills/loxone)


This repository contains the OpenClaw skill definition in **[`SKILL.md`](./SKILL.md)**.

## ClawHub
- Skill page: https://clawhub.ai/skills/loxone
- Install:
  ```bash
  clawhub install loxone --registry "https://auth.clawdhub.com"
  ```

## Local development
- Create a local `config.json` from `config.json.example` (this file is **gitignored**).
- Run scripts from the skill folder, e.g.:
  ```bash
  python3 scripts/loxone.py rooms
  ```

## Documentation

- [SKILL.md](SKILL.md) — agent-facing reference (commands, behavior, limitations)
- [SETUP.md](SETUP.md) — prerequisites, configuration, and setup instructions
- [ClawHub](https://www.clawhub.com/skills/loxone) — install via ClawHub registry
