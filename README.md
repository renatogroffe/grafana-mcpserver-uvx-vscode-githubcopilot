# grafana-mcpserver-uvx-vscode-githubcopilot
Configurações para uso do MCP Server do Grafana com uvx (packages Pythons) + Visual Studio Code + GitHub Copilot.

Arquivo **mcp.json**:

```json
{
	"servers": {
		"grafana": {
			"command": "uvx",
			"args": ["mcp-grafana"],
			"env": {
				"GRAFANA_URL": "http://localhost:3000"
			}
		}
	},
	"inputs": []
}
```
