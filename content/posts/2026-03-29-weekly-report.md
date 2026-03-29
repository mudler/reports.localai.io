---
title: "Weekly Report - 2026-03-29"
date: 2026-03-29
tags: [weekly, report, activity]
categories: [reports]
---

## Weekly Report: March 22 - March 29, 2026

### Leader Contributions

**PRs Opened by Leader:**
- https://github.com/mudler/LocalAI/pull/9160 - chore: Update ggml-org/llama.cpp
- https://github.com/mudler/LocalAI/pull/9155 - fix: Use SDPA instead of flash_attention_2 for ROCm/hipblas environments
- https://github.com/mudler/LocalAI/pull/9148 - Fix watchdog_enabled setting persistence
- https://github.com/mudler/LocalAI/pull/9146 - fix: X-Forwarded-Prefix not working in reverse proxy scenarios
- https://github.com/mudler/LocalAI/pull/9147 - fix: Use SDPA instead of flash_attention_2 for ROCm/hipblas environments (closed)
- https://github.com/mudler/LocalAI/pull/9131 - Fix CI failures for Unsloth fine-tuning feature (closed)
- https://github.com/mudler/LocalAI/pull/9130 - chore(model gallery): add 1 new models via gallery agent (closed)
- https://github.com/mudler/LocalAI/pull/9129 - chore(model gallery): add 1 new models via gallery agent (closed)
- https://github.com/mudler/LocalAI/pull/9126 - feat: Unsloth fine-tuning backend implementation (closed)

**PRs Merged by Leader:**
- https://github.com/mudler/LocalAI/pull/9144 - chore: Update ggml-org/llama.cpp
- https://github.com/mudler/LocalAI/pull/9128 - chore: Update ace-step/acestep.cpp
- https://github.com/mudler/LocalAI/pull/9127 - chore: Update ggml-org/llama.cpp
- https://github.com/mudler/LocalAI/pull/9123 - chore: Update ggml-org/llama.cpp
- https://github.com/mudler/LocalAI/pull/9103 - feat(swagger): update swagger
- https://github.com/mudler/LocalAI/pull/9102 - chore: Update ggml-org/llama.cpp

**PRs Closed (not merged) by Leader:**
- https://github.com/mudler/LocalAI/pull/9158 - chore(model gallery): add 1 new models (closed)
- https://github.com/mudler/LocalAI/pull/9157 - chore(model gallery): add 1 new models (closed)
- https://github.com/mudler/LocalAI/pull/9152 - chore(model gallery): add 1 new models (closed)

**Tasks Dispatched:**
- Multiple task files processed and dispatched to agents
- State reconciliation performed - reclaimed queues from stale agents
- Weekly routine executions completed

### Team/Agent Contributions

**PRs Merged by Agents:**
- https://github.com/mudler/LocalAI/pull/9150 - fix(voxcpm): Force using a recent voxcpm version (richiejp)
- https://github.com/mudler/LocalAI/pull/9142 - fix(coqui,nemo,voxcpm): Add dependencies (richiejp)
- https://github.com/mudler/LocalAI/pull/9141 - feat: Merge repeated log lines (richiejp)
- https://github.com/mudler/LocalAI/pull/9137 - chore: Update ggml-org/llama.cpp
- https://github.com/mudler/LocalAI/pull/9136 - feat(swagger): update swagger
- https://github.com/mudler/LocalAI/pull/9135 - fix: implement encoding_format=base64 (walcz-de)
- https://github.com/mudler/LocalAI/pull/9134 - fix(docs): Use notice instead of alert (richiejp)
- https://github.com/mudler/LocalAI/pull/9121 - chore(deps): bump go-containerregistry (dependabot)
- https://github.com/mudler/LocalAI/pull/9118 - chore(deps): bump modelcontextprotocol/go-sdk (dependabot)
- https://github.com/mudler/LocalAI/pull/9116 - chore(deps): bump mudler/skillserver (dependabot)
- https://github.com/mudler/LocalAI/pull/9114 - chore(deps): bump peter-evans/create-pull-request (dependabot)
- https://github.com/mudler/LocalAI/pull/9110 - chore(deps): bump actions/checkout (dependabot)
- https://github.com/mudler/LocalAI/pull/9107 - fix(downloader): Rewrite full https HF URI (richiejp)

**Notable Agent Work:**
- PR #8793: Fix model parameter in neutts-air gallery definition (awaiting review)
- PR #9054: Feature request for model fine-tuning support via Unsloth backend
- PR #9138: FlashAttention2 availability issue in hipblas Docker images

### LocalAI Repository Changes

**Notable Commits/Updates:**
- Multiple llama.cpp updates (PRs #9160, #9144, #9137, #9128, #9127, #9123, #9102)
- SDPA fix for ROCm/hipblas environments (PR #9155)
- Watchdog setting persistence fix (PR #9148)
- X-Forwarded-Prefix reverse proxy fix (PR #9146)

### Metrics Summary

**Leader PR Activity (Past Week):**
- PRs Opened: 9
- PRs Merged: 6
- PRs Closed (not merged): 3

**Total PR Activity (All Contributors):**
- PRs Merged: 15+
- PRs Open: 10+
- PRs Closed: 10+

### Upcoming Focus Areas

1. **PR Review Follow-up**: Address pending review comments on open PRs
2. **Weekly Maintenance**: Continue routine board synchronization and task dispatch
3. **Issue Triage**: Monitor and triage new issues in LocalAI repository
4. **CI Stability**: Monitor CI status for open PRs, especially those with failing checks

### Notes

- State reconciliation completed - reclaimed queues from stale agents (BACKGROUND-MONITOR, team-coding-agent-3-small)
- Healthy agents: team-coding-agent-1, team-coding-agent-2 (both idle)
- No backlog tasks pending
- Several PRs awaiting human review (PRs #8793, #8880, #8948, #8955, #9146, #9148)
