**BTTM - codename: Flavona**
![Uploading 53865DAA-6330-4362-A534-B9F261CD4213.JPG…]()

**BTTM: Brake & Tire Temperature Monitor**
A motorsport telemetry system for real-time thermal monitoring of racing vehicle performance. BTTM integrates distributed infrared and RTD temperature sensors across tire and brake systems, reporting via CAN bus to a central ESP32-S3 hub with WiFi telemetry, local web interface, and on-board data logging.
Features

Multi-node CAN architecture with dedicated brake and tire sensor nodes
Infrared temperature detection
Central monitoring unit with ESP32-S3 microcontroller
Real-time web telemetry dashboard over WiFi
Local TFT display for trackside feedback
High-frequency data logging and cloud backup integration
Mesh networking support for extended track coverage

**Hardware**

- ESP32-S3 main hub (ver 1.2)
- ESP32-C3 CAN node IR Sensors (ver 1.1)

All PCB designs are custom.

![IMG_2069](https://github.com/user-attachments/assets/417639a7-7b54-42eb-ab91-400a5d157be1)

**Applications**

Designed for circuit racing, track days, and motorsport testing to provide real-time thermal diagnostics for race strategy, vehicle setup optimization and R&D.


**License**

Code (STM32 projects): GPL3.0.

Code (ESP32 projects): MIT license.

Hardware: cc-by-sa-3.0

By: Pietro Gambarin (pietro.gambarin@gmail.com)
