# Local verification 2026-10-14 (Asia/Taipei)
- plugin.json vs agent-plugins 1.0.0 plugin.schema.json: PASS (jsonschema)
- mcp.json vs agent-plugins 1.0.0 mcp.schema.json: PASS
- .cursor-plugin/plugin.json vs cursor/plugins schemas/plugin.schema.json: PASS
- tools/list (Grok Bot authenticated MCP connection): 17 tools, names match README
- Unauthenticated POST /mcp/external: 401 + OAuth discovery; AS metadata has DCR, PKCE S256, auth method none
- Installed copy: ~/.cursor/plugins/local/pa-cafe (real dir, box)
- NOT proven: Cursor loader (@anysphere/cursor-plugins not on npm, no Cursor binary on box), Customize UI, logo render, OAuth inside Cursor, dual-manifest precedence in Cursor
