---
id: okf-memory-core
type: Workflow
name: OKF Memory Core
created: 2026-09-11
updated: 2026-09-11
status: active
tags: [memory, okf, obsidian, architecture]
index: ../index.md
log: ../log.md
summary: The OKF vault is the primary long-term memory core for all bots, agents, and sessions.
---

# OKF Memory Core

The OKF vault is the primary long-term memory. All agent sessions load this vault as context.

## Structure
- `wiki/` — atomic knowledge notes (one idea per note)
- `index.md` — root navigation (MOC)
- `log.md` — reverse-chronological change log
- `raw/` — raw captures (future)

## Rules
1. Check the vault first before answering anything related to infrastructure, projects, or setup.
2. Write findings back to the vault as OKF notes.
3. Keep markdown links relative and standard: `[Label](./wiki/Note.md)` — never `[[wiki links]]`.