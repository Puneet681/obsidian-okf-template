# OKF Vault Template

An **OKF-compliant Obsidian vault template** — a portable structure for knowledge management that survives agent context resets.

## What is OKF?

**OKF = Obsidian Knowledge Files** — a minimal, agent-friendly convention:

- **Atomic notes** — one idea per note, stored flat in `wiki/`
- **Machine-readable frontmatter** — every note carries `id`, `created`, `updated`, `index`, `log` plus domain fields
- **Navigation via index** — `index.md` at the root is the MOC hub linking to every note
- **Change log** — `log.md` records every meaningful change, reverse-chronological
- **Standard markdown links** — `[Label](./wiki/File.md)`, never `[[wiki links]]`, so any renderer/parser works

## Structure

```
vault/
├── index.md          # Root index / MOC — navigation hub, links to every wiki note
├── log.md            # Reverse-chronological change log
├── wiki/             # Atomic knowledge notes (one idea per note)
│   ├── hardware-profile.md
│   ├── hermes-setup.md
│   └── ...
├── raw/              # Raw captures, unsorted scratch, imports (future)
└── .gitkeep
```

## Frontmatter convention

Every `wiki/*.md` note:

```yaml
---
id: <kebab-case-slug>
type: Tool | Person | Rule | Workflow | Index | Design | Project | ...
name: <Human Readable Name>
created: 2026-09-11
updated: 2026-09-11
status: active
tags: [tag1, tag2]
summary: One-line summary of what this note holds.
index: ../index.md
log: ../log.md
---
```

## Usage

1. Copy `wiki/` notes, update frontmatter to your domain.
2. Replace `index.md` section links with your own notes.
3. Append to `log.md` with today's date whenever you change anything.
4. Dump unsorted captures into `raw/` until you atomic-ize them into `wiki/`.

## License

MIT — use it, fork it, ship it.