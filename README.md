# Dotfiles

Personal configuration files for setting up development environments quickly and consistently across systems.

---

## What's Included

### Bash Aliases (`.bash_aliases`)

Enhanced bash aliases for improved productivity and safety.

**Features:**
- **Navigation shortcuts**: `ll` and `ls` for enhanced directory listings
- **Color output**: Enhanced readability for common commands
- **Utility shortcuts**: Quick access to frequently used commands
- **Safety aliases**: *(planned)* Confirmation prompts for destructive operations

**Installation:**

Download and install aliases:
```bash
curl -o ~/.bash_aliases https://raw.githubusercontent.com/jvc3000/dotfiles/main/.bash_aliases
```

Reload your shell configuration:
```bash
source ~/.bashrc
```

Test an alias:
```bash
update
```

**Usage Notes:**
- Ubuntu systems automatically source `.bash_aliases` if it exists
- Aliases take effect in new shell sessions or after running `source ~/.bashrc`
- To temporarily bypass an alias, prefix the command with `\` (e.g., `\ls`)

---

## Supported Systems

- Ubuntu 20.04+
- Debian 10+
- Other Linux distributions with bash

---

## Adding New Configurations

This repository will be expanded to include:
- `.gitconfig` - Git configuration and aliases
- `.vimrc` - Vim editor configuration  
- `.bashrc` - Custom bash configuration
- Install scripts for automated setup

---

## License

These configuration files are provided as-is for personal and educational use.
