# Flipper-Zero-WIFI-Hat
Designing a wifi hat for the flipper zero from scratch using the ESP-32 and a custom PCB. The device was designed in KiCad.

# Bill of Materials (BOM)

This BOM contains all components required for the build, including electronics, PCB fabrication, shipping estimates, and the Flipper Zero used for development/testing.

Prices are based on the supplied supplier quotes.

---

# Electronic Components

| Qty | Manufacturer     | Part Number               | Description                                               | Unit Price (NOK) | Total (NOK) | Link |
| --: | ---------------- | ------------------------- | --------------------------------------------------------- | ---------------: | ----------: | ---- |
| 2 | Kamaya | RMC1/10K5101DTP | Thick Film Resistors - SMD 0805, 5.10 kΩ, 0.5%, Lead Free | 1.82 | 3.64 | https://no.mouser.com/en/ProductDetail/Kamaya/RMC1-10K5101DTP |
| 10 | Bourns | CR2512AJW-103ELF | Thick Film Resistors - SMD 2512, 10 kΩ, 5%, 1 W | 1.08 | 10.80 | https://no.mouser.com/en/ProductDetail/Bourns/CR2512AJW-103ELF |
| 1 | Same Sky | UJ20-C-H-G-MSMT-4B-P16-TR | USB Connector, Type-C 2.0, Horizontal SMT, 16 Pin | 4.51 | 4.51 | https://no.mouser.com/en/ProductDetail/Same-Sky/UJ20-C-H-G-MSMT-4B-P16-TR |
| 2 | Same Sky | TS04-66-65-BK-260-SMT | Tactile Switch, 6 × 6 mm, 6.5 mm Actuator, 260 gf | 1.73 | 3.46 | https://no.mouser.com/en/ProductDetail/Same-Sky/TS04-66-65-BK-260-SMT |
| 5 | Murata | GRM155D70G106ME18D | MLCC SMD 0402, 10 µF, 4 V, X7T, ±20% | 3.94 | 19.70 | https://no.mouser.com/en/ProductDetail/Murata/GRM155D70G106ME18D |
| 1 | Microchip | MCP1827S-3302E/EBVAO | LDO Voltage Regulator, 3.3 V, 1.5 A | 17.74 | 17.74 | https://no.mouser.com/en/ProductDetail/Microchip/MCP1827S-3302E-EBVAO |
| 1 | onsemi | 2N7002WT1G | Small Signal N-Channel MOSFET | 1.92 | 1.92 | https://no.mouser.com/en/ProductDetail/onsemi/2N7002WT1G |
| 1 | Same Sky | CPT-1775-3TH | Board Mount Buzzer, 3 V, 75 dB, Through Hole | 10.85 | 10.85 | https://no.mouser.com/en/ProductDetail/Same-Sky/CPT-1775-3TH |
| 1 | Espressif | ESP32-S3-WROOM-1-N16R8 | ESP32-S3 Module, 16 MB Flash, 8 MB PSRAM, PCB Antenna | 64.73 | 64.73 | https://no.mouser.com/en/ProductDetail/Espressif/ESP32-S3-WROOM-1-N16R8 |
| 1 | Espressif | ESP32-S3-WROOM-1U-N8 | ESP32-S3 Module, 8 MB Flash, IPEX Antenna Connector | 54.35 | 54.35 | https://no.mouser.com/en/ProductDetail/Espressif/ESP32-S3-WROOM-1U-N8 |
| 1 | Taoglas | GW17.07.0250E | IPEX Terminal Antenna | 80.13 | 80.13 | https://no.mouser.com/en/ProductDetail/Taoglas/GW17.07.0250E |
| 1 | Würth Elektronik | 693072010801 | MicroSD Card Connector, 8 Pin Hinge | 32.70 | 32.70 | https://no.mouser.com/en/ProductDetail/Wurth-Elektronik/693072010801 |

### Electronics Subtotal

