# Silent Wolf Labs Codex Plugins

Public Codex marketplace for plugins published by Silent Wolf Labs.

## Install this marketplace

```bash
codex plugin marketplace add Silent-Wolf-Labs/codex-plugins --ref main
```

## Available plugins

### Dependency Upgrade Audit

Researches dependency upgrades using authoritative compatibility and security
evidence before making the smallest safe migration.

Install the released version:

```bash
codex plugin add dependency-upgrade-audit@silent-wolf-labs
```

Start a new Codex conversation after installation so the skill is available.

## Releases

Each marketplace entry pins its plugin source to an immutable Git tag. To
publish a new plugin version, release and push a tag in the plugin's own
repository, then update that plugin's `ref` in
`.agents/plugins/marketplace.json`.
