---
title: Debug Claude Code OOM issue + fix coding agent integration
category: technical
list_state: P3
created_date: 2026-02-08
due_date: null
estimated_time: 120
---

# Debug Coding Agent (Claude Code) with OpenClaw

## Context
Claude Code crashed twice with OOM (signal 9) when building freight visualizer. Need to investigate why and fix.

## Root Cause Hypothesis
- VPS is 2vCPU/4GB RAM (borderline for Claude Code + npm deps)
- Interactive terminal UI + node dev server + hot reload = high memory
- Possibly hitting system OOM killer

## Next Actions
- [ ] Check VPS memory usage during future Claude Code runs
- [ ] Options:
  1. Upgrade VPS to 8GB RAM ($24/mo)
  2. Build locally on Mac/Windows instead
  3. Use sub-agent to spawn isolated build session
  4. Defer Claude Code for non-time-sensitive projects
- [ ] Test with smaller project (not freight visualizer)
- [ ] Document workaround in TOOLS.md

## Notes
- Freight visualizer MVP still useful, but not urgent
- Can resume after 100-conversation sprint
- This is "when you have breathing room" work

## Progress Log
- 2026-02-08: Task created - P3 (chill time project)