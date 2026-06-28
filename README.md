# Raspberry Pi Pico RS485 Industrial IoT Interface

A custom **Industrial IoT Interface PCB** designed using **KiCad**, built around the **Raspberry Pi Pico**. This board provides reliable power management, RS-485 communication, relay control, sensor interfacing, and GPIO expansion for embedded and industrial automation applications.

## 📌 Features

- ⚡ 24V DC to 5V DC Buck Converter
- 🔋 5V to 3.3V LDO Regulator
- 🔄 RS-485 Communication (MAX485)
- 🌡️ SHT31 Temperature & Humidity Sensor (I²C)
- 🔌 Relay Driver Circuit
- 💡 User Status LEDs
- 🎛️ DIP Switch Inputs
- 🔘 Push Button Input
- 📡 SPI & I²C Expansion Headers
- 🛡️ TVS/ESD Protection
- 📐 Designed using KiCad

## 🛠️ Hardware Components

| Component | Description |
|-----------|-------------|
| Raspberry Pi Pico | Main Controller |
| TSR 1-2450 | 24V → 5V Buck Converter |
| TLV1117-3.3 | 5V → 3.3V LDO |
| MAX485 | RS-485 Transceiver |
| SHT31 | Temperature & Humidity Sensor |
| Relay Driver | BC817 + Flyback Diode |
| LEDs | Status Indicators |
| DIP Switch | User Configuration |

## 📂 Repository Structure

```
.
├── Schematic/
├── PCB/
├── Libraries/
├── Images/
└── README.md
```

## 🚀 Applications

- Industrial Automation
- Industrial IoT (IIoT)
- Remote Sensor Nodes
- Data Acquisition Systems
- Environmental Monitoring
- PLC Interface Projects

## 🧰 Software

- KiCad
- Raspberry Pi Pico SDK / MicroPython (Optional)

## 📸 Preview

> Add schematic and PCB images here.

## 👨‍💻 Author

**Akshat Jaiswal**

---

⭐ If you found this project helpful, consider giving it a **Star** on GitHub!
