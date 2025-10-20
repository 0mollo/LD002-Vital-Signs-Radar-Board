LD6002 Vital Signs Radar PCB

[![Open Source Hardware](https://img.shields.io/badge/Open--Source-Hardware-green.svg)](https://www.oshwa.org/)
[![KiCad](https://img.shields.io/badge/Designed%20With-KiCad-blue.svg)](https://www.kicad.org/)
[![License: CERN-OHL-P v2](https://img.shields.io/badge/License-CERN--OHL--P--v2-yellow.svg)](LICENSE)
[![Made by Carenuty](https://img.shields.io/badge/Made%20by-Carenuty-blueviolet.svg)](#)



📘 Overview
The LD6002 Vital Signs Radar PCB is an open-source hardware design that uses the Hi-Link LD6002 60 GHz radar sensor for non-contact detection of human presence, motion, respiration, and heart rate.  
The board is designed in KiCad and integrates seamlessly with the ESP32-C3 Mini microcontroller for data acquisition and wireless communication.


⚙️ Features
- High-precision 60 GHz FMCW radar sensing
- Detection of breathing and heart rate through low-power Doppler processing
- Compact piggyback form factor for embedded applications
- Designed for ESP32-C3 Mini integration
- Fully open-source design files under CERN-OHL-P v2


🧾 Bill of Materials (BOM)
📄 [Bom File.xlsx](Bom%20File.xlsx)


🧠 Usage
1. Power with 3.3 V DC regulated supply  
2. Connect TX/RX to ESP32-C3 Mini UART 
3. Read radar data via serial output  
4. Ensure unobstructed sensing path  


📜 License
Licensed under CERN Open Hardware Licence v2 – Permissive (CERN-OHL-P v2).  
See [LICENSE](LICENSE) for full details.



© 2025 Brian Omollo / Carenuity. All rights reserved.
