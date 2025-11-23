# IoTsmart Series: RP2040, RP2350A & ESP32-S3 for MQTT & Node-RED Automation

## Overview

IoTsmart is a family of compact, high-performance System-on-Module (SoM) boards for IoT, smart home, and small-scale industrial automation.  
The series includes three models — **RP2040**, **RP2350A**, and **ESP32-S3** — each optimized for different automation, connectivity, and compute requirements.

IoTsmart modules integrate seamlessly with IoTextra-Digital hardware and support **IoTflow**, which enables **no-code programming for distributed MCU nodes** using MQTT and Node-RED.

---

## Platform Differences & MCU Specifications

### **RP2040**
- Dual-core Arm Cortex-M0+ (133 MHz)  
- Predictable timing and low-latency digital I/O  
- Ideal for GPIO-driven sensors, actuators, and local event logic  
- Raspberry Pi PICO–compatible form factor  

### **RP2350A**
A next-generation microcontroller **packing a dual-core and dual-architecture design**:
- **Dual-core Arm Cortex-M33 processors**  
- **Dual-core Hazard 3 RISC-V processors**  
Offers significantly higher performance, improved security, and advanced event-handling capabilities for demanding automation tasks.

### **ESP32-S3**
- Dual-core Xtensa LX7  
- Integrated **Wi-Fi + Bluetooth**  
- Hardware acceleration for AI/ML tasks  
- Ideal for wireless automation, API-based workflows, and cloud-driven systems  

### **IoTsmart XIAO (Coming Soon)**
A compact, minimal form-factor variant for embedded, wearable, or space-constrained IoT applications.  
(Currently a placeholder — full module documentation will be added in a future release.)

---

## Features & Capabilities

- Reliable MCU platforms for IoT and IIoT deployments  
- Clean physical and logical integration with IoTextra-Digital modules  
- Stable performance for GPIO, PWM, UART, I²C, and SPI peripherals  
- Optional wireless connectivity (ESP32-S3)  
- Raspberry Pi PICO–compatible pinouts for RP2040/RP2350A  
- Suitable for **prototyping and small-batch production**  

---

## Hardware Specifications

Full specifications — including pinouts, voltage ratings, PCB layouts, and electrical characteristics — are provided in the individual module folders:

- `RP2040/v1.02/`
- `RP2350A/v1.02/`
- `ESP32-S3/v1.02/`
- `XIAO/v1.02/` (Coming Soon)

Refer to the documentation inside each directory for complete technical details.

---

## Configuration & Setup Guide

All IoTsmart modules follow a unified setup workflow:

1. Choose an IoTsmart module (RP2040, RP2350A, ESP32-S3).  
2. Review the pinout and electrical documentation inside the module folder.  
3. Wire the board to IoTextra-Digital modules, external sensors, or relays.  
4. Flash your firmware using **USB**, **SWD**, **Arduino IDE**, or **MicroPython** (model-dependent).  
5. Integrate the node into MQTT or Node-RED automation using **IoTflow** or your own host environment.

---

## Software Support

IoTsmart modules are compatible with:

- **IoTflow** — enables no-code workflow automation for distributed MCU nodes  
- **MQTT** — for event-driven messaging  
- **Node-RED** — workflow orchestration  
- **Arduino IDE** — for rapid firmware development  
- **MicroPython / CircuitPython** — for lightweight scripting  
- **C/C++** SDKs for advanced embedded development  

### Examples

Reference examples are available inside:

👉 **`/examples/` — contains Python examples and reference code for supported MCUs**

---

## Ordering Information

For SKUs, ordering codes, and module-specific notes, please see the individual module directories:

- `RP2040/`  
- `RP2350A/`  
- `ESP32-S3/`  
- `XIAO/` (Coming Soon)

Each folder contains its own specifications and ordering information.

---

## Licensing

This repository uses separate licenses for different asset categories:

- **Code:** [`LICENSE_CODE.md`](./LICENSE_CODE.md) — MIT License  
- **Schematics & Documentation:** [`LICENSE_HARDWARE.md`](./LICENSE_HARDWARE.md) — CC BY-SA 4.0  
- **Documentation:** [`LICENSE_DOCS.md`](./LICENSE_DOCS.md)  
- **Media:** [`LICENSE_MEDIA.md`](./LICENSE_MEDIA.md)
