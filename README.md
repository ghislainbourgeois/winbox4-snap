# WinBox 4 Snap

A [Snap](https://snapcraft.io/) package for [WinBox 4](https://mikrotik.com/), the GUI management tool for Mikrotik network equipment running RouterOS or SwitchOS.

## About WinBox

WinBox is a lightweight graphical tool provided by Mikrotik for managing Mikrotik routers, switches, and access points. This snap bundles the official Linux release of WinBox 4 into a sandboxed Snap package.

## Installation

```bash
sudo snap install winbox4
```

## Usage

Launch WinBox from your application menu or run:

```bash
winbox
```

## Features

- Sandboxed and securely confined
- Automatically updates via the Snap store
- Works on all Snap-supported Linux distributions

## Requirements

- A Linux distribution that supports Snap packages
- Internet access to discover and manage Mikrotik devices

## License

The snap packaging code in this repository is licensed under the [GNU General Public License v3.0](LICENSE.md).

WinBox itself is proprietary software developed by Mikrotik. This snap merely packages the official WinBox binary distributed by Mikrotik. WinBox is subject to Mikrotik's proprietary license terms.