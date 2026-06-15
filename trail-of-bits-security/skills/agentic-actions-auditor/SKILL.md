---
name: agentic-actions-auditor
description: "Audits GitHub Actions workflows for security vulnerabilities in AI agent integrations including Claude Code Action, Gemini CLI, OpenAI Codex, and GitHub AI Inference. Detects attack vectors where attacker-controlled input reaches AI agents running in CI/CD pipelines, including env var intermediary patterns, direct expression injection, dangerous sandbox configurations, and wildcard user allowlists. Use when reviewing workflow files that invoke AI coding agents, auditing CI/CD pipeline security for prompt injection risks, or evaluating agentic action configurations."
  Audits GitHub Actions workflows for security vulnerabilities in AI agent integrations (Claude Code Action, Gemini CLI, OpenAI Codex, GitHub AI Inference)
metadata:
  sources:
    - kind: github-file
      repo: trailofbits/skills
      path: plugins/agentic-actions-auditor/skills/agentic-actions-auditor/SKILL.md
      commit: c070b9b5881183ea5f6e320ff06c46688becb13e
      attribution: Trail of Bits
      license: CC-BY-SA-4.0
      usage: referenced
---
