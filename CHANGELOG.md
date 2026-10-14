# Changelog

All notable changes to this plugin are documented here.

## 0.2.1 - 2026-10-13

- The plugin's documentation link now opens the EQUIRE connect guide.

## 0.2.0 - 2026-10-13

- One EQUIRE plugin for Claude, ChatGPT, Codex, and Cursor, published from a single public repository with matching manifests for each host and one shared connection to `https://www.equire.ai/mcp`.
- New onboarding skill: connect EQUIRE, choose an organization, and learn what the assistant can and cannot change.
- Investment workflow skill, previously ChatGPT and Codex only, now ships to every host and covers document evidence across deals, deal notes, diligence items, review-item proposals, and the interactive EQUIRE workspace.
- Every skill now shares the same ground rules, including a confirmation step that states the exact change before any tool that writes or stages a change, no presentation of the assistant's own arithmetic as an EQUIRE figure, and rate changes reported in basis points.
- Underwriting what-if applies a basis-point change to the saved value, and market research keeps deal names, tenants, and prices out of web search requests and states when a run or attached report uses the organization's metered research allowance.
- Market research, portfolio triage, and underwriting what-if skills gained steps for metro trends, weekly activity, and proposal readback.
- 512 px PNG icon for directory listings.

## 0.1.x and earlier

- Separate packages for Claude (five workflow skills) and for ChatGPT and Codex (one investment workflow skill), each connecting to the same EQUIRE server.
