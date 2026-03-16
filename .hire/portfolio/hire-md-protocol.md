---
# ═══════════════════════════════════════════════════════════════
# Portfolio Item — HIRE.md Protocol
# ═══════════════════════════════════════════════════════════════

# ─── Project Identity ────────────────────────────────────────
title: "HIRE.md Protocol"
url: "https://github.com/ominou5/HIRE-protocol"
role: "Creator & Maintainer"
status: active

# ─── Discoverability ─────────────────────────────────────────
tags:
  - "open-source"
  - "protocol-design"
  - "typescript"
  - "javascript"
  - "ai-agents"
  - "hiring-protocol"
  - "developer-tools"
  - "cli"
  - "hire-md"
  - "decentralized"
dates:
  start: "2026-03"
  end: "present"

---

## What I Built

HIRE.md is an open protocol for discovering, evaluating, and aligning AI agents and human developers — using only GitHub and a lightweight CLI. No servers. No databases. No SaaS middlemen. Just Markdown, YAML, and Git.

A project of [Agashic AI](https://agashic.ai), HIRE.md defines two core file formats — `hire.md` (candidate profile) and `job.md` (role spec) — and a CLI tool (`hire-cli`) that lets humans and AI agents search GitHub for matches, generate alignment reports, and initiate contact, all without leaving the terminal.

The protocol is designed to be readable by both humans and AI agents natively. A hiring agent can `hire-cli discover`, pull a candidate's `.hire/` folder, run `hire-cli engage`, and produce a structured alignment score — zero infrastructure required.

## Key Outcomes

- Defined an open, versioned spec (currently v0.2.0) adopted as the foundation of the `hire-cli` toolchain
- Built `hire-cli` in TypeScript — covers discovery, validation, engagement scoring, profile publishing, and contact routing
- Zero-dependency infrastructure: the entire hiring pipeline runs on GitHub + Git + Markdown
- Designed for both human readability and AI agent traversal from day one
- Part of the broader Agashic AI vision for decentralized, AI-native work coordination

## Tech Stack

- **CLI**: Node.js, TypeScript
- **Protocol Format**: Markdown + YAML frontmatter
- **Distribution**: npm (`hire-cli`)
- **Infrastructure**: GitHub (zero servers, zero databases)

## Verification

- **repo**: https://github.com/ominou5/HIRE-protocol
- **setup**: `npm install`
- **test**: `npm test`              # vitest — runs all unit tests
- **build**: `npm run build`        # tsc — clean TypeScript compile
- **lint**: `npm run lint`          # eslint src/
- **cli**: `hire-cli --version`     # confirms global install works
