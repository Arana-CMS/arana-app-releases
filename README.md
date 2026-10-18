# arana-app-releases
19 September 2026

# Arana || App Downloads

Official release builds of **Arana**, the digital out-of-home (DOOH) signage player and content platform by [Traxx Technology](https://traxxtech.africa).

> This repository hosts installers only.

## Download (latest)

| Platform | File | Link |
|---|---|---|
| Windows 10/11 (64-bit) | `arana-setup.exe` | [Download](https://github.com/Arana-CMS/arana-app-releases/releases/download/v1.0.5/arana.exe) |
| Android | `arana.apk` | [Download](https://github.com/Arana-CMS/arana-app-releases/releases/download/v1.0.5/arana.apk) |

Older versions and release notes: [Releases](https://github.com/Arana-CMS/arana-app-releases/releases)

## Install

### Windows
1. Run `arana-setup.exe`.
2. If you see **"Windows protected your PC"**, click **More info → Run anyway**.
3. Follow the installer. Tick **Start at login** for unattended screens.

Updating: run the new installer. It upgrades in place; your settings are kept.

### Android
1. Open `arana.apk` on the device.
2. When prompted, allow **Install unknown apps** for your browser or file manager.
3. Tap **Install**.

Updating: install the new APK over the existing app. No need to uninstall.

## Verify your download

Each release lists a SHA-256 checksum per file. To compare:

```powershell
# Windows (PowerShell)
Get-FileHash .\arana-setup.exe -Algorithm SHA256
```
```bash
# macOS / Linux
shasum -a 256 arana.apk
```

Only install files downloaded from this repository or the official Arana website.

## Requirements

| Platform | Minimum |
|---|---|
| Windows | Windows 10 or 11, 64-bit |
| Android | Android <X.0> or later |

## Support

- Website: <https://getarana.com
- Email: albertmwai@dta.africa

Report issues through the contacts above rather than GitHub Issues.

---

© Traxx Technology. All rights reserved.
