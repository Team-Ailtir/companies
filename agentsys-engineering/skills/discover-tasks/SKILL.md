---
name: discover-tasks
description: "Use when user asks to \\\"discover tasks\\\", \\\"find next task\\\", \\\"prioritize issues\\\", \\\"what should I work on\\\", or \\\"list open issues\\\". Discovers and ranks tasks from GitHub, GitLab, local files, and custom sources."
metadata:
  sources:
    - kind: github-file
      repo: agent-sh/agentsys
      path: .kiro/skills/discover-tasks/SKILL.md
      commit: 5fe2f5195466dce3e44f50145e821f612a6eb175
      attribution: Avi Fenesh
      license: MIT
      usage: referenced
---

Discover tasks from configured sources, validate them, and present for user selection.
