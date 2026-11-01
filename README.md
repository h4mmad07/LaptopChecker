<div align="center">

# 💻 LaptopCheck

### Laptop hardware diagnostics, health scoring & used-laptop inspection for Windows

[![Platform](https://img.shields.io/badge/Platform-Windows%2010%20%7C%2011%20(x64)-0078D6?logo=windows&logoColor=white)](#)
[![Python](https://img.shields.io/badge/Python-3.9%2B-3776AB?logo=python&logoColor=white)](#)
[![UI](https://img.shields.io/badge/UI-PyQt6-41CD52?logo=qt&logoColor=white)](#)
[![Reports](https://img.shields.io/badge/Reports-PDF%20%7C%20HTML%20%7C%20JSON%20%7C%20CSV-orange)](#)
[![Status](https://img.shields.io/badge/Status-v1.0.0%20pilot-yellow)](#)
[![License](https://img.shields.io/badge/License-Proprietary-lightgrey)](LICENSE)

**Scan it. Test it. Grade it. Prove it.**
Everything a technician or a careful buyer needs to check a laptop before money changes hands.

</div>

---

## ✨ Why LaptopCheck?

Buying or servicing a used laptop means trusting a seller's word. LaptopCheck replaces that trust with evidence: it reads hardware details straight from Windows, runs real diagnostic tests, compares the result against what the seller *claimed*, and produces a report you can keep or hand to a customer.

Values come directly from Windows interfaces (WMI/CIM, Win32 API, DXGI, NVIDIA NVML, ACPI thermal zones). Anything the system doesn't expose is labelled **Unavailable** instead of being guessed.

---

## 🚀 Features

| | |
|---|---|
| 🔍 **Full hardware scan** | CPU, GPU, RAM (per-DIMM), storage with SMART/NVMe data, battery wear & cycles, display/EDID, audio, network, USB/peripherals, driver errors, BIOS/UEFI, TPM, Secure Boot |
| 🩺 **Health scoring** | Per-component status plus a transparent 0–100 score with itemised deductions |
| 🕵️ **Buyer Mode** | *Advertised vs Detected* comparison (CPU, GPU, RAM, storage, screen) with clear `MATCH` / `MISMATCH` / `CANNOT VERIFY` verdicts, and a 17-point physical inspection checklist |
| 🧪 **Diagnostic tests** | One-click 11-point quick test, visual keyboard tester, fullscreen dead-pixel/backlight test, non-destructive RAM pattern test, stereo audio test, webcam check, network test |
| 🔥 **Benchmarks & thermals** | Multi-core CPU benchmark, GPU 3D benchmark, combined stress test with automatic thermal safety cutoff, live temperature/clock/power charts, throttling analysis |
| 📄 **Reports & certificates** | Export to **PDF, HTML, JSON, CSV**; single-page inspection certificate; optional serial/MAC masking |
| 🗂️ **History** | Local SQLite database of scans, tests, benchmarks and reports |
| 🖥️ **GUI + CLI** | Dark-mode PyQt6 desktop app, plus a headless CLI for bench technicians |
| 🎒 **Portable** | Single-file portable build that runs from a USB stick |
| 🔑 **Licensing** | 7-day full-feature trial, then offline RSA-signed Pro license bound to the device |

---

## 🔒 Privacy

- No accounts, no telemetry, no cloud upload of scan data
- Scans, history and reports are stored locally
- Serial numbers and MAC addresses are masked in reports by default
- Diagnostics are read-only: LaptopCheck never flashes firmware or changes BIOS/registry settings

---

## 👤 Author

**Muhammad Hammad** · [@h4mmad07](https://github.com/h4mmad07)

<div align="center">

*Built to make buying and repairing laptops a little more honest.*

</div>
