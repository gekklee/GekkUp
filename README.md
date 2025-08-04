# GekkUp

GekkUp is a simple system update script for EndeavourOS.

## Features

- Updates Flatpaks
- Refreshes package databases
- Shows pending updates (unless using --noconfirm)
- Prompts before upgrade (unless using --noconfirm)
- Always upgrades with --noconfirm

## Installation

```bash
sudo cp GekkUp /usr/bin/GekkUp
sudo chmod +x /usr/bin/GekkUp
```

## Usage

Interactive (default):

```bash
GekkUp
```

Non-interactive:

```bash
GekkUp --noconfirm
```

## License

This project is licensed under the GNU General Public License v3.0.
See LICENSE for details.
