# Artifact Keeper Claude Marketplace

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/artifact-keeper/.github/main/brand/logo-horizontal-dark.png">
    <img alt="Artifact Keeper" src="https://raw.githubusercontent.com/artifact-keeper/.github/main/brand/logo-horizontal-light.png" width="360">
  </picture>
</p>

Claude Code plugin marketplace for the Artifact Keeper team.

## Available Plugins

| Plugin | Description |
|--------|-------------|
| [ak-audit-agent](https://github.com/artifact-keeper/artifact-keeper-audit-agent) | Multi-lens audit team with 8 specialist reviewers |

## Installation

Add this marketplace to Claude Code:

```
/plugin marketplace add artifact-keeper/claude-marketplace
```

Then install any plugin:

```
/plugin install ak-audit-agent@ak-marketplace
```

## Adding Plugins

To add a new plugin to this marketplace, add an entry to `.claude-plugin/marketplace.json` with the plugin's name, source, and description.
