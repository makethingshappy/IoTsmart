# IoTsmart Series: RP2040, RP2350A & ESP32-S3 for MQTT & Node-RED Automation

## Overview

IoTsmart is a family of compact, high-performance System-on-Module (SoM) boards designed for IoT, smart home, and light industrial automation projects.  
The series includes three models — **RP2040**, **RP2350A**, and **ESP32-S3** — each offering unique strengths in GPIO, connectivity, and compute capability.

All IoTsmart modules integrate seamlessly with the IoTextra-Digital hardware series and can be combined with MQTT and Node-RED workflow tools via external libraries such as **IoTflow**.

## Platform Differences & MCU Specifications

The IoTsmart series includes three MCU platforms. Their differences are summarized below:

### **RP2040**
- Dual-core Arm Cortex-M0+ (133 MHz)
- Predictable timing and low-latency I/O
- Ideal for pure GPIO-driven digital logic and sensor input/output

### **RP2350A**
- Upgraded RP2-series MCU  
- Higher clock speed and expanded capabilities  
- Designed for more demanding workflows requiring faster event handling and larger program memory

### **ESP32-S3**
- Dual-core Xtensa processor with Wi-Fi + Bluetooth  
- Built-in hardware acceleration for ML/AI tasks  
- Ideal for wireless automation, API-connected workflows, and cloud-first deployments

(Refer to the documentation inside each module folder for specific electrical and mechanical details.)

## Features & Capabilities

- High-reliability microcontroller platforms for IoT and IIoT environments  
- Clean integration with IoTextra-Digital I/O modules  
- Stable performance for GPIO, PWM, serial buses, and sensor integration  
- Optional Wi-Fi/Bluetooth (ESP32-S3 model)  
- Works with Raspberry Pi, Node-RED, Arduino, and other automation ecosystems  
- Designed for cabinet use, prototyping, and low-power embedded deployments  

## Hardware Specifications (Per Model)

See the individual versioned folders for each MCU:

- `RP2040/v1.02/`  
- `RP2350A/v1.02/`  
- `ESP32-S3/v1.02/`  
- `XIAO/v1.02/` (additional compact variant)

Inside each you'll find:

- Pinout diagrams  
- Electrical characteristics  
- Supported voltage ranges  
- PCB layout information (where applicable)

## Configuration & Setup Guide

Each IoTsmart module follows the same high-level setup process:

1. Select the desired IoTsmart board (RP2040, RP2350A, ESP32-S3).  
2. Review the pinout and electrical characteristics from the module folder.  
3. Wire the board to IoTextra-Digital modules or external sensors.  
4. Flash your firmware using USB or SWD (depending on model).  
5. Integrate with Node-RED or MQTT workflow engines via a host system (e.g., Raspberry Pi).

## Software Support

While IoTsmart is a hardware series, it is fully compatible with common workflow and automation tools:

- **MQTT** (via host software such as IoTflow)  
- **Node-RED** (via GPIO plugins or IoTflow templates)  
- **Arduino / CircuitPython / MicroPython** (depending on MCU)  

For workflow examples and integration patterns, please refer to the external project:

👉 **IoTflow repository:** https://github.com/makethingshappy/IoTflow  
👉 See `/examples/` folder inside IoTflow for reference Node-RED and MQTT workflows.

(*No code is included here — this repository documents hardware only.*)

## Firmware Updates & Versioning

IoTsmart strictly follows the unified versioning structure described in the project’s Technical Specification.

Current hardware versions:

- `RP2040/v1.02/`  
- `RP2350A/v1.02/`  
- `ESP32-S3/v1.02/`  
- `XIAO/v1.02/`

All updates, revisions, and future hardware releases will follow the same pattern.

## Licensing

This repository uses separate licenses for different asset types:

- **Code:** [`LICENSE_CODE.md`](./LICENSE_CODE.md) – MIT License  
- **Hardware:** [`LICENSE_HARDWARE.md`](./LICENSE_HARDWARE.md) – CC BY-SA 4.0  
- **Documentation:** [`LICENSE_DOCS.md`](./LICENSE_DOCS.md)  
- **Media:** [`LICENSE_MEDIA.md`](./LICENSE_MEDIA.md)
