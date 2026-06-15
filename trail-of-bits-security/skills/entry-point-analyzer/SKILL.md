---
name: entry-point-analyzer
description: "Analyzes smart contract codebases to identify state-changing entry points for security auditing. Detects externally callable functions that modify state, categorizes them by access level (public, admin, role-restricted, contract-only), and generates structured audit reports. Excludes view/pure/read-only functions. Use when auditing smart contracts (Solidity, Vyper, Solana/Rust, Move, TON, CosmWasm) or when asked to find entry points, audit flows, external functions, access control patterns, or privileged operations."
  Analyzes smart contract codebases to identify state-changing entry points for security auditing. Detects externally callable functions that modify state, categorizes them by access level, and generates structured audit reports.
metadata:
  sources:
    - kind: github-file
      repo: trailofbits/skills
      path: plugins/entry-point-analyzer/skills/entry-point-analyzer/SKILL.md
      commit: c070b9b5881183ea5f6e320ff06c46688becb13e
      attribution: Trail of Bits
      license: CC-BY-SA-4.0
      usage: referenced
---
