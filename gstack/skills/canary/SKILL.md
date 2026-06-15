---
name: canary
description: "Post-deploy canary monitoring. (gstack)"
  Post-deploy monitoring. Watches live app via headless browser for console
  errors, performance regressions, page failures, visual anomalies. Alert on
  deltas not absolutes, transient tolerance (2+ consecutive checks). Default
  10-minute monitoring window. Baseline capture mode.
metadata:
  sources:
    - kind: github-file
      repo: garrytan/gstack
      path: canary/SKILL.md
      commit: c7ae63201ab193a7dc7fb7e0d81238645111ffac
      attribution: Garry Tan
      license: MIT
      usage: referenced
---
