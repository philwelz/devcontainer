# Development Containers

This repository contains Development Container configurations for different development environments. Development containers provide a consistent, isolated development environment across different machines.

## Available Configurations

### Python Environment
- Located in [.devcontainer/python/devcontainer.json](.devcontainer/python/devcontainer.json)
- Base image: `mcr.microsoft.com/devcontainers/base:<TAG>`
- Includes:
  - Python development tools
  - Common utilities
  - VS Code extensions for Python development and GitHub Copilot

### Azure Environment
- Located in [.devcontainer/azure/devcontainer.json](.devcontainer/azure/devcontainer.json)
- Base image: `mcr.microsoft.com/devcontainers/python:<TAG>`
- Includes:
  - Azure CLI
  - Terraform
  - VS Code extensions for Azure, Terraform, and Bicep development

## Features

- EditorConfig support for consistent coding styles
- GitHub Dependabot configuration for automated updates
- Pre-configured VS Code settings and extensions
- Common development utilities and tools

## Getting Started

1. Install Visual Studio Code and the Remote Development extension pack
2. Clone this repository
3. Open the repository in VS Code
4. Select the development container configuration you want to use
5. Click "Reopen in Container" when prompted

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.
