# Dotfiles

Personal configuration files for setting up development environments quickly and consistently across systems.

## Quick Setup

### Install Bash Aliases (Ubuntu/Debian)

```bash
# Download and install aliases
curl -o ~/.bash_aliases https://raw.githubusercontent.com/jvc3000/dotfiles/main/.bash_aliases
```

```bash
# Reload your shell configuration
source ~/.bashrc
```

### Verify Installation

```bash
# Test an alias
update
```

## What's Included

### Bash Aliases (`.bash_aliases`)
- **Navigation shortcuts**: `ll`, `la`, `l` for enhanced directory listings
- **Safety aliases**: Confirmation prompts for destructive operations
- **Color output**: Enhanced readability for common commands
- **Utility shortcuts**: Quick access to frequently used commands

## Supported Systems

- Ubuntu 20.04+
- Debian 10+
- Other Linux distributions with bash

## Usage Notes

- Ubuntu systems automatically source `.bash_aliases` if it exists
- Aliases take effect in new shell sessions or after running `source ~/.bashrc`
- To temporarily bypass an alias, prefix the command with `\` (e.g., `\ls`)

## Adding New Configurations

This repository will be expanded to include:
- `.gitconfig` - Git configuration and aliases
- `.vimrc` - Vim editor configuration  
- `.bashrc` - Custom bash configuration
- Install scripts for automated setup

## License

These configuration files are provided as-is for personal and educational use.
