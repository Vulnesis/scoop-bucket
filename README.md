<p align="center">
  <img src="strix.svg" alt="Strix, the Vulnesis mascot" width="110">
</p>

# Vulnesis Scoop Bucket

[![Ask DeepWiki](https://deepwiki.com/badge.svg)](https://deepwiki.com/Vulnesis/scoop-bucket)

[Scoop](https://scoop.sh/) bucket for [Vulnesis CLI](https://github.com/Vulnesis/cli) on Windows.

## Installation

```powershell
# Add the bucket
scoop bucket add vulnetix https://github.com/Vulnesis/scoop-bucket

# Install the CLI
scoop install vulnetix

# Verify installation
vulnetix --version
```

## Upgrade

```powershell
scoop update vulnetix
```

## Uninstall

```powershell
scoop uninstall vulnetix

# Optionally remove the bucket
scoop bucket rm vulnetix
```

## Available Packages

| Package | Description |
|---------|-------------|
| `vulnetix` | Vulnesis CLI for vulnerability management |
| `belai` | Role-managed, injection-safe LLM coding harness |
| `keleustes` | Desktop Software Factory that coordinates belai hosts |

## Links

- [Vulnesis CLI Documentation](https://docs.cli.vulnes.is/)
- [GitHub Releases](https://github.com/Vulnesis/cli/releases)

## License

This repository is licensed under the [GNU Affero General Public License v3.0](LICENSE). Each manifest's `license` field states the licence of the software it installs.
<!-- ci-touch: 2026-08-24T20:54:39Z -->