**303.53 NOK (~$31.57 USD)**

---

# PCB Manufacturing

| Qty | Item | Cost (NOK) | Link |
| --: | ---- | ---------: | ---- |
| 1 | PCB + SMT stencil including shipping | 250.00 | JLCPCB |

### PCB Subtotal

**250.00 NOK (~$26 USD)**

---

# Additional Hardware

| Qty | Item | Cost (NOK) | Link |
| --: | ---- | ---------: | ---- |
| 1 | Flipper Zero | 2656.00 | Joom |

### Hardware Subtotal

**2656.00 NOK (~$276.22 USD)**

---

# Shipping

| Item | Cost (NOK) |
| ---- | ---------: |
| Mouser shipping and tax estimate | 459.61 |

### Shipping Subtotal

**459.61 NOK (~$47.80 USD)**

---

# Final Cost Summary

| Category | NOK | USD Approx. |
| -------- | --: | ----------: |
| Electronic components | 303.53 | $31.57 |
| PCB + stencil | 250.00 | $26.00 |
| Mouser shipping/tax | 459.61 | $47.80 |
| Flipper Zero | 2656.00 | $276.22 |

---

# Total Project Cost

## Complete Build

**3669.14 NOK**

**≈ $381 USD**

Budget estimate: **~$400 USD**

---

# Notes

- The BOM includes both ESP32-S3-WROOM modules:
  - ESP32-S3-WROOM-1-N16R8 (PCB antenna)
  - ESP32-S3-WROOM-1U-N8 (IPEX antenna connector)

- The Taoglas GW17.07.0250E antenna is required for the WROOM-1U module.

- Solder paste and hot plate equipment have been removed from the BOM.

- AliExpress items and shipping estimates have been removed.

- Prices are based on supplied quotes and may change with exchange rates.

# Notes

- The BOM includes both ESP32-S3-WROOM modules from the original order:
  - ESP32-S3-WROOM-1-N16R8 (PCB antenna)
  - ESP32-S3-WROOM-1U-N8 (IPEX antenna connector)
- The Taoglas GW17.07.0250E antenna is required for the WROOM-1U module.
- Solder paste and hot plate equipment have been removed from the BOM.
- AliExpress shipping estimate has been removed.
- Prices are based on the supplied order data and may change with exchange rates.

## Notes

- ESP32-S3-WROOM-1-N16R8 and ESP32-S3-WROOM-1U-N8 are both included from the original order list.
- The Taoglas GW17.07.0250E antenna is used with the ESP32-S3-WROOM-1U-N8 module.
- Assembly tools and solder paste have been removed from this BOM.
- Prices are based on the supplied quotes and may change with exchange rates and supplier pricing.
## Notes

- The BOM includes both ESP32-S3-WROOM variants as listed in the order:
  - ESP32-S3-WROOM-1-N16R8 (PCB antenna)
  - ESP32-S3-WROOM-1U-N8 (IPEX antenna)
- The Taoglas GW17.07.0250E antenna is required for the WROOM-1U module.
- Prices are based on the supplied Mouser/JLCPCB/AliExpress/Joom estimates.
- USD conversions are approximate and will vary with exchange rates.

*Approx 255 dollars to be safe*

Features:
USB-C for flashing the ESP-32-S3-WROOM-1 module
ISTP port for antennas
Bluetooth Low Energy compatibiltiy
WIFI 2.4ghz compatability
Fully designed for Flipper Zero pins
Is compatible with Flipper Zero wifi marauder
MicroSD compatible for storage of large data packets to prevent cluttering of the UART communication

Here are some pictures of the design:

<img width="729" height="649" alt="image" src="https://github.com/user-attachments/assets/459608d9-51e5-4511-9ac1-32ab3a06684c" />
<img width="918" height="649" alt="image" src="https://github.com/user-attachments/assets/fb7c944f-6f95-4e23-b340-19b83b96d19b" />

