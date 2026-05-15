# HashVektor v1.1 — Proprietary Edition
![License: Proprietary](https://img.shields.io/badge/License-Proprietary-red.svg)
![Platform: Windows](https://img.shields.io/badge/Platform-Windows-blue.svg)
![Version](https://img.shields.io/badge/Version-1.1.0-green.svg)

HashVektor is a fast, lightweight file hashing utility designed for Windows.  
It provides quick access to common cryptographic hash functions, batch hashing,  
and a clean interface suitable for both casual and technical users.

This is the **official proprietary release** of HashVektor v1.1.

---

## Features

- Portable **.exe** application — no installation required
- SHA‑256, SHA‑512, SHA‑1, MD5, CRC32, and additional hash algorithms
- **Single file** hashing with drag-and-drop support
- **Batch hashing** across files and folders with parallel processing
- **Baseline scanning** — create and compare directory snapshots to detect changes
- **Verify mode** — validate files against a saved hash manifest
- **Duplicate finder** — locate identical files across a folder tree
- **Explorer context menu** — right-click any file or folder to hash it instantly
- **Recent files** list with quick re-hash
- Copy-to-clipboard support with auto-copy option
- Clipboard hash detection (auto-populates comparison field)
- Dark mode and system theme sync
- Minimize to system tray
- Toast notifications on job completion
- Configurable output format — lowercase, UPPERCASE, `0x` hex prefix, or Base64
- Configurable data directory for cache and log files
- Optional verbose output and portable mode
- Fully offline — no data ever leaves your machine
- No PowerShell, .NET runtime, or admin rights required

---

## Licensing & Activation

HashVektor v1.1 uses **offline per‑machine activation**.

- Each purchase includes **one lifetime license** for a single machine.
- Activation is bound to your hardware ID.
- No internet connection is required.
- Activation data is stored securely in your Windows registry.
- If HashVektor is moved to a different machine, it will enter **Unlicensed Mode**.

### Unlicensed Mode Limitations
- Maximum of 15 files hashed per user (lifetime trial)
- Batch mode disabled  
- Activation prompt shown at launch  

### License Transfers
If you replace or retire your computer, you may request a **courtesy license transfer**.  
Because HashVektor uses offline activation, deactivation on the old machine is not enforced automatically.

---

## How to Activate

1. Launch `HashVektor_v1.0.exe`
2. Click **Activate License**
3. Supply your Machine ID
4. License key will be generated and supplied
5. Enter your license key
6. HashVektor will bind the key to your machine and unlock full functionality

Activation takes only a few seconds and does not require internet access.

---

## System Requirements

- Windows 10 or 11 (64‑bit)
- Fully portable EXE — no installation required
- No PowerShell required
- No .NET runtime required
- No admin permissions required

---

## Download

The latest release of HashVektor v1.1 is available on:

- **GitHub Releases**  
- **[PlanetArchives.org](http://planetarchives.org/HashVektor.html)** (official distribution)

---

## Security

HashVektor performs all hashing locally and never transmits data.  
No files, hashes, or metadata leave your machine.

For security issues, please report privately. See [SECURITY.md](SECURITY.md).

---

## Support

For licensing assistance, transfers, or technical support:

**Dustin Wayne Deen**  
PlanetArchives.org  
support@planetarchives.org

## Integrity Verification & Technical Notes

- SHA‑256 checksum of `HashVektor_HF-003_Patcher.exe`:
    `f29e1ebba7abefc0897d3f57873d95b231e679c00a2c255608d771ccf0447489`
- SHA‑256 checksum of `HashVektor_v1.0.exe` [LATEST VERSION]:
    `0da31f844e77432ea0371d1a816d0d9dfbd8b95033338f0b5cc47348df73752f`
- Size: `609.84 KB`
- Modified: `2026-05-14 16:38:30`
- Version number: `1.1.0`
- VirusTotal Scan
    - [`HashVektor_HF-003_Patcher.exe`](https://www.virustotal.com/gui/file/f29e1ebba7abefc0897d3f57873d95b231e679c00a2c255608d771ccf0447489?nocache=1)
        — a few heuristic false positives; no confirmed malware
    - [`HashVektor_v1.0.exe [LATEST VERSION]`](https://www.virustotal.com/gui/file/0da31f844e77432ea0371d1a816d0d9dfbd8b95033338f0b5cc47348df73752f?nocache=1)
        — a few heuristic false positives; no confirmed malware
- Originally developed in PowerShell, compiled into a standalone executable
- No external dependencies
- No telemetry or data collection
- To submit bug reports, please contact support@planetarchives.org
- Future patches and improvements will be delivered as free updates to licensed users. To receive updates, please download and run the necessary HotFix. A HotFix is a file which, when double-clicked, prompts the user with the option to update the HashVektor executable.
- Please run the program in a folder.
- Please activate the latest version.
