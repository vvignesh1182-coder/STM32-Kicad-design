# STM32 2-Layer PCB Design

A custom 2-layer Printed Circuit Board (PCB) designed around the STM32 microcontroller. This repository contains the complete open-source hardware files, schematics, PCB layouts, and manufacturing outputs created using **KiCad**.

---

## 📌 Project Overview
This project focuses on robust hardware layout practices for embedded microcontrollers, featuring optimized power distribution, ground copper pour zones, and signal integrity routing tailored for a standard 2-layer manufacturing stackup.

---

## 🚀 Key Features
* **Microcontroller Core:** Built around the STM32 MCU family for high-performance embedded control.
* **Power & Filtering:** Stable regulated power distribution featuring $+3.3\text{V}$ traces and ferrite bead isolation (`FB1`) to minimize noise between digital and analog domains.
* **Copper Ground Pour:** Utilizes dedicated GND copper fill zones and ground stitching vias to ensure low-impedance return paths and mitigate EMI.
* **Design Verification:** Fully verified and DRC-clean (Design Rules Checker) with confirmed schematic-to-layout parity.

---

## 📂 Repository Structure
```text
├── Schematic/       # KiCad schematic files (.kicad_sch) and symbol libraries
├── PCB/             # Board layout files (.kicad_pcb) and stackup settings
├── Manufacturing/   # Gerber files, drill files, and Bill of Materials (BOM) for fabrication
└── README.md        # Project documentation

🛠️ Tools & Requirements
Design Software: KiCad (v8.0 or compatible version recommended)

⚙️ Getting Started
Clone the repository:

Bash
git clone [https://github.com/vvignesh1182-coder/STM32-Kicad-design.git](https://github.com/vvignesh1182-coder/STM32-Kicad-design.git)
Open KiCad, select File > Open Project, and choose the .kicad_pro file from the repository directory.

Explore the Schematic Editor or PCB Editor to inspect the routing, stackup, and component placement.

📦 Manufacturing Outputs
The Manufacturing/ folder contains all necessary files ready to be zipped and uploaded directly to standard PCB fabrication houses (such as JLCPCB or PCBWay):

Gerber files (Copper layers, silkscreen, mask, edge cuts)

Excellon Drill files

Bill of Materials (BOM) CSV file
