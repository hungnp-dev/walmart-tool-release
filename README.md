# CD-TEAM Monitor

Official Windows releases for **CD-TEAM Monitor**, an operations tool for Walmart order monitoring and Google Sheets workflows.

## Latest Release

**v2026.09.01.86**

Download the latest executable from the [Releases](https://github.com/hungnp-dev/walmart-tool-release/releases/latest) page.

## Main Capabilities

- Scheduled and manual Walmart order checks
- Live, visible processing progress for every order
- Centralized employee, customer, and master Google Sheet configuration
- Automatic status synchronization back to Google Sheets
- Browser profile and bookmark management
- Telegram commands, notifications, and multi-order lookup
- Built-in update support for Windows VPS deployments

## Installation

1. Download **CD-TEAM-Monitor-*.exe** from the latest release.
2. Place it in a writable folder on the Windows VPS.
3. Start the application and configure Apps Script and Telegram locally.

Runtime configuration and order history are stored under **%APPDATA%\CD-Team Monitor** and are preserved when the EXE is replaced.

## Release Policy

Releases are built automatically by GitHub Actions from the **master** branch. Each release includes English release notes, a versioned executable, source commit information, and reproducible build metadata.

## Security

Private release assets include the bundled deployment defaults from source config. Runtime configuration and local history stay under **%APPDATA%\CD-Team Monitor**. Microsoft Edge is used from the Windows installation and no third-party browser runtime is bundled.
