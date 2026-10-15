# Changelog

All notable changes to this plugin are documented here.

## 0.2.5 - 2026-10-15

- Adds the ChatGPT demo recording link to the OpenAI review metadata; no tool or skill behavior change.

## 0.2.4 - 2026-10-14

- Listing category is now Finance, which matches the plugin's commercial real estate investment purpose; no tool or skill behavior change.

## 0.2.3 - 2026-10-14

- Listing copy rewritten around the analyst's IC preparation; no tool or skill behavior change.

## 0.2.2 - 2026-10-14

- Market research skill: attaching a report now links and indexes it without reading its figures, so a linked-only result is expected. Figures come from the next research run or Continue fact review. Web pages may be turned off on a deployment, while PDF links are supported (a PDF can still be unreachable). Attaching a report that is already linked to the deal reports it as already linked without fetching it again.
- Retrying named report sources now reports skipped sources with a reason, and refuses before starting a run when none of the named sources can be retried.
- A prospect's source count now reads as unknown rather than zero when it could not be read.

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
