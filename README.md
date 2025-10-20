# LD6002 Vital Signs Radar PCB

[![Open Source Hardware](https://img.shields.io/badge/Open--Source-Hardware-green.svg)](https://www.oshwa.org/)
[![KiCad](https://img.shields.io/badge/Designed%20With-KiCad-blue.svg)](https://www.kicad.org/)
[![License: CERN-OHL-P v2](https://img.shields.io/badge/License-CERN--OHL--P--v2-yellow.svg)](LICENSE)
[![Made by Carenuty](https://img.shields.io/badge/Made%20by-Carenuity-blueviolet.svg)](#)


## 📘 Overview
The **LD6002 Vital Signs Radar PCB** is an open-source hardware design that uses the **Hi-Link LD6002 60 GHz radar sensor** for non-contact detection of **human presence, motion, respiration, and heart rate**.  
The board is designed in **KiCad** and integrates seamlessly with the **ESP32-C3 Mini** microcontroller for data acquisition and wireless communication.


## ⚙️ Features
- High-precision **60 GHz FMCW radar** sensing
- Detection of **breathing and heart rate** through low-power Doppler processing
- Compact **piggyback form factor** for embedded applications
- Designed for **ESP32-C3 Mini** integration
- Fully open-source design files under **CERN-OHL-P v2**



## 🔧 Technical Description
The design is based on the **Hi-Link LD6002** module, which provides motion and vital sign information using advanced radar algorithms.  
The PCB hosts the LD6002 sensor module and routing interface to the ESP32-C3 Mini through standard pin headers.

The system can be integrated into smart IoT devices such as:
- Smart home automation (presence sensing)
- Health monitoring stations
- Human–machine interaction systems
- Industrial safety monitoring



## 🧾 Bill of Materials (BOM)
A detailed list of all components is included in the **Bill of Materials** file:  
📄 [Bom File.xlsx](Bom%20File.xlsx)


## 🖼️ PCB Preview

Below are rendered views of the **LD6002 Vital Signs Radar Sensor PCB**:

| Top View | Bottom View |
|-----------|--------------|
| ![Top View](images/LD6002_Radar_Sensor_Top.png) | ![Bottom View](images/LD6002_Radar_Sensor_Bottom.png) 


## 🧠 Usage and Integration Notes
1. Power the module with **3.3 V DC** regulated supply.  
2. Connect serial data pins (TX/RX) to the **ESP32-C3 Mini UART** interface.  
3. Configure the MCU firmware to interpret radar serial output for presence and vital sign data.  
4. For optimal performance, ensure there are no metallic obstructions in the sensing path.  


## 🧩 Hardware Design
All design files were created using **KiCad**.  
To open the project:
1. Clone or download this repository.
2. Open `project.kicad_pro` in KiCad 7.0 or later.


## 📜 License
This project is licensed under the **CERN Open Hardware Licence v2 – Permissive (CERN-OHL-P v2)**.  
You are free to use, modify, and distribute this design, provided that proper attribution is maintained.  
See the [LICENSE](LICENSE) file for details.


## 👤 Author Information
**Author:** [Brian Omollo](https://www.linkedin.com/in/brian-omollo-25a71620b/)  
**Organization:** Carenuity  
**License:** CERN-OHL-P v2 (Permissive)  
**Design Tool:** KiCad  


## 📖 Citation

If you use this design in your work, please cite it as follows:

> Omollo, B. (2025). *LD6002 Vital Signs Radar PCB (v1.0)*. Carenuity Open Hardware Project. Licensed under CERN-OHL-P v2.

**BibTeX:**
```bibtex
@hardware{omollo2025ld6002,
  author    = {Brian Omollo},
  title     = {LD6002 Vital Signs Radar PCB (v1.0)},
  year      = {2025},
  publisher = {Carenuty Open Hardware Project},
  license   = {CERN-OHL-P v2},
  url       = {https://github.com/Carenuity/LD6002-Vital-Signs-Radar-PCB}
}
