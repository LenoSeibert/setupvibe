# SetupVibe

> The ultimate cross-platform development environment setup script — v0.34.0

Installs and configures a complete development stack in one command, supporting macOS and major Linux distributions.

## Key Features

- **Smart Privilege Elevation:** Uses `sudo` only where strictly necessary; most tools are installed in `$HOME/.local/bin`.
- **Auto-Update:** Automatically upgrades existing Homebrew packages during setup.
- **Modern Shell:** ZSH + Oh My Zsh + Starship with a curated set of plugins and aliases.
- **Optimized Tmux:** Pre-configured with TPM, intuitive keybindings, and window/pane numbering starting at 1.
- **AI-Ready:** Includes the latest AI CLI tools for developers.

## Documentation

| Language | Link |
|---|---|
| English | [docs/en/README.md](docs/en/README.md) |
| Português (Brasil) | [docs/pt-BR/README.md](docs/pt-BR/README.md) |

## Quick Start

### Desktop (macOS & Linux)

```bash
curl -sL https://raw.githubusercontent.com/promovaweb/setupvibe/refs/heads/main/desktop.sh | bash
```

### Server (Linux only)

```bash
curl -sL https://raw.githubusercontent.com/promovaweb/setupvibe/refs/heads/main/server.sh | bash
```

---

Maintained by [promovaweb.com](https://promovaweb.com) · Licensed under [GPL-3.0](LICENSE)
