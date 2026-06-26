<p align="center">
  <img src="img/Logo.png" width="1450" alt="VRAM Shield Logo">
</p>


<p align="center">
  <strong>Advanced thermal management and workload scheduling for high-performance GPUs.</strong>
</p>


<p align="center">
  <a href="https://vramshield.com/">Official Website</a> •
  <a href="https://vramshield.com/#pricing">Get PRO Version</a> •
  <a href="https://github.com/53-software/vram-shield/releases">Download Latest</a>
</p>


<p align="center">
  <img src="https://img.shields.io/badge/Status-Production--Ready-green" alt="Status">
  <img src="https://img.shields.io/badge/Platform-Windows%2010%20%7C%2011-blue" alt="Platform">
  <img src="https://img.shields.io/badge/License-Proprietary-red" alt="License">
</p>


---

**VRAM Shield** is a professional system utility designed to manage thermal loads and maintain compute stability during sustained high-load tasks.

## Why VRAM Shield?

Modern high-performance laptops face significant thermal density challenges. During AI generation (Stable Diffusion, LLMs), professional 3D rendering, or intensive gaming, VRAM often reaches its operational limits long before the GPU core. This leads to firmware-level throttling, inconsistent performance, and worst of all—**the irreversible degradation of expensive, irreplaceable video memory chips.** 

VRAM Shield solves this by intelligently scheduling GPU-heavy processes using **advanced mathematical logic** to ensure sustained, predictable performance.

## Key Features

*   **Native NVIDIA Integration:** Direct communication with the NVIDIA driver (NVML) for zero-latency, zero-overhead telemetry without third-party background monitors.
*   **True Hardware & Virtual VRAM Sensors (NEW):** VRAM Shield prioritizes reading real, physical temperature sensors on modern GPUs. For older graphics cards (RTX 30-series and below) where physical VRAM sensors do not exist, we specifically developed the **Virtual VRAM Sensor**. This proprietary mathematical model was calibrated through rigorous real-world stress testing in the 53 Software hardware laboratory to accurately estimate memory temperatures, ensuring 100% hardware compatibility and honest monitoring.
*   **Pulse Throttling (FREE):** A static scheduling engine to keep thermal loads within a target range.
*   **Smart Throttling (PRO):** A dynamic engine that uses advanced mathematical logic to micro-adjust load for maximum stability and fluid rendering.
*   **Panic Mode:** An emergency halt protocol that activates at critical thermal thresholds to maintain operational stability.
*   **Multilingual Interface:** Full support for 8 languages.

## Download & Installation

You can download the latest compiled version from the **[Releases](https://github.com/53-software/vram-shield/releases)** section.

1.  Download the latest `VRAMShield_X.X.X.exe`.
2.  Run the application as Administrator (required for process management).
3.  **On first launch, VRAM Shield will automatically download and install required Windows components (.NET Desktop Runtime & WebView2) if they are missing from your system.**
4.  Once active, the application will begin managing your VRAM thermal load natively.

> **Note:** This repository is used for distribution and issue tracking only. The source code is proprietary and not available for public access.

## Technical Architecture

VRAM Shield is a proprietary product of 53 Software. 

Starting with version 2.3.0, we have completely removed external third-party dependencies. VRAM Shield now utilizes direct, low-level integration with the **NVIDIA Management Library (NVML)**. This ensures enterprise-grade security, eliminates false positive antivirus detections, and provides instantaneous sensor readings.

*All scheduling algorithms, the Virtual VRAM Sensor logic, and UI components are independent developments of 53 Software.*

## Support & Links

*   **Official Website:** [vramshield.com](https://vramshield.com)
*   **Pricing & PRO Version:** [Select Your Edition](https://vramshield.com/#pricing)
*   **Documentation:** [Quick Start Guide](https://vramshield.com/quick-start)
*   **Email Support:** support@vramshield.com

## Legal Disclaimer

**VRAM Shield is provided "AS IS", without warranty of any kind.**

By downloading and using this software, you agree that:

1.  **Use at Your Own Risk:** The authors are not responsible for any hardware damage, data loss, or system instability.
2.  **Not a Safety Guarantee:** While designed to mitigate heat, this software cannot guarantee the prevention of hardware failure due to physical defects or extreme usage conditions.
3.  **License:** This software is proprietary. Unauthorized redistribution, reverse engineering, or cracking is prohibited.

Please read the full [End User License Agreement](https://vramshield.com/terms) and [Privacy Policy](https://vramshield.com/privacy.html) before use.

---

**VRAM Shield is managing your hardware thermals. Support the project by giving this repository a ⭐! It helps us a lot.** 

© 2026. 53 Software. All rights reserved.
