# forge-core

The Forge bootstrap demo vault.

## What's inside

This vault contains a single snippet, `hello_registry`, which returns the
string `"hello registry"`. It exists to verify that the full Forge stack —
backend, plugin, registry, install machinery, cross-vault snippet
resolution, and execution — is working end-to-end.

## Install

From any Forge-enabled Obsidian vault:

```
[[install]] "forge-core"
```

## Use

Once installed, reference the snippet from your own vault:

```python
result = context.compute("forge-core/hello_registry")
# returns "hello registry"
```

If the call works, your Forge stack is wired correctly.

## License

Apache License 2.0 — see [LICENSE](LICENSE) and [NOTICE](NOTICE) for details.

## Part of the Forge ecosystem

- Main project: https://github.com/frmoded/forge
- Other vaults:
  - https://github.com/frmoded/forge-music
  - https://github.com/frmoded/forge-moda
