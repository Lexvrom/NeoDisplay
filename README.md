# NeoDisplay

> A sleek, Matrix-inspired Rainmeter suite combining system monitoring with retro cyberpunk ASCII aesthetics.

---

## 📌 Overview

**NeoDisplay** is a complete Windows desktop customization suite built for [Rainmeter](https://www.rainmeter.net/). Originally created as a digital art project, it serves as a functional dashboard that delivers real-time internal PC diagnostics while maintaining a bold, matrix-style visual theme.

---

## 🖼️ Preview

<!-- Add your desktop screenshot here by replacing 'preview.png' with your image file name -->
![NeoDisplay Preview](preview.png)

---

## ✨ Features & Components

- **System & Hardware Monitoring:** Real-time tracking for CPU usage, RAM consumption (`Memory`), disk metrics (`Disk`), and core temperatures via Core Temp integration.
- **Clock & Calendar Options:** Multiple aesthetic variations for time and date displays (`Clock`, `Clock2`, `Date`, `Date2`).
- **Matrix Digital Rain:** Layered visual effect featuring up to 6 stacked binary rain streams (`Matrix` through `Matrix6`).
- **Folder Navigation:** Quick access links to system directories (`Pastes`).
- **Desktop Typography:** Custom title headers (`Desktop Title`) and the iconic "UMadBro?" ASCII character banner.

---

## 🛠️ Hardware & Environment Requirements

- **OS:** Windows 10 / 11
- **Native Resolution:** **1366x768** (Tested on a 19" monitor). *(Note: On higher or lower resolutions, widget positioning coordinates in `.ini` files may require manual adjustment).*
- **Engine:** [Rainmeter](https://www.rainmeter.net/) v4.5.23+
- **Hardware Temperature Tracking:** [Core Temp](https://www.alcpu.com/CoreTemp/) v1.19.5+
- **Required Fonts:** 
  - `Akira Expanded Demo` (`.otf`)
  - `Orbitron` (Black, Bold, Medium, Regular) (`.ttf`)

---

## 📂 Repository Structure

```text
NeoDisplay/
├── Necessary Files/         # Installers & dependencies
│   ├── Akira Expanded Demo.otf   # Required display font
│   ├── Orbitron-*.ttf            # Required suite typography family
│   ├── Core-Temp-setup-v1.19.5.69.exe # CPU temperature hardware monitor
│   └── Rainmeter-4.5.23.exe      # Rainmeter engine installer
├── Clock/                        # Primary time widget (clock.ini)
├── Clock2/                       # Alternate time layout (clock2.ini)
├── CPU/                          # Processor metrics skin (cpu.ini)
├── Date/                         # Primary calendar skin (Date.ini)
├── Date2/                        # Alternate calendar layout (Date2.ini)
├── Desktop Title/                # Main header label skin (Desktop.ini)
├── Disk/                         # Storage monitoring skin (disk.ini)
├── Matrix/ ... Matrix6/          # Layered binary digital rain animation modules (matrix.ini - Matrix6.ini)
├── Memory/                       # RAM consumption skin (Memory.ini)
├── Pastes/                       # Quick folder shortcuts skin (Pastes.ini)
├── UmadBro/                      # Custom ASCII art banner skin
├── LICENSE
└── README.md
```
--- 

🚀 Installation & Setup
1. Install Prerequisites & Dependencies
Navigate to the Necessary Files/ folder:

Install all font files (Akira Expanded Demo.otf and all Orbitron-*.ttf variants) by right-clicking them and selecting Install.

Run Core-Temp-setup-v1.19.5.69.exe to enable CPU temperature reading.

If you don't have Rainmeter running, execute Rainmeter-4.5.23.exe.

2. Load the Suite
Move the NeoDisplay folder into your Rainmeter skins directory (typically C:\Users\YourUsername\Documents\Rainmeter\Skins\).

Open Rainmeter, click Refresh all in the bottom left corner.

Expand the NeoDisplay directory and click Load on the desired .ini components.

📜 License
Distributed under the MIT License. See LICENSE for more information.

👤 Author
Developed by Lexvrom.
