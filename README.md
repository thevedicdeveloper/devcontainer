<h1 align="center">.devcontainer</h1>

```JSON
{
	"name": "Alpine",
	"image": "mcr.microsoft.com/devcontainers/base:alpine-3.18",
	"features": {
		"ghcr.io/devcontainers/features/git:1": {},
		"ghcr.io/devcontainers/features/github-cli:1": {},
		"ghcr.io/devcontainers/features/azure-cli:1": {},
		"ghcr.io/devcontainers/features/aws-cli:1": {},
		"ghcr.io/devcontainers/features/node:1": {}
	},
	"customizations": {
		"vscode": {
			"extensions": [
				// Fonts and Theme
				"GitHub.github-vscode-theme",
				"PKief.material-icon-theme",

				// Azure
				"ms-azuretools.vscode-azurevirtualmachines",
				"ms-azuretools.vscode-azurestorage",
				"ms-azuretools.vscode-azurestaticwebapps",
				"ms-azuretools.vscode-azureresourcegroups",
				"ms-azuretools.vscode-azurefunctions",
				"ms-azuretools.azure-dev",
				"ms-azuretools.vscode-cosmosdb",
				"ms-azuretools.vscode-azurecontainerapps",
				"ms-azuretools.vscode-azureappservice",
				"ms-vscode.azure-account",

				// Google Cloud
				"googlecloudtools.cloudcode",

				// UI and UX
				"figma.figma-vscode-extension",
				"ms-edgedevtools.vscode-edge-devtools",

				// Common Utitlities
				"njzy.stats-bar",

				"GitHub.vscode-pull-request-github",
				"GitHub.codespaces",
				"ms-vscode-remote.remote-containers",
				"ms-azuretools.vscode-docker",
				"ms-kubernetes-tools.vscode-kubernetes-tools",
				"redhat.vscode-yaml",
				"ms-dotnettools.csharp",
				"ms-dotnettools.csdevkit",
				"ms-dotnettools.vscode-dotnet-runtime",
				"ms-vscode.vscode-node-azure-pack",

			]
		}
	}
}
```


<details>
<summary>Angular</summary>

```JSON
{
	"name": "Alpine",
	"image": "mcr.microsoft.com/devcontainers/base:alpine-3.18",
	"features": {
		"ghcr.io/devcontainers/features/git:1": {},
		"ghcr.io/devcontainers/features/github-cli:1": {},
		"ghcr.io/devcontainers/features/azure-cli:1": {},
		"ghcr.io/devcontainers/features/aws-cli:1": {},
		"ghcr.io/devcontainers/features/node:1": {}
	},
	"customizations": {
		"vscode": {
			"extensions": [
				// Fonts and Theme
				"GitHub.github-vscode-theme",
				"PKief.material-icon-theme",

				// UI and UX
				"figma.figma-vscode-extension",
				"ms-edgedevtools.vscode-edge-devtools",

				// Common Utitlities
				"njzy.stats-bar",

				"GitHub.vscode-pull-request-github",
				"GitHub.codespaces",
				"ms-vscode-remote.remote-containers",
				"ms-azuretools.vscode-docker",
				"ms-kubernetes-tools.vscode-kubernetes-tools",
				"redhat.vscode-yaml",
				"ms-dotnettools.csharp",
				"ms-dotnettools.csdevkit",
				"ms-dotnettools.vscode-dotnet-runtime",
				"ms-vscode.vscode-node-azure-pack",

			]
		}
	}
}
```

</details>