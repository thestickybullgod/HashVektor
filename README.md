# HashVektor v1.2 — Proprietary Edition
![License: Proprietary](https://img.shields.io/badge/License-Proprietary-red.svg)
![Platform: Windows](https://img.shields.io/badge/Platform-Windows-blue.svg)
![Version](https://img.shields.io/badge/Version-1.2.0-green.svg)

HashVektor is a fast, lightweight file hashing utility designed for Windows.  
It provides quick access to common cryptographic hash functions, batch hashing,  
and a clean interface suitable for both casual and technical users.

- Comfortable range: 1 – 10,000 files (no warnings, no UI lag, fast)
- Capable but expect a wait: 10,000 – 50,000 files (the app handles it, warning appears above 50k)
- Upper ceiling: ~100,000 files (cache pruning limit; batch is architecturally capable but very long-running)
- Baseline tab specifically: 5,000 – 20,000 files is the sweet spot since it's single-threaded

This is the **official proprietary release** of HashVektor v1.2.

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

HashVektor v1.2 uses **offline per‑machine activation**.

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

1. Launch `HashVektor_v1.2.exe`
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

The latest release of HashVektor v1.2 is available on:

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

---

## Integrity Verification & Technical Notes

- SHA‑256 checksum of `HashVektor_v1.2.exe`:
    `ba45b1beedb289db29faf2a8dd813d68eca006e9b2f4a84744c0dd69cca91ac1`
- Size: `610.34 KB`
- Modified: `2026-05-14 19:11:49`
- Version number: `1.2.0`
- VirusTotal Scan
    - [`HashVektor_v1.2.exe`](https://www.virustotal.com/gui/file/ba45b1beedb289db29faf2a8dd813d68eca006e9b2f4a84744c0dd69cca91ac1?nocache=1)
        — a few heuristic false positives; no confirmed malware
- Originally developed in PowerShell, compiled into a standalone executable
- No external dependencies
- No telemetry or data collection
- Future patches and improvements will be delivered as free updates to licensed users. To receive updates, please download and run the necessary HotFix. A HotFix is a file which, when double-clicked, prompts the user with the option to update the HashVektor executable.
- Please run the program in a folder.
- Please activate the latest version.
