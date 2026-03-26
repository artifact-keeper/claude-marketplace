# Artifact Keeper Claude Marketplace

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
