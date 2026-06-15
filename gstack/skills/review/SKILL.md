---
name: review
description: "Pre-landing PR review. (gstack)"
  Pre-landing PR review with two-pass checklist. Pass 1 critical: SQL safety,
  race conditions, LLM trust boundaries, enum completeness. Pass 2 informational:
  side effects, magic numbers, dead code, test gaps. Adversarial review auto-scaled
  by diff size. Scope drift detection.
metadata:
  sources:
    - kind: github-file
      repo: garrytan/gstack
      path: review/SKILL.md
      commit: c7ae63201ab193a7dc7fb7e0d81238645111ffac
      attribution: Garry Tan
      license: MIT
      usage: referenced
---
