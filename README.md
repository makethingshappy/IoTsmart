# IoTsmart Series: RP2040, RP2350A, ESP32-S3 & XIAO for MQTT & Node-RED Automation

## Overview

**IoTsmart** is a family of compact, high-performance System-on-Module (SoM) boards designed for IoT, smart home, and small-scale industrial automation.  
The series includes four core modules — [**RP2040**](https://makethingshappy.io/products/iotsmart-rp2040), [**RP2350A**](https://makethingshappy.io/products/iotsmart-rp2350), [**ESP32-S3**](https://makethingshappy.io/products/iotsmart-esp32-s3) and [**XIAO**](https://makethingshappy.io/products/iotsmart-xiao) — each optimized for different compute, connectivity, and automation requirements.

IoTsmart modules integrate seamlessly with [**IoTextra-Digital**](https://makethingshappy.io/collections/digital-iotextra) hardware and support [**IoTflow**](https://makethingshappy.io/pages/iotflow), which enables **no-code programming for distributed MCU nodes** using MQTT and Node-RED.

---

## Platform Differences & MCU Specifications

### **RP2040**
- Dual-core Arm Cortex-M0+ (133 MHz)  
- Predictable timing and low-latency digital I/O  
- Ideal for GPIO-driven sensors, actuators, and event logic  
- Raspberry Pi PICO–compatible form factor  

### **RP2350A**
A next-generation microcontroller **packing a dual-core, dual-architecture design**:
- **Dual-core Arm Cortex-M33 processors**  
- **Dual-core Hazard 3 RISC-V processors**  

This platform offers significantly improved performance, enhanced security, and advanced event-processing capacity for demanding automation tasks.

### **ESP32-S3**
- Dual-core Xtensa LX7  
- Integrated **Wi-Fi + Bluetooth**  
- Hardware acceleration for AI/ML tasks  
- Ideal for wireless automation, cloud workflows, and API-driven systems  

### **IoTsmart XIAO**
Carrier for Seeed Studio XIAO and Adafruit QT Py modules — one carrier for many MCUs (ESP32-S3, ESP32-C6, ESP32-C3, RP2040, RP2350, nRF52840, SAMD21, MG24 and others).  
- **v.1.02** — 40 × 31 mm, H-HOST or V-HOST connector, one Qwiic connector  
- **v.2.01** — 47 × 30 mm, V-HOST connector, two Qwiic connectors  
- Optional UART connector, onboard EEPROM

---

## Features & Capabilities

- Reliable MCU platforms for IoT and IIoT deployments  
- Clean physical and logical integration with IoTextra-Digital modules  
- Stable performance across GPIO, PWM, UART, I²C, and SPI interfaces  
- Optional wireless connectivity (ESP32-S3; XIAO with ESP32-based modules)  
- Suitable for **prototyping and small-batch production**  

---

## Hardware Specifications

Full hardware specifications — including pinouts, voltage ratings, PCB layouts, and electrical characteristics — are located inside the module folders:

- **[RP2040](./RP2040/)**  
- **[RP2350A](./RP2350A/)**  
- **[ESP32-S3](./ESP32-S3/)**  
- **[XIAO](./XIAO/)**

Each module directory includes its own documentation.  
Each hardware revision has its own subfolder (e.g., `v.2.01`) with the datasheet, schematic, `host-map.yaml` and media for that revision.

---

## Configuration & Setup Guide

1. Select an IoTsmart module (RP2040, RP2350A, ESP32-S3, or XIAO).  
2. Review the module’s pinout, electrical ratings, and wiring notes in its folder.  
3. Connect the board to IoTextra-Digital modules or external sensors/actuators.  
4. Flash your firmware via **USB**, **SWD**, **Arduino IDE**, or **MicroPython** (depending on MCU).  
5. Integrate the MCU into your MQTT or Node-RED automation using **IoTflow** or your own tooling.

---

## Software Support

IoTsmart modules support a variety of development environments:

- **IoTflow** — no-code workflow automation for distributed MCU nodes  
- **MTH for Tasmota** (formerly IoThome) — Tasmota templates and Berry drivers, ESP32-based IoTsmart boards ([IoThome](https://github.com/makethingshappy/IoThome))  
- **MTH for ESPHome** — ready-to-flash ESPHome configurations, ESP32-based IoTsmart boards ([MTH-for-ESPHome](https://github.com/makethingshappy/MTH-for-ESPHome))  
- **MQTT** — event-driven device messaging  
- **Node-RED** — workflow orchestration  
- **Arduino IDE** — rapid firmware prototyping  
- **MicroPython / CircuitPython** — lightweight scripting environments  
- **C/C++ SDKs** — for advanced embedded development  

Which IoTsmart boards and IoTextra modules are supported by which software is shown in the [compatibility tables](https://github.com/makethingshappy#readme).

---

## Examples

IoTsmart has no `/examples` directory of its own. Ready-to-use configurations live in the companion repositories:

- Tasmota templates and Berry drivers — [IoThome / Tasmota_Templates](https://github.com/makethingshappy/IoThome/tree/main/Tasmota_Templates)
- ESPHome configurations — [MTH-for-ESPHome / Configs](https://github.com/makethingshappy/MTH-for-ESPHome/tree/main/Configs)

For complete MQTT and Node-RED automation examples using IoTsmart + IoTextra-Digital, see:

👉 **IoTflow Node-RED Examples**  
https://github.com/makethingshappy/IoTflow/tree/main/Node-RED%20Examples

---

## Ordering Information

### 📦 SKU Information  
The SKU list for each module is available inside its own folder:

- [RP2040/SKU.md](RP2040/SKU.md)
- [RP2350A/SKU.md](RP2350A/SKU.md)
- [ESP32-S3/SKU.md](ESP32-S3/SKU.md)
- [XIAO/SKU.md](XIAO/SKU.md)

---

### 🛒 Purchase Links  
Order IoTsmart modules directly from the official store:

- **IoTsmart RP2040:**  
  https://makethingshappy.io/collections/iotsmart/products/iotsmart-rp2040

- **IoTsmart RP2350A:**  
  https://makethingshappy.io/collections/iotsmart/products/iotsmart-rp2350

- **IoTsmart ESP32-S3:**  
  https://makethingshappy.io/collections/iotsmart/products/iotsmart-esp32-s3

- **IoTsmart XIAO:**  
  https://makethingshappy.io/collections/iotsmart/products/iotsmart-xiao

---

## Licensing

This repository uses separate licenses per asset type:

- **Code:** [`LICENSE_CODE.md`](./LICENSE_CODE.md) — MIT License  
- **Schematics & Documentation:** [`LICENSE_HARDWARE.md`](./LICENSE_HARDWARE.md) — CC BY-SA 4.0  
- **Documentation:** [`LICENSE_DOCS.md`](./LICENSE_DOCS.md)  
- **Media:** [`LICENSE_MEDIA.md`](./LICENSE_MEDIA.md)
