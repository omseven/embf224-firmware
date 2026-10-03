# EMBF224 Full Drive Booster Pump Controller Firmware

[![Firmware Version](https://img.shields.io/badge/Firmware-V1.85-brightgreen.svg)](https://github.com/omseven/embf224-firmware/releases/tag/EMBF224)
[![Hardware](https://img.shields.io/badge/Hardware-ESP32--S3-blue.svg)](https://elecmarketing.ir/product/controller-boosterpump-embf224/)
[![Manufacturer](https://img.shields.io/badge/Manufacturer-ElecMarketing-orange.svg)](https://elecmarketing.ir/)

Official firmware distribution repository and Over-The-Air (OTA) update endpoint for the **EMBF224 Full-Drive Booster Pump Controller** designed and manufactured by **ElecMarketing** (الکمارکتینگ).

---

## 📌 Product Overview

The **EMBF224** is an industrial smart booster pump controller engineered for **Full-Drive multi-pump systems** (up to 4 pumps with 4 independent variable frequency inverters). Each pump is driven by a dedicated inverter to minimize mechanical wear, optimize energy efficiency, and maintain constant water pressure via real-time closed-loop PID control.

🔗 **Official Product Page:** [https://elecmarketing.ir/product/controller-boosterpump-embf224/](https://elecmarketing.ir/product/controller-boosterpump-embf224/)

---

## ✨ Key Features & Specifications

### ⚙️ Control & Drive Interfaces
- **4 Dedicated Analog Outputs:** 0–10V / 0–5V control signals for up to 4 independent inverters with software channel reassignment.
- **True PID Regulation:** High-precision pressure stabilization with configurable Proportional, Integral, and Derivative terms.
- **Dual Analog Pressure Inputs:** Redundant dual pressure sensor inputs (6 Bar / 10 Bar / 16 Bar / 25 Bar / 40 Bar / 60 Bar) supporting `4–20 mA`, `0–20 mA`, `0–10 mA`, `0–5 V`, and `2–10 V`.
- **Dual PT100 Temperature Inputs:** Collector and manifold thermal protection and temperature monitoring.
- **4 Multi-Function Inputs (MFI 1–4):** External phase control, external level float switch, emergency stop, maximum pressure switch, and hardware pump service lockout.
- **4 Multi-Function Relay Outputs (MFO 1–4):** Exhaust fan, external alarm beacon, system ready, and reservoir auto-fill tank control.

### 🔄 Intelligent Pump Management & Protection
- **Dual Changeover (Cyclic Operation):**
  - *Time-based changeover* (runtime equal distribution).
  - *Start/Stop-based changeover* (on each duty cycle).
- **Intelligent Fault Detection & Failover:** Automatic faulty pump isolation and seamless backup pump staging.
- **Full Load & Leakage Protection:** Detection of closed inlet/outlet valves, pump cavitation/airlock, and pipeline rupture.
- **Smart Sleep & Wake Mechanism:** 4-condition energy-saving sleep mode with zero-consumption detection.
- **Integrated Liquid Level Control:** Built-in liquid level protection with configurable float delay timers.

### 🖥️ User Interface & Monitoring
- **Integrated Web Interface & Wi-Fi Hotspot:** Direct smartphone/PC configuration, live pressure dashboard, runtime monitoring, and one-click OTA firmware updates.
- **Graphic Display & RGB Status Indicator:** High-resolution 8000-pixel graphic LCD accompanied by a multi-color RGB LED indicator (Green: Normal, Blue: Low Pressure, Yellow: High Pressure, Red: Fault, Purple: Manual Mode).
- **BMS & RS-485 Communication:** Modbus RTU communication for building management systems (BMS).
- **Power Supply:** 24V DC industrial power input for high reliability and noise immunity.

---

## 🚀 Firmware Release & OTA Updates

This repository serves as the central backend for online and local OTA firmware distribution.

### Latest Release
- **Version:** `V1.85`
- **Release Tag:** [`EMBF224`](https://github.com/omseven/embf224-firmware/releases/tag/EMBF224)
- **Binary Image:** [`Booster_EMBF224.efw`](https://github.com/omseven/embf224-firmware/releases/download/EMBF224/Booster_EMBF224.efw)
- **Metadata:** [`version.json`](https://raw.githubusercontent.com/omseven/embf224-firmware/main/version.json)

### OTA Update Flow
1. Connect to the controller's Wi-Fi Access Point or local network.
2. Open the built-in Web Management Panel in your browser (`http://192.168.4.1`).
3. Navigate to **System / Update** (بروزرسانی).
4. Select **Online Update** to automatically fetch the latest release from this repository or upload the `.efw` package manually.

---

## 📚 Documentation & Downloads

| Resource | Link |
| :--- | :--- |
| 📖 **User Manual (کاتالوگ و راهنما)** | [EMBF224 User Manual (PDF)](https://elecmarketing.ir/wp-content/uploads/2025/01/EMBF224.pdf) |
| 🔄 **Update Guide (راهنمای بروزرسانی)** | [Firmware Update Guide (PDF)](https://elecmarketing.ir/wp-content/uploads/2025/01/%D8%AF%D9%81%D8%AA%D8%B1%DA%86%D9%87-%D8%B1%D8%A7%D9%87%D9%86%D9%85%D8%A7%DB%8C-%D8%A8%D9%87-%D8%B1%D9%88%D8%B2%D8%B1%D8%B3%D8%A7%D9%86%DB%8C-%D9%81%D9%88%D9%84-%D8%AF%D8%B1%D8%A7%DB%8C%D9%88.pdf) |
| ⚡ **Wiring Diagram - 1 Drive** | [1 Drive 1 Pump Schematic](https://elecmarketing.ir/wp-content/uploads/2025/01/Full-drive-controller-1PUMP.pdf) |
| ⚡ **Wiring Diagram - 2 Drives** | [2 Drives 2 Pumps Schematic](https://elecmarketing.ir/wp-content/uploads/2025/01/Full-drive-controller-2PUMP.pdf) |
| ⚡ **Wiring Diagram - 3 Drives** | [3 Drives 3 Pumps Schematic](https://elecmarketing.ir/wp-content/uploads/2025/01/Full-drive-controller-3PUMP.pdf) |
| ⚡ **Wiring Diagram - 4 Drives** | [4 Drives 4 Pumps Schematic](https://elecmarketing.ir/wp-content/uploads/2025/01/Full-drive-controller-4PUMP.pdf) |

---

## 🏢 Manufacturer & Support

- **Manufacturer:** [ElecMarketing (الکمارکتینگ)](https://elecmarketing.ir/)
- **Technical Support:** 24/7 Support via WhatsApp / Telegram / Phone
- **Warranty:** 1-Year Replacement Warranty & 5-Year After-Sales Service
