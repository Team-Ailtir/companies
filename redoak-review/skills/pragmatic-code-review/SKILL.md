---
name: pragmatic-code-review
description: "Use this agent when you need a thorough code review that balances engineering excellence with development velocity. This agent should be invoked after completing a logical chunk of code, implementing a feature, or before merging a pull request. The agent focuses on substantive issues but also addresses style.\\n\\nExamples:\\n- <example>\\n  Context: After implementing a new API endpoint\\n  user: \"I've added a new user authentication endpoint\"\\n  assistant: \"I'll review the authentication endpoint implementation using the pragmatic-code-review agent\"\\n  <commentary>\\n  Since new code has been written that involves security-critical functionality, use the pragmatic-code-review agent to ensure it meets quality standards.\\n  </commentary>\\n</example>\\n- <example>\\n  Context: After refactoring a complex service\\n  user: \"I've refactored the payment processing service to improve performance\"\\n  assistant: \"Let me review these refactoring changes with the pragmatic-code-review agent\"\\n  <commentary>\\n  Performance-critical refactoring needs review to ensure improvements don't introduce regressions.\\n  </commentary>\\n</example>\\n- <example>\\n  Context: Before merging a feature branch\\n  user: \"The new dashboard feature is complete and ready for review\"\\n  assistant: \"I'll conduct a comprehensive review using the pragmatic-code-review agent before we merge\"\\n  <commentary>\\n  Complete features need thorough review before merging to main branch.\\n  </commentary>\\n</example>"
  Perform a 7-tier hierarchical code quality review covering Architecture, Functionality, Security, Maintainability, Testing, Performance, and Dependencies with triage levels (Critical/Blocker, Improvement, Nit)
metadata:
  sources:
    - kind: github-file
      repo: OneRedOak/claude-code-workflows
      path: code-review/pragmatic-code-review-subagent.md
      commit: 6a653445125da828f31af473fcdd3cf29f99be82
      attribution: Patrick Ellis
      license: MIT
      usage: referenced
---

Perform a structured code quality review using the Pragmatic Quality framework. Reviews code through a 7-tier hierarchy — Architecture, Functionality, Security, Maintainability, Testing, Performance, Dependencies — and triages every finding as Critical/Blocker, Improvement, or Nit. Use when reviewing pull requests, feature branches, or entire codebases for code quality.
