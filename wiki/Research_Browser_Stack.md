---
id: research-browser-stack
type: Tool
name: Research Browser Stack
created: 2026-09-11
updated: 2026-09-11
status: active
tags: [browser, ego-lite, web, research]
index: ./index.md
log: ./log.md
summary: ego-lite browser for web research. browser_navigate fails due to Chrome lock.
---

# Research Browser Stack

**Primary:** ego-lite at `C:\Users\q\ego-lite-windows`
**Launch:** `cd /c/Users/q/ego-lite-windows && node scripts/ego-browser-launch.mjs nodejs < task.js`
**Built-in:** browser_navigate FAILS (Chrome lock conflict)

Always end ego-lite tasks with `taskSpaces.complete()`.