# edge-apps-claude-config

Shared Claude AI configuration for Screenly Edge App repositories.

## Usage

Add this repo as a git submodule in your Edge App repository:

```bash
git submodule add https://github.com/Screenly/edge-apps-claude-config .claude
```

When cloning a repo that uses this submodule:

```bash
gh repo clone Screenly/<repo-name> -- --recurse-submodules
```

To update the submodule to the latest version:

```bash
git submodule update --remote .claude
```
