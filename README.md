LD6002 Vital Signs Radar Sensor Board

[Board Render](images/LD6002 Radar Sensor piggyback top view.png)

Overview
This repository contains the design files for the LD6002 Vital Signs Radar Sensor Board, an open-source hardware module developed in KiCad.  
It integrates the Hi-Link LD6002 60GHz radar sensor, enabling human presence, motion, and vital sign detection such as breathing and heart rate monitoring.

This board is designed for seamless interfacing with ESP8266/ESP32 development boards, allowing rapid prototyping in health monitoring, smart home, and occupancy detection systems.


Features
Utilizes Hi-Link LD6002 (60GHz) radar sensor
Detects presence, motion, breathing, and heartbeat
Compatible with 3.3V logic microcontrollers
Dedicated UART, I2C, and analog I/O headers
Compact footprint suitable for embedded applications
Onboard decoupling capacitors and resistor network for signal stability



Technical Specifications
Parameter
Operating Voltage = 3.3V 
Sensor = Hi-Link LD6002
Communication Interfaces  UART 
Detection Range  ~1.5m (vital signs), ~6m (presence)
PCB Design Tool = KiCad 
Board Type  2-layer, Through-Hole and SMD mixed 


Pinout Summary
| Pin | Function | Description |
|------|-----------|-------------|
| 3V3 | Power Supply | Input voltage |
| GND | Ground | Common ground reference |
| TX / RX | UART | Serial data communication |
| D0–D8 | GPIO | General purpose pins |
| A0 / AI01 | Analog Input | Sensor analog data |
| SCL0 / TX0 / RX0 | I2C / UART | Secondary interface |


Bill of Materials (BOM)
The complete Bill of Materials is provided in the file:  
[`Bom File.xlsx`](../Bom%20File.xlsx)


📂 Repository Structure

LD6002_Vital_Signs_Radar/
 ┣ 📁 hardware
 ┃ ┣ 📄 schematic.pdf
 ┃ ┣ 📄 LD6002_Radar_Sensor.kicad_pcb
 ┃ ┣ 📄 gerbers.zip
 ┃ ┗ 📄 Bom File.xlsx
 ┣ 📁 images/
 ┃ ┗ 📄 LD6002_Radar_Sensor_piggyback_top_view.png
 ┣ 📄 README.md
 ┣ 📄 LICENSE
 ┗ 📄 .gitignore




 Getting Started
1. Connect the board to a 3.3V-compatible microcontroller (ESP8266, ESP32, or Arduino 3.3V).
2. Power the module via the 3.3V.
3. Use UART to read radar data, or I²C for configuration and status monitoring.
4. Integrate the output into applications such as:
   - Human presence detection
   - Sleep monitoring
   - Contactless heart and breathing rate detection



Example Applications
1. Smart healthcare and patient monitoring
2. Human presence-based lighting or HVAC automation
3. Touchless control interfaces
4. Security and occupancy sensing systems


License
This project is released under the CERN Open Hardware License v2 (CERN OHL v2).  
You are free to use, modify, and distribute this design under the same license terms.

See the [LICENSE](LICENSE) file for full details.

Author
Brian Omollo 
Designed using KiCad  
For inquiries or collaboration: omollobrian234@gmail.com


Acknowledgment
Special thanks to Hi-Link for the LD6002 radar module design reference and open documentation that made this project possible.

#Tagline
> “Vital Signs by 60GHz — Contactless, Smart, and Open.
