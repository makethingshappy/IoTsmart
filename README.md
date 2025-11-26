# IoTsmart Series: RP2040, RP2350A & ESP32-S3 for MQTT & Node-RED Automation

## Overview

**IoTsmart** is a family of compact, high-performance System-on-Module (SoM) boards designed for IoT, smart home, and small-scale industrial automation.  
The series includes three core modules — **RP2040**, **RP2350A**, and **ESP32-S3** — each optimized for different compute, connectivity, and automation requirements.

IoTsmart modules integrate seamlessly with IoTextra-Digital hardware and support **IoTflow**, which enables **no-code programming for distributed MCU nodes** using MQTT and Node-RED.

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

### **IoTsmart XIAO (Coming Soon)**
A compact, minimal form factor ideal for embedded, wearable, or space-constrained IoT applications.  
Full documentation will be added in a future release.

---

## Features & Capabilities

- Reliable MCU platforms for IoT and IIoT deployments  
- Clean physical and logical integration with IoTextra-Digital modules  
- Stable performance across GPIO, PWM, UART, I²C, and SPI interfaces  
- Optional wireless connectivity (ESP32-S3)  
- Raspberry Pi PICO–compatible pinouts for RP2040/RP2350A  
- Suitable for **prototyping and small-batch production**  

---

## Hardware Specifications

Full hardware specifications — including pinouts, voltage ratings, PCB layouts, and electrical characteristics — are located inside the module folders:

- **[RP2040](./RP2040/)**  
- **[RP2350A](./RP2350A/)**  
- **[ESP32-S3](./ESP32-S3/)**  
- **[XIAO](./XIAO/)** (Coming Soon)

Each module directory includes its own documentation.  
Versioned subfolders (e.g., `v1.xx`) will be added by the development team in future updates.

---

## Configuration & Setup Guide

1. Select an IoTsmart module (RP2040, RP2350A, or ESP32-S3).  
2. Review the module’s pinout, electrical ratings, and wiring notes in its folder.  
3. Connect the board to IoTextra-Digital modules or external sensors/actuators.  
4. Flash your firmware via **USB**, **SWD**, **Arduino IDE**, or **MicroPython** (depending on MCU).  
5. Integrate the MCU into your MQTT or Node-RED automation using **IoTflow** or your own tooling.

---

## Software Support

IoTsmart modules support a variety of development environments:

- **IoTflow** — no-code workflow automation for distributed MCU nodes  
- **MQTT** — event-driven device messaging  
- **Node-RED** — workflow orchestration  
- **Arduino IDE** — rapid firmware prototyping  
- **MicroPython / CircuitPython** — lightweight scripting environments  
- **C/C++ SDKs** — for advanced embedded development  

---

## Examples

IoTsmart does **not** yet include its own `/examples` directory.  
Firmware examples and reference templates will be added in a future update by the development team.

For complete MQTT and Node-RED automation examples using IoTsmart + IoTextra-Digital, see:

👉 **IoTflow Node-RED Examples**  
https://github.com/makethingshappy/IoTflow/tree/main/Node-RED%20Examples

---

## Ordering Information

### 📦 SKU Information  
The full SKU list is available in the repository root:

- **[`SKU IoTsmart.pdf`](./SKU%20IoTsmart.pdf)**

---

### 🛒 Purchase Links  
Order IoTsmart modules directly from the official store:

- **IoTsmart RP2040:**  
  https://makethingshappy.io/collections/iotsmart/products/iotsmart-rp2040

- **IoTsmart RP2350A:**  
  https://makethingshappy.io/collections/iotsmart/products/iotsmart-rp2350

- **IoTsmart ESP32-S3:**  
  https://makethingshappy.io/collections/iotsmart/products/iotsmart-esp32-s3

---

## Licensing

This repository uses separate licenses per asset type:

- **Code:** [`LICENSE_CODE.md`](./LICENSE_CODE.md) — MIT License  
- **Schematics & Documentation:** [`LICENSE_HARDWARE.md`](./LICENSE_HARDWARE.md) — CC BY-SA 4.0  
- **Documentation:** [`LICENSE_DOCS.md`](./LICENSE_DOCS.md)  
- **Media:** [`LICENSE_MEDIA.md`](./LICENSE_MEDIA.md)
