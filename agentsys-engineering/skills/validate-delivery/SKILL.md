---
name: validate-delivery
description: "Use when user asks to \\\"validate delivery\\\", \\\"check readiness\\\", or \\\"verify completion\\\". Runs tests, build, and requirement checks with pass/fail instructions."
metadata:
  sources:
    - kind: github-file
      repo: agent-sh/agentsys
      path: .kiro/skills/validate-delivery/SKILL.md
      commit: 5fe2f5195466dce3e44f50145e821f612a6eb175
      attribution: Avi Fenesh
      license: MIT
      usage: referenced
---

Autonomously validate that a task is complete and ready to ship.
