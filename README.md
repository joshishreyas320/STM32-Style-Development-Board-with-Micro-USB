# STM32-Style Development Board with Micro USB

> KiCad PCB Design | 2-Layer Board | ATmega328P-M + Micro USB

---

## Project Description
An Arduino-compatible MCU development board designed using **KiCad**, featuring an **ATmega328P-M** microcontroller, **Micro USB** interface for power and programming, and an **LM1117DT-5V** onboard voltage regulator. Dual 15-pin expansion headers provide full GPIO access in an Arduino-compatible footprint. Includes SMD resonator, power LED, and reset switch.

**Short Description (≤350 chars):**
> Arduino-compatible MCU development board with Micro USB interface, LM1117 5V regulation, dual 15-pin headers, and onboard LED+reset. Designed in KiCad with ATmega328P-M for embedded development use.

---

## Key Components

| Component | Description |
|-----------|-------------|
| **ATmega328P-M** | Core MCU – Arduino-compatible |
| **USB_B_Micro** | Micro USB connector for power and programming |
| **LM1117DT-5.0** | 5V LDO regulator from USB VBUS |
| **SMD Resonator (3-pin)** | Stable MCU clock source |
| **2× 15-pin Headers** | GPIO/power expansion (Arduino-style) |
| **Reset Switch** | Manual MCU reset |
| **LED** | Power indicator |
| **Decoupling Capacitors** | +3.3V and +5V rail filtering |

---

## Design Features
- Micro USB for both power supply and MCU programming
- LM1117DT-5.0 provides regulated 5V from USB VBUS
- ATmega328P-M with Arduino-compatible pinout
- SMD resonator for reliable clock without external components
- Compact 2-layer PCB with dual 15-pin expansion headers
- Onboard power LED and reset switch for user interaction

---

## Signal Flow
```
Micro USB Connector (VBUS / D+ / D-)
       ↓
  LM1117DT-5.0 – Voltage Regulator (5V)
       ↓
  ATmega328P-M – MCU
       ↓
  SMD Resonator ← Clock Source
  15-pin Dual Headers ← GPIO / Power Expansion
  LED ← Power Indicator
  Reset Switch ← Manual Reset
```

---

## Files Included
- `Development_board_project_with_STM_components_and_Micro_USB.kicad_sch` – Schematic
- `Development_board_project_with_STM_components_and_Micro_USB.kicad_pcb` – PCB Layout
- `Gerber_File_Development_board_project_with_STM_components_and_Micro_USB.zip` – Gerber files

---

