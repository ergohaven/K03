## K:03 is an ergonomic, split, mechanical keyboard with five thumb keys on each half and the ability to install encoders on either half

*K:03 keeps a 60% footprint, a 60-key layout, and clean ergonomics across two versions: the Wired Edition and the Wireless Edition*

![K:03 v4](images/K03_v4.png)

## Design philosophy
K:03 combines futuristic styling, a compact form factor, and practical ergonomics. The Wired Edition is built for a feature-rich daily setup, and the Wireless Edition adds Bluetooth portability

![K:03 v4 WE](images/K03_v4_WE.png)

## Features
- Split, ergonomic design
- 60 fully programmable keys and 15 additional layers for all your tasks
- Optional encoder support on either half
- Hot-swappable PCB (MX sockets)

### Wired Edition
- Powered by RP2040 and QMK firmware
- USB-C connection between halves
- Easily remap any key and customize your keyboard with [Vial](https://eh.industries/vial)
- OLED display and active-layer indicator

![K:03 v4 Layouts](images/K03_v4_en.png)

### Wireless Edition
- Powered by nRF52840 and RMK/ZMK firmware
- Bluetooth connectivity for up to 6 devices
- Rechargeable 200 mAh battery
- USB-C connection

![K:03 v4 WE Layouts](images/K03_WE_en.png)

## This repository contains all files related to this keyboard
PCB and schematic for [K:03 v4](https://oshwlab.com/yuriiq/project_vqxdarna) and [K:03 v4 – Wireless Edition](https://oshwlab.com/yuriiq/project_somqsptz)

### BOM
#### K:03 v4

| Components | Quantity (pcs) |
| --- | ---: |
| K:03 v4 PCB | 1 |
| RP2040 MCU, LQFN-56 | 2 |
| OLED SSD1306 Display, 128x32, DSP-OLED-128X32 | 2 |
| MX hotswap sockets | 60 |
| 1N4148W diodes, SOD-523F | 60 |
| Resistor 0402 5.1 kΩ | 8 |
| Resistor 0402 1 kΩ | 2 |
| Resistor 0402 200 Ω | 2 |
| Resistor 0402 27 Ω | 4 |
| Capacitor 0402 1 nF | 4 |
| Capacitor 0402 15 pF | 4 |
| Capacitor 0402 100 nF | 10 |
| Capacitor 0402 2.2 µF | 2 |
| SMD LED SK6803MINI-E-001 | 2 |
| P-channel MOSFET, SOT-23, JSM2301S | 2 |
| SMD tactile switch TS-1187F-1526 | 4 |
| LDO, SOT-23-3, 662K | 2 |
| SPI flash W25Q32JVSSIQ | 2 |
| SMD USB connector USB-TYPE-C-021 | 2 |
| SMD USB connector USB-TYPE-C-018 | 2 |
| SMD crystal resonator 12 MHz XXHCCLNANF-12.000000MHZ | 2 |
| 3M bumpons (8 mm) | 8 |
| MagSafe ring (optional) | 2 |

#### K:03 v4 – Wireless Edition

| Components | Quantity (pcs) |
| --- | ---: |
| K:03 Wireless Edition PCB | 1 |
| E73-2G4M08S1C Bluetooth module | 2 |
| MX hotswap sockets | 60 |
| 1N4148W diodes, SOD-523F | 60 |
| B5819WS Schottky diode, SOD-323 | 2 |
| Resistor 0402 5.1 kΩ | 6 |
| Resistor 0402 100 kΩ | 2 |
| Resistor 0402 806 kΩ | 2 |
| Resistor 0402 2 MΩ | 2 |
| Resistor 0402 10 kΩ | 2 |
| Capacitor 0402 4.7 µF | 4 |
| SMD LED SK6803MINI-E-001 | 2 |
| P-channel MOSFET, SOT-23, JSM2301S | 4 |
| MSK12CO2-SZ SMD slide switch | 2 |
| LN2054Y42AMR linear Li-Ion battery charger, SOT-23-5 | 2 |
| ZX-SH1.0-2PWT SMD wire-to-board connector | 2 |
| AP2112K-3.3TRG1 LDO regulator, SOT-23-5 | 2 |
| SMD USB connector USB-TYPE-C-018 | 2 |
| TS5235A 250gf 025 SMD tactile switch | 2 |
| Li-Pol, 3.7V, 200mAh, 402030 with JST SH-1.0mm, 2 pin connector | 2 |
| 3M bumpons (8 mm) | 8 |
| MagSafe ring (optional) | 2 |
| Plexiglass window for case, 24x23 mm (optional) | 2 |

## License
The files in this repository are licensed under the Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License

## Useful links

- K:03 v4:
  - [Case for 3D printing (STL)](stls/k03-v4)
  - [Case model for editing (STEP)](step/k03-v4)
  - [Circuit schematic](https://oshwlab.com/yuriiq/project_vqxdarna)

- K:03 v4 – Wireless Edition:
  - [Case for 3D printing (STL)](stls/k03-v4-we)
  - [Case model for editing (STEP)](step/k03-v4-we)
  - [Circuit schematic](https://oshwlab.com/yuriiq/project_somqsptz)

### Firmware
- [Pre-compiled files](https://github.com/ergohaven/keymap_hub)
- Source code:
  - wired [QMK](https://github.com/ergohaven/vial-qmk)
  - wireless [RMK](https://github.com/ergohaven/rmk-eh)

## Availability
The complete keyboard (not a DIY kit) is available for purchase at [eh.industries](https://eh.industries/)
