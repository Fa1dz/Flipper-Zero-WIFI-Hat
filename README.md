# Flipper-Zero-WIFI-Hat
Designing a wifi hat for the flipper zero from scratch using the ESP-32 and a custom PCB. The device was designed in KiCad.

# Bill of Materials (BOM)

## Electronics

| Qty | Manufacturer | Part Number | Description | Unit Price (NOK) | Total (NOK) | Link |
|---:|---|---|---|---:|---:|---|
| 2 | Kamaya | RMC1/10K5101DTP | Thick Film Resistor SMD 0805, 5.10 kΩ, 0.5% | 1.82 | 3.64 | https://no.mouser.com/en/ProductDetail/Kamaya/RMC1-10K5101DTP |
| 10 | Bourns | CR2512AJW-103ELF | Thick Film Resistor SMD 2512, 10 kΩ, 5%, 1 W | 1.08 | 10.80 | https://no.mouser.com/en/ProductDetail/Bourns/CR2512AJW-103ELF |
| 1 | Same Sky | UJ20-C-H-G-MSMT-4B-P16-TR | USB Type-C Connector, USB 2.0, 16 pin, SMT | 4.51 | 4.51 | https://no.mouser.com/en/ProductDetail/Same-Sky/UJ20-C-H-G-MSMT-4B-P16-TR |
| 2 | Same Sky | TS04-66-65-BK-260-SMT | Tactile Switch 6×6 mm, 6.5 mm actuator, 260 gf | 1.73 | 3.46 | https://no.mouser.com/en/ProductDetail/Same-Sky/TS04-66-65-BK-260-SMT |
| 5 | Murata | GRM155D70G106ME18D | MLCC 0402, 10 µF, 4 V, X7T, ±20% | 3.94 | 19.70 | https://no.mouser.com/en/ProductDetail/Murata/GRM155D70G106ME18D |
| 1 | Microchip | MCP1827S-3302E/EBVAO | 3.3 V 1.5 A LDO Voltage Regulator | 17.74 | 17.74 | https://no.mouser.com/en/ProductDetail/Microchip/MCP1827S-3302E-EBVAO |
| 1 | onsemi | 2N7002WT1G | Small Signal N-Channel MOSFET | 1.92 | 1.92 | https://no.mouser.com/en/ProductDetail/onsemi/2N7002WT1G |
| 1 | Same Sky | CPT-1775-3TH | 3 V Board Mount Buzzer, 75 dB | 10.85 | 10.85 | https://no.mouser.com/en/ProductDetail/Same-Sky/CPT-1775-3TH |
| 1 | Espressif | ESP32-S3-WROOM-1-N16R8 | ESP32-S3 Module, 16 MB Flash, 8 MB PSRAM, PCB antenna | 64.73 | 64.73 | https://no.mouser.com/en/ProductDetail/Espressif/ESP32-S3-WROOM-1-N16R8 |
| 1 | Espressif | ESP32-S3-WROOM-1U-N8 | ESP32-S3 Module, 8 MB Flash, IPEX antenna connector | 54.35 | 54.35 | https://no.mouser.com/en/ProductDetail/Espressif/ESP32-S3-WROOM-1U-N8 |
| 1 | Taoglas | GW17.07.0250E | IPEX Terminal Antenna | 80.13 | 80.13 | https://no.mouser.com/en/ProductDetail/Taoglas/GW17.07.0250E |
| 1 | Würth Elektronik | 693072010801 | MicroSD Card Connector, 8 Pin Hinge | 32.70 | 32.70 | https://no.mouser.com/en/ProductDetail/Wurth-Elektronik/693072010801 |

## Assembly Materials

| Qty | Item | Price (NOK) | Total (NOK) | Link |
|---:|---|---:|---:|---|
| 1 | Chip Quik TS391AX50 No-Clean Solder Paste Sn63/Pb37 T4 50g | 133.92 | 133.92 | https://no.mouser.com/en/ProductDetail/Chip-Quik/TS391AX50 |
| 1 | ALIENTEK HP20 Hot Plate Preheater 200 W | 550.00 | 550.00 | AliExpress |
| 1 | PCB + SMT Stencil + Shipping | 400.00 | 400.00 | JLCPCB |

## Shipping / Additional Items

| Item | Cost (NOK) |
|---|---:|
| Mouser shipping and tax estimate | 459.61 |
| AliExpress shipping estimate | 31.42 |
| Flipper Zero (Joom) | 2656.00 |

---

# Cost Summary

| Category | NOK | USD Approx. |
|---|---:|---:|
| Electronic components | 303.53 | $28.84 |
| Solder paste | 133.92 | $12.72 |
| PCB + stencil | 400.00 | $38.00 |
| Hot plate | 550.00 | $52.25 |
| Mouser shipping/tax | 459.61 | $43.66 |
| AliExpress shipping | 31.42 | $2.99 |
| Flipper Zero | 2656.00 | $252.32 |

## Total Project Cost

### Without Flipper Zero
**2308.48 NOK ≈ $219.31 USD**

### Complete Build Including Flipper Zero
**4964.48 NOK ≈ $471.63 USD**

---

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

