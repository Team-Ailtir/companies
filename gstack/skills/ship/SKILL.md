---
name: ship
description: "Ship workflow: detect + merge base branch, run tests, review diff, bump VERSION, update CHANGELOG, commit, push, create PR. (gstack)"
  Fully automated ship workflow: pre-flight, merge base, run tests, coverage
  audit, pre-landing review, design review, adversarial review, version bump,
  CHANGELOG generation, TODOS.md update, bisectable commits, push and PR
  creation, auto-sync docs via document-release.
metadata:
  sources:
    - kind: github-file
      repo: garrytan/gstack
      path: ship/SKILL.md
      commit: c7ae63201ab193a7dc7fb7e0d81238645111ffac
      attribution: Garry Tan
      license: MIT
      usage: referenced
---
