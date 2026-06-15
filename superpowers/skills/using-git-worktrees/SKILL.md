---
name: using-git-worktrees
description: "Use when starting feature work that needs isolation from current workspace or before executing implementation plans - ensures an isolated workspace exists via native tools or git worktree fallback"
metadata:
  sources:
    - kind: github-file
      repo: obra/superpowers
      path: skills/using-git-worktrees/SKILL.md
      commit: f2cbfbefebbfef77321e4c9abc9e949826bea9d7
      attribution: Jesse Vincent
      license: MIT
      usage: referenced
---

Creates isolated git worktrees with smart directory selection, safety verification (checks gitignore), auto-detects project setup (npm, cargo, poetry, go), and verifies clean test baseline.
