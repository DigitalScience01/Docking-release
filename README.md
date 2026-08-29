<div align="center">

<img src="https://raw.githubusercontent.com/DigitalScience01/Docking/main/assets/logo.png" alt="DockFlow Logo" width="160" height="160" style="border-radius: 20%; filter: drop-shadow(0px 8px 24px rgba(0, 240, 255, 0.45));" />

# DockFlow
### Molecular Docking, AI Protocol Advisory, 2D/3D Interaction Mapping & ADMET Screening Platform

[![Current Release](https://img.shields.io/badge/Release-v1.2.0-00f0ff.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/DigitalScience01/Docking-release/releases)
[![Platform](https://img.shields.io/badge/Platform-Windows%20x64-0078D6.svg?style=for-the-badge&logo=windows&logoColor=white)](https://github.com/DigitalScience01/Docking-release/releases)
[![Status](https://img.shields.io/badge/Status-Stable%20Production-10b981.svg?style=for-the-badge)](https://github.com/DigitalScience01/Docking-release/releases)
[![Python Runtime](https://img.shields.io/badge/Python-3.11%20Portable%20Embedded-3776AB.svg?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
[![Engine](https://img.shields.io/badge/AutoDock%20Vina-v1.2.7-E25A1C.svg?style=for-the-badge)](https://vina.scripps.edu/)
[![AI Advisor](https://img.shields.io/badge/Google%20Gemini%20AI-2.5%20Flash%20%2F%20Pro-8E24AA.svg?style=for-the-badge&logo=google&logoColor=white)](https://ai.google.dev/)
[![Bytenode Protected](https://img.shields.io/badge/Security-Bytenode%20V8%20Bytecode-47848F.svg?style=for-the-badge)](https://github.com/DigitalScience01/Docking)

<p align="center">
  Official production release hub for <b>DockFlow Desktop Suite</b>. Download the latest Windows setup installers, standalone portable packages, and differential auto-update manifests.
</p>

[📥 Download Latest Release (v1.2.0)](#-latest-release-v120-downloads) • [✨ Highlights](#-whats-new-in-v120) • [💻 System Requirements](#-system-requirements) • [🚀 Installation Guide](#-installation--setup-guide) • [🔐 License Activation](#-license-activation--support) • [📂 Source Code](https://github.com/DigitalScience01/Docking)

</div>

---

## 📦 Latest Release: v1.2.0 Downloads

| Package Type | File Name | Size | Architecture | Description |
| :--- | :--- | :--- | :--- | :--- |
| **Windows Installer (NSIS)** | [`DockFlow-Setup-1.2.0.exe`](https://github.com/DigitalScience01/Docking-release/releases/download/v1.2.0/DockFlow-Setup-1.2.0.exe) | ~256 MB | `x64` (64-bit) | Recommended for desktop PCs and laptops. Includes pre-bundled Python 3.11 runtime, desktop shortcuts, and auto-updater integration. |
| **Windows Portable** | [`DockFlow.1.2.0.exe`](https://github.com/DigitalScience01/Docking-release/releases/download/v1.2.0/DockFlow.1.2.0.exe) | ~255 MB | `x64` (64-bit) | Zero-installation standalone executable with full embedded cheminformatics engine. Ideal for USB flash drives and lab computers. |
| **Auto-Update Manifest** | [`latest.yml`](https://github.com/DigitalScience01/Docking-release/releases/download/v1.2.0/latest.yml) | 345 B | All | Cryptographic SHA512 manifest for background auto-updates. |
| **Blockmap File** | [`DockFlow-Setup-1.2.0.exe.blockmap`](https://github.com/DigitalScience01/Docking-release/releases/download/v1.2.0/DockFlow-Setup-1.2.0.exe.blockmap) | ~240 KB | `x64` | Fast differential delta update blockmap. |

---

## ✨ What's New in v1.2.0

* 🐍 **Zero-Configuration Embedded Python 3.11 Runtime**:
  * Bundled standalone CPython 3.11 runtime with complete pre-compiled native libraries (RDKit, Meeko, NumPy, SciPy, Gemmi) inside `resources/python`.
  * **100% Plug-and-Play**: Users no longer need to install Python, configure environment variables, or manage virtual environments.
* ⚡ **Bulletproof Direct CLI Execution**:
  * Re-architected Electron-to-Python execution engine to run CLI runner scripts directly via absolute paths with automatic `sys.path` bootstrapping.
  * Completely eliminates module lookup errors across all Windows distributions and user privilege levels.
* 🔒 **Bytenode V8 Native Bytecode Security**:
  * All Electron main process, preload APIs, docking bridge, and licensing algorithms compiled into native immutable V8 `.jsc` bytecode.
* 🤖 **AI Protocol Advisor (Google Gemini 2.5 Flash / Pro)**:
  * Natural language receptor target research, active pocket coordinate calculation, druggability index scoring, and methodology generation.
* 🧬 **Real-Time 2D/3D Interaction Profiler & 600 DPI Export**:
  * Dynamic LigPlot-style 2D interaction diagrams (H-bonds, hydrophobic contacts, electrostatic interactions) and 300/600 DPI publication rendering.
* 🔑 **Hardware-Bound Cloud Licensing**:
  * Real-time machine fingerprint authentication with Google Sheets cloud license server and offline grace cache.

---

## 💻 System Requirements

| Specification | Minimum Requirement | Recommended Specification |
| :--- | :--- | :--- |
| **Operating System** | Windows 10 (64-bit, Build 1809+) | Windows 11 (64-bit, Version 22H2 or newer) |
| **Python Installation** | **None Required** (Pre-bundled in app) | None Required (Self-contained) |
| **Processor (CPU)** | Intel Core i3 / AMD Ryzen 3 (Dual-core, 2.0 GHz) | Intel Core i7/i9 or AMD Ryzen 7/9 (8+ multi-threading cores for Vina) |
| **Memory (RAM)** | 4 GB RAM | 16 GB+ High-Speed RAM |
| **Graphics (GPU)** | Integrated Graphics with WebGL / OpenGL 2.0+ | Dedicated NVIDIA GTX / RTX or AMD Radeon GPU |
| **Storage** | 2 GB free disk space | 5 GB+ SSD storage (for multi-ligand batch screening cache) |
| **Display Resolution** | $1280 	imes 720$ | $1920 	imes 1080$ (Full HD) or $3840 	imes 2160$ (4K UHD) |

---

## 🚀 Installation & Setup Guide

### Option 1: Standard Installation Wizard (Recommended)
1. Download [`DockFlow-Setup-1.2.0.exe`](https://github.com/DigitalScience01/Docking-release/releases/download/v1.2.0/DockFlow-Setup-1.2.0.exe).
2. Double-click the installer executable.
3. Select your desired installation directory and click **Install**.
4. Launch **DockFlow** from your Desktop shortcut or Start Menu. Everything (including Python and docking tools) is ready out of the box!

### Option 2: Portable Standalone Executable
1. Download [`DockFlow.1.2.0.exe`](https://github.com/DigitalScience01/Docking-release/releases/download/v1.2.0/DockFlow.1.2.0.exe).
2. Move the file to any folder or USB flash drive.
3. Double-click to run immediately without administrative installation privileges.

---

## 🔐 License Activation & Support

Upon initial launch, DockFlow presents an Enterprise License Verification Gate:

* **Email-Based Cloud Activation**:
  * Enter your registered institutional or personal email address.
  * Click **🔓 Verify Email & Unlock DockFlow** to verify against the enterprise license database and unlock the complete application suite.
  * For offline field research, verified licenses are cached locally with an automatic grace period.

---

## 🔍 Cryptographic SHA-512 Verification

To verify the cryptographic integrity of your downloaded installer, execute PowerShell:

```powershell
Get-FileHash -Path ".\DockFlow-Setup-1.2.0.exe" -Algorithm SHA512
```

**Official Expected Hash (v1.2.0 - Base64):**
```text
uHl1xSABbmgFuFhvpzf1KmPeOiZD60NmwT4k7GCA7aEPmT98M/vFvOaKzxSJVFByLpQFzMwkqLnmhItvkYqSJg==
```

---

## 🔄 Automatic Updates

DockFlow includes a built-in background updater powered by `electron-updater`. Whenever a new release or security patch is published to this repository:
1. DockFlow automatically detects the new version on startup.
2. The download proceeds silently in the background.
3. An **"⚡ Install & Restart"** notification appears in the header and Settings tab.

---

## 📚 Scientific Engine Citations

* **AutoDock Vina v1.2.7**: *Eberhardt, J. et al. (2021). J. Chem. Inf. Model., 61(8), 3891–3898.*
* **RDKit**: *Landrum, G. et al. Open-Source Cheminformatics toolkit (rdkit.org).*
* **Meeko**: *Forli Lab, Scripps Research (github.com/forlilab/Meeko).*
* **3Dmol.js**: *Rego, N., & Koes, D. (2015). Bioinformatics, 31(8), 1322–1324.*

---

## 🔗 Related Links & Resources

* 💻 **Source Code Repository:** [https://github.com/DigitalScience01/Docking](https://github.com/DigitalScience01/Docking)
* 📦 **Release Archives:** [https://github.com/DigitalScience01/Docking-release/releases](https://github.com/DigitalScience01/Docking-release/releases)
* 🐛 **Issue Tracker & Feature Requests:** [https://github.com/DigitalScience01/Docking/issues](https://github.com/DigitalScience01/Docking/issues)

---

<div align="center">
  <sub>Developed with ❤️ by <b>Digital Science</b> • Enterprise Molecular Modeling & Cheminformatics Platform</sub>
</div>
