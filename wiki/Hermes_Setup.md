---
id: hermes-setup
type: Tool
name: Hermes Setup
created: 2026-09-11
updated: 2026-09-11
status: active
tags: [hermes, install, stt, avx2]
index: ./index.md
log: ./log.md
summary: Hermes install root, launch path, and the AVX2 STT fix.
---

# Hermes Setup

Hermes is installed at `D:\SutraQ Tech\SutraQ AI Company\Hermes`.

**Launch:** double-click `Hermes.exe` in `D:\SutraQ Tech\SutraQ AI Company\Hermes\release\win-unpacked\Hermes.exe`

**STT fix (AVX2):** The speech-to-text pipeline requires pinning specific versions in pyproject.toml/uv.lock — not by version number alone. venv-based fixes fail; pinning in the lock file works.