# spec-kit-tutorial

This repository is a quickstart tutorial for [GitHub Spec-Kit](https://github.com/github/spec-kit).

## Prerequisites

- Windows PC
- GitHub Copilot AI model

## Installation

### Install uv

Install uv using winget:

```bash
winget install astral-sh.uv
```

For more installation options, see the [uv installation guide](https://docs.astral.sh/uv/getting-started/installation/#winget).

### Install speckit

Install speckit using uv:

```bash
uv tool install specify-cli --from git+https://github.com/github/spec-kit.git
```

## Usage

### Initialize in Current Project

To use spec-kit in your current project (be careful not to commit newly added prompt files):

```bash
# Initialize in current directory and skip git initialization
specify init . --ai copilot --no-git
```

### Using with VS Code

1. Open the repository in VS Code
2. Open the Copilot Chat UI
3. You will see spec-kit custom slash commands available

## Available Slash Commands

For a full list of available slash commands, see the [Spec-Kit README](https://github.com/github/spec-kit?tab=readme-ov-file#available-slash-commands).