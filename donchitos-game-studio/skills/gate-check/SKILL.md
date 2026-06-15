---
name: gate-check
description: "Validate readiness to advance between development phases. Produces a PASS/CONCERNS/FAIL verdict with specific blockers and required artifacts. Use when user says 'are we ready to move to X', 'can we advance to production', 'check if we can start the next phase', 'pass the gate'."
metadata:
  sources:
    - kind: github-file
      repo: Donchitos/Claude-Code-Game-Studios
      path: .claude/skills/gate-check/SKILL.md
      commit: 984023ddac0d5e27624f2baacde6105e45de375f
      attribution: Donchitos
      license: MIT
      usage: referenced
---

Quality gate validation.
