# Flipper-Zero-WIFI-Hat
Designing a wifi hat for the flipper zero from scratch using the ESP-32 and a custom PCB. The device was designed in KiCad.

## Bill of Materials (BOM)

| Qty | Part Number | Description | Unit Price | Total | Supplier |
|---:|---|---|---:|---:|---|
| 2 | RMC1/10K5101DTP | 0805 5.1 kΩ 0.5% Thick Film Resistor | kr 1.82 | kr 3.64 | [Mouser](https://no.mouser.com/en/ProductDetail/Kamaya/RMC1-10K5101DTP?qs=GedFDFLaBXG1LvR8QK0EcA%3D%3D) |
| 10 | CR2512AJW-103ELF | 2512 10 kΩ 1 W Thick Film Resistor | kr 1.08 | kr 10.80 | [Mouser](https://no.mouser.com/en/ProductDetail/Bourns/CR2512AJW-103ELF?qs=GedFDFLaBXEqggePGBQmuQ%3D%3D) |
| 1 | UJ20-C-H-G-MSMT-4B-P16-TR | USB Type-C 2.0 Connector (16-pin) | kr 4.51 | kr 4.51 | [Mouser](https://no.mouser.com/en/ProductDetail/Same-Sky/UJ20-C-H-G-MSMT-4B-P16-TR?qs=6avfeC6zeS47Lo0obtd7QQ%3D%3D) |
| 2 | TS04-66-65-BK-260-SMT | 6×6 mm SMT Tactile Switch | kr 1.73 | kr 3.46 | [Mouser](https://no.mouser.com/en/ProductDetail/Same-Sky/TS04-66-65-BK-260-SMT?qs=A6eO%252BMLsxmTvOTHTIBabhQ%3D%3D) |
| 5 | GRM155D70G106ME18D | 10 µF 0402 X7T MLCC Capacitor | kr 3.94 | kr 19.70 | [Mouser](https://no.mouser.com/en/ProductDetail/Murata/GRM155D70G106ME18D?qs=doiCPypUmgEf2sthzNH4lA%3D%3D) |
| 1 | MCP1827S-3302E/EBVAO | 3.3 V 1.5 A LDO Regulator | kr 17.74 | kr 17.74 | [Mouser](https://no.mouser.com/en/ProductDetail/Microchip/MCP1827S-3302E-EBVAO?qs=W%2FMpXkg%252BdQ5AjGztZ%252B4L5g%3D%3D) |
| 1 | 2N7002WT1G | N-Channel MOSFET | kr 1.92 | kr 1.92 | [Mouser](https://no.mouser.com/en/ProductDetail/onsemi/2N7002WT1G?qs=Jh7l0IbPjidRgzyVQt6Xnw%3D%3D) |
| 1 | CPT-1775-3TH | 3 V Through-Hole Buzzer | kr 10.85 | kr 10.85 | [Mouser](https://no.mouser.com/en/ProductDetail/Same-Sky/CPT-1775-3TH?qs=yc9RBI4tIAK9HFcgM%252BStOQ%3D%3D) |
| 1 | ESP32-S3-WROOM-1-N16R8 | ESP32-S3 Module (16 MB Flash, 8 MB PSRAM) | kr 64.73 | kr 64.73 | [Mouser](https://no.mouser.com/en/ProductDetail/Espressif/ESP32-S3-WROOM-1-N16R8?qs=Li%252BoUPsLEnvQc9gW6AMhZg%3D%3D) |
| 1 | ESP32-S3-WROOM-1U-N8 | ESP32-S3 Module (8 MB Flash, U.FL) | kr 54.35 | kr 54.35 | [Mouser](https://no.mouser.com/en/ProductDetail/Espressif/ESP32-S3-WROOM-1U-N8?qs=Li%252BoUPsLEntthfxdhgRI1w%3D%3D) |
| 1 | GW17.07.0250E | 2.4 GHz IPEX Antenna | kr 80.13 | kr 80.13 | [Mouser](https://no.mouser.com/en/ProductDetail/Taoglas/GW17.07.0250E?qs=AL7xPqYNrmTPXhCuHzQycg%3D%3D) |
| 1 | 693072010801 | MicroSD Card Connector | kr 32.70 | kr 32.70 | [Mouser](https://no.mouser.com/en/ProductDetail/Wurth-Elektronik/693072010801?qs=7gQLVZk5cPmw4uU1mAcUFg%3D%3D) |
| 1 | TS391AX50 | Sn63/Pb37 No-Clean Solder Paste (50 g) | kr 133.92 | kr 133.92 | [Mouser](https://no.mouser.com/en/ProductDetail/Chip-Quik/TS391AX50?qs=1mbolxNpo8c66lK8U%252Bbg8g%3D%3D) |
| 1 | HP20 | ALIENTEK HP20 Mini Hot Plate (200 W) | kr 1099.74 | kr 1099.74 | AliExpress |
| 1 | — | PCB + SMT Stencil (incl. shipping) | kr 400.00 | kr 400.00 | JLCPCB |

### Additional Costs

| Item | Cost |
|---|---:|
| Mouser shipping & taxes | kr 459.61 |
| AliExpress shipping | kr 31.42 |

### Estimated Total

| Category | Cost |
|---|---:|
| Components & tools | **kr 1,937.19** |
| Shipping & taxes | **kr 491.03** |
| **Grand Total** | **kr 2,428.22** |

Features:
USB-C for flashing the ESP-32-S3-WROOM-1 module
ISTP port for antennas
Bluetooth Low Energy compatibiltiy
WIFI 2.4ghz compatability
Fully designed for Flipper Zero pins
Is compatible with Flipper Zero wifi marauder
MicroSD compatible for storage of large data packets to prevent cluttering of the UART communication

Parts:
Solder RMA Solder Paste SN63/PB37 T4 (35g Syringe)
Adafruit
Desc.
Soldering & Desoldering Stations Mini Brass Hot Plate Preheater with USB-C PD or DC - MHP50-B5
Antennas IPEX TERMINAL ANTENNA

Espressif
Desc.
Multiprotocol Modules SMD module, ESP32-S3, 8 MB SPI flash, IPEX antenna connector

Espressif
Desc.
Multiprotocol Modules SMD module, ESP32-S3R8 with 3.3V, 8 MB Octal PSRAM die inside, 16 MB Quad SPI flash, PCB antenna

Same Sky
Desc.
Buzzers & Audio Indicators - Board Mount buzzer, 17 mm x 7.5 mm deep, P, 3 V, 75 dB, Through Hole, Audio Transduce


onsemi
Desc.
MOSFETs SMALL SIGNAL MOSFET 6.8V LO C

Microchip
Desc.
LDO Voltage Regulators 1.5A LDO Regulator


Murata
Desc.
Multilayer Ceramic Capacitors MLCC - SMD/SMT 0402 4VDC 10uF 20% X7T


Same Sky
Desc.
Tactile Switches 6 x 6 mm, 6.5 mm Act Height, 260 gf, Black, Surface Mount, SPST,


Same Sky
Desc.
USB Connectors USB Jack, Type C, 2.0, MSMT, Horizontal, Gold Flash, 16 Pin, TR

Bourns
Desc.
Thick Film Resistors - SMD ResA 2512 10k 5% 1W TC200

Kamaya
Desc.
Thick Film Resistors - SMD 0805 5K10 0.5% Lead Free

Here are some pictures of the design:

<img width="729" height="649" alt="image" src="https://github.com/user-attachments/assets/459608d9-51e5-4511-9ac1-32ab3a06684c" />
<img width="918" height="649" alt="image" src="https://github.com/user-attachments/assets/fb7c944f-6f95-4e23-b340-19b83b96d19b" />

