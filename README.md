<p align="center">
  <img src="logo.png" width="96" alt="FORGEPOINT logo">
</p>

<h1 align="center">FORGEPOINT</h1>
<p align="center"><b>PC diagnostics &amp; IT workshop for Windows</b></p>

<p align="center">
  <a href="https://maggotzyt.github.io/forgepoint/"><b>Website</b></a> ·
  <a href="https://maggotzyt.github.io/forgepoint/#download"><b>Download</b></a>
</p>

---

FORGEPOINT is a native Windows app for PC technicians, repair shops and
advanced home users. It checks the hardware, reviews Windows health, runs
guided repairs and keeps track of customers, devices and repair tickets, all
on the machine it's running on.

## Download

Download from the **[website](https://maggotzyt.github.io/forgepoint/#download)**
or straight from the [`downloads`](downloads) folder here:

| File | What it is |
|------|------------|
| `FORGEPOINT-Setup-x64.exe` | Installer: Start Menu shortcut, uninstaller, data kept on upgrade |
| `FORGEPOINT-Portable-x64.zip` | Portable: unzip and run, no installation |
| `FORGEPOINT-Portable-arm64.zip` | Windows on ARM, **experimental** (built automatically, not yet tested on ARM hardware) |
| `SHA256SUMS.txt` | Checksums to verify your download |

> This repository holds the website and the finished downloads only. The
> FORGEPOINT source code is not published.

### Verify your download

```powershell
Get-FileHash .\FORGEPOINT-Setup-x64.exe -Algorithm SHA256
```

The result must match the line for that file in `SHA256SUMS.txt`.

### "Windows protected your PC"

FORGEPOINT isn't code-signed yet, so SmartScreen doesn't recognise the
publisher. If you downloaded it from this page and the checksum matches,
choose **More info → Run anyway**.

## Features

* **Dashboard**: health score, live CPU and memory, storage, uptime
* **Diagnostics**: 14 read-only hardware checks (CPU, memory, GPU, drives and SMART where available, battery, USB, PCI and more)
* **Windows Health**: activation, updates, Defender and firewall status (read-only), crash summary, restore points, SFC and DISM checks
* **Repair Centre**: SFC, DISM, cleanup, DNS flush, Windows Update reset and restore points, each explained and confirmed first
* **Driver Workshop**: driver inventory, problem devices, driver backup
* **IT Workshop**: customers, devices and repair tickets with printable PDFs
* **Software & Startup, Network Workshop, Script Workshop, Reports**

## Safety

* Read-only checks work without administrator rights.
* Anything that changes the system explains itself, shows the exact command and asks first.
* FORGEPOINT never disables Windows Defender or the firewall, never edits the registry silently, never removes drivers automatically and never runs downloaded scripts.
* No telemetry and no account. Customer records stay in a local database.

## Requirements

Windows 11 x64. Windows 10 is being tested.

## Reporting a problem

Open an [issue](https://github.com/MagGoTzYT/forgepoint/issues). For security
problems, see [SECURITY.md](SECURITY.md).

---

© 2026 MagGoTzYT. All rights reserved.
