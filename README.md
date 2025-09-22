# Softswitch [![AUR version](https://img.shields.io/aur/version/softswitch)](https://aur.archlinux.org/packages/softswitch)

A simple, fast CLI for switching between installed PHP versions on Arch Linux.

## Installation

Install from the AUR using your favorite helper:

```bash
yay -S softswitch
```

## Usage

### List available versions

```bash
softswitch list
```

### Switch to a version (requires sudo)

```bash
sudo softswitch use php82
```

### Check current status

```bash
softswitch status
```