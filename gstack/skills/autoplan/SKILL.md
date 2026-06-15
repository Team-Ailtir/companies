---
name: autoplan
description: "Auto-review pipeline — reads the full CEO, design, eng, and DX review skills from disk and runs them sequentially with auto-decisions using 6 decision principles. (gstack)"
  Fully automated review pipeline: CEO, Design, and Eng reviews with
  auto-decisions using 6 principles (completeness, boil lakes, pragmatic,
  DRY, explicit over clever, bias toward action). Only pauses for premise
  confirmation. Classifies decisions as Mechanical (silent) or Taste
  (surfaced at final gate).
metadata:
  sources:
    - kind: github-file
      repo: garrytan/gstack
      path: autoplan/SKILL.md
      commit: c7ae63201ab193a7dc7fb7e0d81238645111ffac
      attribution: Garry Tan
      license: MIT
      usage: referenced
---
