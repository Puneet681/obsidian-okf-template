---
id: security-consent-policy
type: Rule
name: Security Consent Policy
created: 2026-09-11
updated: 2026-09-11
status: active
tags: [security, consent, privacy, rules]
index: ./index.md
log: ./log.md
summary: Ask before any install/modify/delete. No data exfiltration. Self-hosted only.
---

# Security & Consent Policy

**HARD RULE (always active):**
Before ANY command that installs, creates, modifies, or deletes data:
- git/GitHub operations
- Package installs
- DB writes/deletes

**ASK THE USER FIRST.** Explain what you plan to do and get approval.

**Privacy:**
- No data exfiltration to external services
- No leaking app data to the internet
- Self-hosted only (Tailscale for remote access)