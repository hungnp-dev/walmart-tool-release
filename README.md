# CD-TEAM Monitor

Official Windows releases for **CD-TEAM Monitor**, an operations tool for Walmart order monitoring and Google Sheets workflows.

## Latest Release

**v2026.09.24.109**

Download the latest executable from the [Releases](https://github.com/hungnp-dev/walmart-tool-release/releases/latest) page.

## Main Capabilities

- Backend-queued Walmart order checks
- MongoDB-backed order, sync, retry, and audit state
- Centralized employee, customer, and master Google Sheet configuration
- Automatic status synchronization back to Google Sheets
- Browser profile and bookmark management
- Fast master-order lookup from MongoDB
- Built-in update support for Windows VPS deployments

## Installation

1. Download **CD-TEAM-Monitor-*.exe** from the latest release.
2. Place it in a writable folder on the Windows VPS.
3. Start the application and connect it to the deployed Backend API.

Order history is stored in MongoDB. Only machine-local UI and browser files remain under **%APPDATA%\CD-Team Monitor**.

## Release Policy

Releases are built automatically by GitHub Actions from the **master** branch. Each release includes English release notes, a versioned executable, source commit information, and reproducible build metadata.

## Security

Private release assets include deployment defaults from source config. MongoDB credentials must be supplied through the protected runtime environment or private configuration and must not be committed to the executable. Microsoft Edge is used from the Windows installation and no third-party browser runtime is bundled.
