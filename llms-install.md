# Installing Flowra MCP

Flowra is a remote MCP server. No local install, no API key.

Add this to your client's MCP config:

```json
{ "mcpServers": { "flowra": { "url": "https://mcp.flowra.dev/mcp" } } }
```

On first use the client opens Flowra's OAuth sign-in in the browser. After sign-in, connect apps at https://flowra.dev and their tools appear automatically. Docs: https://docs.flowra.dev/guides/mcp
