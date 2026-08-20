# Instalação detalhada

ECRVSP Veículos: Número de Motor na BIN é um servidor MCP remoto. Aponte seu cliente pra `https://api.mcp.ai/p_ecrvsp_veiculos_motor`. Snippets rápidos: [INSTALL.md](../INSTALL.md).

| Cliente | URL | Auth |
|---|---|---|
| Claude Desktop | `https://api.mcp.ai/p_ecrvsp_veiculos_motor` | OAuth 2.1 ou agent-auth |
| Cursor | `https://api.mcp.ai/p_ecrvsp_veiculos_motor` | OAuth 2.1 ou agent-auth |
| VS Code (Copilot) | `https://api.mcp.ai/p_ecrvsp_veiculos_motor` | OAuth 2.1 ou agent-auth |

A config JSON é a mesma em todos: só a URL, sem headers.

## Desinstalar

Remova o bloco `mcpServers.ecrvsp_veiculos_motor` (ou `servers.ecrvsp_veiculos_motor` no VS Code) do config do cliente e reinicie.
