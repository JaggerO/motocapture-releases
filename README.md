# MotoCapture

**Know your car's history.**

A free, local-first desktop app for tracking vehicle maintenance, service history, and receipts. No account, no cloud sync, no subscription - your data lives on your own computer.

🌐 **[Website](https://jaggero.github.io/motocapture-releases/)** · ⬇️ **[Download latest release](https://github.com/JaggerO/motocapture-releases/releases/latest)** · 📖 **[Help & FAQ](https://jaggero.github.io/motocapture-releases/help.html)**

---

## What this repo is

This is the **public distribution point** for MotoCapture - installers, versioned releases, and the update manifests the app's built-in updater checks against. It doesn't contain the application's source code.

## Download

Grab the file for your platform from the [latest release](https://github.com/JaggerO/motocapture-releases/releases/latest):

| Platform | File pattern |
| --- | --- |
| macOS (Apple Silicon) | `MotoCapture_<version>_aarch64.dmg` |
| macOS (Intel) | `MotoCapture_<version>_x64.dmg` |
| Windows (x64) | `MotoCapture_<version>_x64-setup.exe` |
| Windows (ARM64) | `MotoCapture_<version>_arm64-setup.exe` |
| Linux | `MotoCapture_<version>_amd64.AppImage` |

Each release page also lists a few files that **aren't for direct download** - `latest.json`, any `.sig` files, `*.app.tar.gz`, and the "Source code" archives. Those are used by the app's auto-updater and build process, not something you need to open yourself.

**A note on install warnings:** builds aren't code-signed yet, so macOS Gatekeeper and Windows SmartScreen will both flag the app as being from an unidentified/unknown publisher on first launch. That's expected for now - right-click → Open on macOS, or "More info → Run anyway" on Windows SmartScreen, gets you past it. Code signing is on the roadmap.

On Linux, make the AppImage executable before running it:
```bash
chmod +x MotoCapture_*.AppImage
./MotoCapture_*.AppImage
```

## Staying updated

MotoCapture checks for updates only when you click "Check for updates" in Settings - nothing happens automatically in the background. New versions are published here as GitHub Releases.

## Support

Found a bug or have feedback? Use **Report a problem / send feedback** inside the app itself (Settings tab) - that's the supported channel, rather than filing an issue on this repo.

## Privacy

MotoCapture doesn't collect anything by default. Full details: [Privacy & Terms](https://jaggero.github.io/motocapture-releases/help.html#privacy).
