---
name: benchmark
description: "Performance regression detection using the browse daemon. (gstack)"
  Performance regression detection. Captures TTFB, FCP, LCP, bundle sizes,
  request counts. Regression thresholds: timing >50% or >500ms. Baseline
  comparison, trend tracking, budget compliance scorecard.
metadata:
  sources:
    - kind: github-file
      repo: garrytan/gstack
      path: benchmark/SKILL.md
      commit: c7ae63201ab193a7dc7fb7e0d81238645111ffac
      attribution: Garry Tan
      license: MIT
      usage: referenced
---
