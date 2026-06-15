---
name: land-and-deploy
description: "Land and deploy workflow. (gstack)"
  Merge PR, wait for deploy, verify production health. 10-step workflow:
  pre-flight, CI check, readiness gate, merge (respects merge queue), detect
  platform, wait for deploy, canary verification, revert option, deploy report.
  Auto-detects Fly, Render, Vercel, Netlify, Heroku, GitHub Actions.
metadata:
  sources:
    - kind: github-file
      repo: garrytan/gstack
      path: land-and-deploy/SKILL.md
      commit: c7ae63201ab193a7dc7fb7e0d81238645111ffac
      attribution: Garry Tan
      license: MIT
      usage: referenced
---
