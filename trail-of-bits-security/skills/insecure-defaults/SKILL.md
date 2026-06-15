---
name: insecure-defaults
description: "Detects fail-open insecure defaults (hardcoded secrets, weak auth, permissive security) that allow apps to run insecurely in production. Use when auditing security, reviewing config management, or analyzing environment variable handling."
  Detects insecure default configurations including hardcoded credentials, fallback secrets, weak authentication defaults, and dangerous values in production
metadata:
  sources:
    - kind: github-file
      repo: trailofbits/skills
      path: plugins/insecure-defaults/skills/insecure-defaults/SKILL.md
      commit: c070b9b5881183ea5f6e320ff06c46688becb13e
      attribution: Trail of Bits
      license: CC-BY-SA-4.0
      usage: referenced
---
