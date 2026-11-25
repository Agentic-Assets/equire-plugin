READ ~/AGENTS.md FIRST (skip if missing).

# EQUIRE plugin repository

Public distribution bundle for EQUIRE in Claude, ChatGPT, Codex, and Cursor: manifests, workflow skills, branding, and remote MCP connection metadata.

## Production application

[Agentic-Assets/EQUIRE](https://github.com/Agentic-Assets/EQUIRE) owns the production application at [www.equire.ai](https://www.equire.ai), the MCP server, OAuth, and canonical plugin source in `plugins/equire/`.
Make plugin payload changes there and mirror them here with its publish script; this repository owns only its root agent guidance, not application runtime code.

This repository root is the plugin root, so it has no root `CLAUDE.md`: plugins never load one, and the Claude directory flags it. The publish script removes it on every mirror run.
