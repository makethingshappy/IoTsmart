# IoTsmart Series  
RP2040, RP2350A & ESP32-S3 MCU Modules for IoT & Node-RED Automation

**IoTsmart** is a family of compact, high-performance System-on-Module (SoM) boards designed for IoT, smart home, and small-scale industrial automation.  
The series includes three MCU platforms — **RP2040**, **RP2350A**, and **ESP32-S3** — each optimized for different connectivity, compute, and workflow automation needs.

IoTsmart modules integrate seamlessly with **IoTextra-Digital** hardware and support **IoTflow**, enabling **no-code programming for distributed MCU nodes** across MQTT and Node-RED ecosystems.

---

## 📦 Module Index

Each module includes versioned documentation (datasheet, schematic), media, and example code.

| Module | Architecture | Connectivity | Folder |
|--------|--------------|--------------|--------|
| **RP2040** | Dual-core Arm Cortex-M0+ | USB | [RP2040/v1.02](./RP2040/v1.02/) |
| **RP2350A** | Dual Cortex-M33 + Dual Hazard3 RISC-V | USB | [RP2350A/v1.02](./RP2350A/v1.02/) |
| **ESP32-S3** | Dual-core Xtensa LX7 | Wi-Fi + Bluetooth | [ESP32-S3/v1.02](./ESP32-S3/v1.02/) |
| **XIAO (Coming Soon)** | TBD | TBD | [XIAO/v1.02](./XIAO/v1.02/) |

---

## 🧠 Platform Differences & MCU Specifications

### **RP2040**
- Dual-core Arm Cortex-M0+ @ 133 MHz  
- Low-latency GPIO and deterministic timing  
- Ideal for local sensor/actuator control  
- Raspberry Pi PICO-compatible form factor  

### **RP2350A**
Next-generation microcontroller featuring a **dual-architecture design**:
- **Dual-core Arm Cortex-M33 processors**  
- **Dual-core Hazard3 RISC-V processors**  
Offers significantly higher performance, advanced event handling, and improved security.

### **ESP32-S3**
- Dual-core Xtensa LX7  
- Integrated **Wi-Fi + Bluetooth**  
- Hardware acceleration for AI/ML tasks  
- Ideal for wireless automation and cloud-connected workflows

### **IoTsmart XIAO (Coming Soon)**
A compact, minimal SoM for space-constrained, embedded, or wearable IoT applications.

---

## 🔧 Features & Capabilities

- Reliable MCU platforms for IoT and IIoT deployments  
- Clean integration with **IoTextra-Digital** modules  
- Stable performance across GPIO, PWM, UART, I²C, and SPI  
- Optional wireless connectivity (ESP32-S3)  
- Raspberry Pi PICO–compatible pinouts (RP2040 / RP2350A)  
- Suitable for **prototyping and small-batch production**  

---

## 🛠 Hardware Documentation

Each module folder contains:

- **/docs** – Datasheet and pinout diagrams  
- **/hardware** – Schematics (PDF)  
- **/media** – 3D renders, PCB images, host-pairing diagrams  
- **/examples** – MCU-specific reference examples  

Quick access:

- **RP2040** → [RP2040/v1.02](./RP2040/v1.02/)  
- **RP2350A** → [RP2350A/v1.02](./RP2350A/v1.02/)  
- **ESP32-S3** → [ESP32-S3/v1.02](./ESP32-S3/v1.02/)  
- **XIAO (Coming Soon)** → [XIAO/v1.02](./XIAO/v1.02/)  

---

## ⚙ Configuration & Setup Guide

All IoTsmart modules follow a unified setup workflow:

1. Select your module (RP2040, RP2350A, ESP32-S3).  
2. Review pinouts and electrical notes inside the module’s `/docs/` folder.  
3. Wire the board to IoTextra-Digital modules, sensors, or relays.  
4. Flash firmware using **USB**, **SWD**, **Arduino IDE**, or **MicroPython** (depending on MCU).  
5. Integrate your node into MQTT or Node-RED automations using **IoTflow** or your preferred workflow engine.

---

## 🧑‍💻 Software Support

IoTsmart modules are compatible with:

- **IoTflow** — enables no-code workflow automation for distributed MCU nodes  
- **MQTT** — event-driven messaging  
- **Node-RED** — workflow orchestration  
- **Arduino IDE** — easy firmware development  
- **MicroPython / CircuitPython** — lightweight scripting  
- **C/C++ SDKs** — for advanced embedded projects  

### Examples

Reference examples are available in:

👉 **[`/examples/`](./examples/)**  
Contains Python examples and general reference code for supported MCUs.

---

## 🛒 Ordering Information

Each module directory contains:

- SKU / part numbers  
- Ordering notes  
- Supported IoTextra modules  
- Mechanical details  

Browse module folders:

- `/RP2040/`  
- `/RP2350A/`  
- `/ESP32-S3/`  
- `/XIAO/` (Coming Soon)

📄 **SKU Sheet:**  
[`SKU IoTsmart.pdf`](./SKU%20IoTsmart.pdf)

---

## 📜 Licensing

Separate licenses apply depending on asset category:

- **Code** → [LICENSE_CODE.md](./LICENSE_CODE.md)  
- **Schematics & Hardware Docs** → [LICENSE_HARDWARE.md](./LICENSE_HARDWARE.md) (CC BY-SA 4.0)  
- **Documentation** → [LICENSE_DOCS.md](./LICENSE_DOCS.md)  
- **Media** → [LICENSE_MEDIA.md](./LICENSE_MEDIA.md)  
