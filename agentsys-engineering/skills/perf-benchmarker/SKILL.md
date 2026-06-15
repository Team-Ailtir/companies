---
name: perf-benchmarker
description: "Use when running performance benchmarks, establishing baselines, or validating regressions with sequential runs. Enforces 60s minimum runs (30s only for binary search) and no parallel benchmarks."
metadata:
  sources:
    - kind: github-file
      repo: agent-sh/agentsys
      path: .kiro/skills/perf-benchmarker/SKILL.md
      commit: 5fe2f5195466dce3e44f50145e821f612a6eb175
      attribution: Avi Fenesh
      license: MIT
      usage: referenced
---

Run sequential benchmarks with strict duration rules.
