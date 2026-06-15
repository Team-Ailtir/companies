---
name: careful
description: "Safety guardrails for destructive commands. (gstack)"
  Warns before destructive commands (rm -rf, DROP TABLE, force-push, git reset
  --hard, kubectl delete, docker force-rm). Session-scoped. Exceptions for
  common temp dirs (node_modules, .next, __pycache__).
metadata:
  sources:
    - kind: github-file
      repo: garrytan/gstack
      path: careful/SKILL.md
      commit: c7ae63201ab193a7dc7fb7e0d81238645111ffac
      attribution: Garry Tan
      license: MIT
      usage: referenced
---
