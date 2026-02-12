# VRAM Shield v2.2.1 PRO

![Status](https://img.shields.io/badge/Status-Production--Ready-green)
![Platform](https://img.shields.io/badge/Platform-Windows%2010%20%7C%2011-blue)
![License](https://img.shields.io/badge/License-Proprietary-red)

**VRAM Shield** is a professional system utility designed to protect modern laptop video memory (VRAM) from critical overheating.

## 🛡️ Why VRAM Shield?

Modern high-performance laptops (NVIDIA RTX 30xx/40xx) often suffer from "Silent Overheating". While the GPU core remains cool, the VRAM chips can reach temperatures of **105-110°C** during AI generation (Stable Diffusion, LLMs), 3D rendering, or intensive gaming. This leads to hardware degradation and performance throttling.

VRAM Shield solves this by intelligently managing GPU-heavy processes using advanced software-based PWM and PID control.

## ✨ Key Features

*   **Real-time VRAM Monitoring:** Tracks memory temperature via LibreHardwareMonitor API.
*   **Normal Mode (FREE):** Pulse throttling logic to keep temperatures under control.
*   **Game Mode (PRO):** Advanced PID-controller with 5-stage progression for maximum FPS priority and smooth cooling.
*   **Panic Mode:** Emergency brake system that kicks in at critical temperatures (e.g., 100°C) to save your hardware.
*   **Multilingual UI:** Support for 8+ languages including English, Spanish, French, German, Chinese, Arabic, Russian, and Esperanto.

## 🚀 Download

You can download the latest compiled version from the **[Releases](https://github.com/53-software/vram-shield/releases)** section.

> **Note:** This repository is used for distribution and issue tracking only. The source code is proprietary.

## 🛠️ Installation

1.  Download `vram-shield.exe` from the latest release.
2.  Ensure **LibreHardwareMonitor** is running (required for sensor data).
3.  Run the application and follow the on-screen instructions.

## 📞 Support & Links

*   **Official Website:** [vramshield.com](https://vramshield.com)
*   **Report a Bug:** Use the [GitHub Issues](https://github.com/53-software/vram-shield/issues) tab.
*   **Email Support:** support@vramshield.com

---
© 2026. 53 Software. All rights reserved.
