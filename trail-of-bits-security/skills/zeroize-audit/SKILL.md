---
name: zeroize-audit
description: "Detects missing zeroization of sensitive data in source code and identifies zeroization removed by compiler optimizations, with assembly-level analysis, and control-flow verification. Use for auditing C/C++/Rust code handling secrets, keys, passwords, or other sensitive data."
  Detects missing or compiler-optimized zeroization of sensitive data with assembly and control-flow analysis
metadata:
  sources:
    - kind: github-file
      repo: trailofbits/skills
      path: plugins/zeroize-audit/skills/zeroize-audit/SKILL.md
      commit: c070b9b5881183ea5f6e320ff06c46688becb13e
      attribution: Trail of Bits
      license: CC-BY-SA-4.0
      usage: referenced
---
