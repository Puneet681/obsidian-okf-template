---
id: hardware-profile
type: Tool
name: Hardware Profile
created: 2026-09-11
updated: 2026-09-11
status: active
tags: [hardware, machine, drives, caches]
index: ../index.md
log: ../log.md
summary: Machine specs and the hard D:-drive data rule.
---

# Hardware Profile

- **CPU:** Intel i5-8300H — AVX2 only, no AVX-512
- **GPU:** GTX 1050 4GB (cannot run InstantMesh/TripoSR/Hunyuan3D — need 6–8GB)
- **RAM:** 16GB
- **OS:** Windows 11 (bash/MSYS terminal)

## Drive rules
- **C: fills easily** (~6GB free, 119GB total). Keep ALL installs/caches/data on **D:**.
- **D:-DRIVE RULE (hard, immutable):** ALL installs/data go to `D:\SutraQ Tech\SutraQ AI Company\Hermes`. NEVER install on C:. If C: is truly unavoidable, ask the user 2–3 times before proceeding.
- From 2026-08-30: nothing new is allowed to install on C: under any circumstances.