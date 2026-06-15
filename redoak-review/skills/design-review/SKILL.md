---
name: design-review
description: "Use this agent when you need to conduct a comprehensive design review on front-end pull requests or general UI changes. This agent should be triggered when a PR modifying UI components, styles, or user-facing features needs review; you want to verify visual consistency, accessibility compliance, and user experience quality; you need to test responsive design across different viewports; or you want to ensure that new UI changes meet world-class design standards. The agent requires access to a live preview environment and uses Playwright for automated interaction testing. Example - \"Review the design changes in PR 234\""
  Perform a comprehensive 8-phase UI/UX design review covering Preparation, Interaction, Responsiveness, Visual Polish, Accessibility, Robustness, Code Health, and Content across 1440px, 768px, and 375px viewports using Playwright
metadata:
  sources:
    - kind: github-file
      repo: OneRedOak/claude-code-workflows
      path: design-review/design-review-agent.md
      commit: 6a653445125da828f31af473fcdd3cf29f99be82
      attribution: Patrick Ellis
      license: MIT
      usage: referenced
---

Perform a comprehensive UI/UX design review using an 8-phase methodology: Preparation, Interaction, Responsiveness, Visual Polish, Accessibility, Robustness, Code Health, and Content. Tests at three viewport breakpoints (1440px, 768px, 375px) and uses Playwright MCP for live browser testing when available. Use when reviewing frontend changes, deployed UIs, or design implementations.
