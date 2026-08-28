<div align="center">

<img src="https://raw.githubusercontent.com/DigitalScience01/Docking/main/assets/logo.png" alt="DockFlow Logo" width="160" height="160" style="border-radius: 20%; filter: drop-shadow(0px 8px 24px rgba(0, 240, 255, 0.45));" />

# DockFlow
### Molecular Docking, AI Protocol Advisory, 2D/3D Interaction Mapping & ADMET Screening Platform

[![Current Release](https://img.shields.io/badge/Release-v1.1.7-00f0ff.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/DigitalScience01/Docking-release/releases)
[![Platform](https://img.shields.io/badge/Platform-Windows%20x64-0078D6.svg?style=for-the-badge&logo=windows&logoColor=white)](https://github.com/DigitalScience01/Docking-release/releases)
[![Status](https://img.shields.io/badge/Status-Stable%20Production-10b981.svg?style=for-the-badge)](https://github.com/DigitalScience01/Docking-release/releases)
[![Engine](https://img.shields.io/badge/AutoDock%20Vina-v1.2.7-E25A1C.svg?style=for-the-badge)](https://vina.scripps.edu/)
[![AI Advisor](https://img.shields.io/badge/Google%20Gemini%20AI-2.5%20Flash%20%2F%20Pro-8E24AA.svg?style=for-the-badge&logo=google&logoColor=white)](https://ai.google.dev/)
[![Bytenode Protected](https://img.shields.io/badge/Security-Bytenode%20V8%20Bytecode-47848F.svg?style=for-the-badge)](https://github.com/DigitalScience01/Docking)

<p align="center">
  Official production release hub for <b>DockFlow Desktop Suite</b>. Download the latest Windows setup installers, standalone portable packages, and differential auto-update manifests.
</p>

[📥 Download Latest Release (v1.1.7)](#-latest-release-v117-downloads) • [✨ Highlights](#-whats-new-in-v117) • [💻 System Requirements](#-system-requirements) • [🚀 Installation Guide](#-installation--setup-guide) • [🔐 License Activation](#-license-activation--support) • [📂 Source Code](https://github.com/DigitalScience01/Docking)

</div>

---

## 📦 Latest Release: v1.1.7 Downloads

| Package Type | File Name | Size | Architecture | Description |
| :--- | :--- | :--- | :--- | :--- |
| **Windows Installer (NSIS)** | [`DockFlow Setup 1.1.7.exe`](https://github.com/DigitalScience01/Docking-release/releases/download/v1.1.7/DockFlow.Setup.1.1.7.exe) | ~178 MB | `x64` (64-bit) | Recommended for desktop PCs and laptops. Includes automatic desktop shortcuts and auto-updater integration. |
| **Windows Portable** | [`DockFlow 1.1.7.exe`](https://github.com/DigitalScience01/Docking-release/releases/download/v1.1.7/DockFlow.1.1.7.exe) | ~178 MB | `x64` (64-bit) | Zero-installation standalone executable. Ideal for USB flash drives, restricted enterprise environments, and lab computers. |
| **Auto-Update Manifest** | [`latest.yml`](https://github.com/DigitalScience01/Docking-release/releases/download/v1.1.7/latest.yml) | 345 B | All | Cryptographic SHA512 manifest for background auto-updates. |
| **Blockmap File** | [`DockFlow Setup 1.1.7.exe.blockmap`](https://github.com/DigitalScience01/Docking-release/releases/download/v1.1.7/DockFlow.Setup.1.1.7.exe.blockmap) | ~180 KB | `x64` | Fast differential delta update blockmap. |

---

## ✨ What's New in v1.1.7

* 🎨 **Full Light & Dark Adaptive Theming in AI Protocol Advisor**:
  * Complete support for Clean Scientific Light Theme across all advisor cards, search drawers, residue badges, druggability meters, and active pocket coordinate pills.
  * Real-time dynamic background synchronization for embedded 3D Mini Ribbon Viewers upon theme change.
* 🧬 **Interactive 2D Protein-Ligand Complex Selector**:
  * Added dynamic `Target Complex:` dropdown and `⚡ View 2D Map` action button on the 2D Interaction Diagram toolbar.
  * Seamlessly toggle and compute hydrogen bonds ($\le 3.5\,\text{\AA}$), hydrophobic contacts ($\le 4.0\,\text{\AA}$), and residue interactions for any docked hit compound and pose.
* 📊 **Interface Standardization & Layout Modernization**:
  * Standardized header typography, weights, and colors across all 3 columns in Ligand Studio (*Ligand Input*, *Prepared Ligands Library*, *Selected Ligand Structure*).
  * Removed numbering clutter from Results subtabs, Receptor Preparation, and Protein Grid Box for a sleek, publication-focused design.
* 🖥️ **High-Contrast Multi-Engine Terminal Console**:
  * Enhanced terminal box styling with crisp cyan illumination in Dark Mode and deep high-contrast terminal styling in Light Mode.
* 🔐 **Resilient Enterprise License Engine**:
  * Fast-track offline activation with master enterprise fallback keys (`DOCKFLOW-PRO-2026`).
  * Automated recovery helper links in the license validation gate to ensure zero workflow disruption during field research.

---

## 💻 System Requirements

| Specification | Minimum Requirement | Recommended Specification |
| :--- | :--- | :--- |
| **Operating System** | Windows 10 (64-bit, Build 1809+) | Windows 11 (64-bit, Version 22H2 or newer) |
| **Processor (CPU)** | Intel Core i3 / AMD Ryzen 3 (Dual-core, 2.0 GHz) | Intel Core i7/i9 or AMD Ryzen 7/9 (8+ multi-threading cores for Vina) |
| **Memory (RAM)** | 4 GB RAM | 16 GB+ High-Speed RAM |
| **Graphics (GPU)** | Integrated Graphics with WebGL / OpenGL 2.0+ | Dedicated NVIDIA GTX / RTX or AMD Radeon GPU |
| **Storage** | 1.5 GB free disk space | 5 GB+ SSD storage (for multi-ligand batch screening cache) |
| **Display Resolution** | $1280 \times 720$ | $1920 \times 1080$ (Full HD) or $3840 \times 2160$ (4K UHD) |

---

## 🚀 Installation & Setup Guide

### Option 1: Standard Installation Wizard (Recommended)
1. Download [`DockFlow Setup 1.1.7.exe`](https://github.com/DigitalScience01/Docking-release/releases).
2. Double-click the installer executable.
3. Select your desired installation directory and click **Install**.
4. Launch **DockFlow** from your Desktop shortcut or Start Menu.

### Option 2: Portable Standalone Executable
1. Download [`DockFlow 1.1.7.exe`](https://github.com/DigitalScience01/Docking-release/releases).
2. Move the file to any folder or USB storage drive.
3. Double-click to run immediately without administrative installation privileges.

---

## 🔐 License Activation & Support

Upon initial launch, DockFlow presents an Enterprise License Verification Gate:

1. **Email-Based Cloud Activation**:
   * Enter your institutional or registered email address.
   * Click **🔓 Validate Email & Unlock DockFlow**.
2. **Instant Master Pro Key Activation**:
   * If working offline or before your email is registered in cloud records, click **`⚡ Auto-fill Pro Key`** (or enter `DOCKFLOW-PRO-2026`).
   * Click **🔓 Validate Email & Unlock DockFlow** to immediately unlock the complete application suite.

---

## 🔍 Cryptographic SHA-512 Verification

To verify the cryptographic integrity of your downloaded installer, execute PowerShell:

```powershell
Get-FileHash -Path ".\DockFlow Setup 1.1.7.exe" -Algorithm SHA512
```

**Official Expected Hash (v1.1.7):**
```text
zVkJVMbJpDb5bkhZxox16NHhFh8HxzldndCvhczcecE30l5FzS3bwO6mllpw64sqRCV79QuDIjGR1f+iRwKPvg==
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

