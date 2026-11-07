# Orbie for Mac

Mac installers and signed update artifacts for Orbie.

## Install

Download the universal `.dmg` from [the latest release](https://github.com/SimonStenelid/orbie-releases/releases/latest), open it and drag Orbie into Applications. It supports Apple Silicon and Intel Macs running macOS 12 or later. Eject the disk image before opening Orbie from Applications.

This build uses ad-hoc signing and is not notarized by Apple. macOS may block the first launch. If you trust this download, use System Settings → Privacy & Security → Open Anyway to approve this specific app. Do not disable system-wide security protections. Keychain may also request permission to access the app's saved login, including after updates.

## Updates

The app checks at startup and every six hours while running. Use “Check for updates” in the account menu for a manual check. Choose “Update and restart” to install a release. Updates are deferred while a chat reply is active.

Updates are verified using the app's embedded public key. This signature is separate from Apple developer signing. If an in-app update fails, install the latest DMG manually.
