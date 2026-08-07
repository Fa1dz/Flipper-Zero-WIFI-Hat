# Flipper-Zero-WIFI-Hat
Designing a wifi hat for the flipper zero from scratch using the ESP-32 and a custom PCB. The device was designed in KiCad.

## Bill of Materials (BOM)

| Qty | Part Number | Description | Unit Price (USD) | Total (USD) | Supplier |
|---:|---|---|---:|---:|---|
| 2 | RMC1/10K5101DTP | 0805 5.1 kΩ 0.5% Thick Film Resistor | $0.19 | $0.38 | [Mouser](https://no.mouser.com/en/ProductDetail/Kamaya/RMC1-10K5101DTP?qs=GedFDFLaBXG1LvR8QK0EcA%3D%3D) |
| 10 | CR2512AJW-103ELF | 2512 10 kΩ 1 W Thick Film Resistor | $0.11 | $1.12 | [Mouser](https://no.mouser.com/en/ProductDetail/Bourns/CR2512AJW-103ELF?qs=GedFDFLaBXEqggePGBQmuQ%3D%3D) |
| 1 | UJ20-C-H-G-MSMT-4B-P16-TR | USB Type-C 2.0 Connector (16-pin) | $0.47 | $0.47 | [Mouser](https://no.mouser.com/en/ProductDetail/Same-Sky/UJ20-C-H-G-MSMT-4B-P16-TR?qs=6avfeC6zeS47Lo0obtd7QQ%3D%3D) |
| 2 | TS04-66-65-BK-260-SMT | 6×6 mm SMT Tactile Switch | $0.18 | $0.36 | [Mouser](https://no.mouser.com/en/ProductDetail/Same-Sky/TS04-66-65-BK-260-SMT?qs=A6eO%252BMLsxmTvOTHTIBabhQ%3D%3D) |
| 5 | GRM155D70G106ME18D | 10 µF 0402 X7T MLCC Capacitor | $0.41 | $2.04 | [Mouser](https://no.mouser.com/en/ProductDetail/Murata/GRM155D70G106ME18D?qs=doiCPypUmgEf2sthzNH4lA%3D%3D) |
| 1 | MCP1827S-3302E/EBVAO | 3.3 V 1.5 A LDO Regulator | $1.84 | $1.84 | [Mouser](https://no.mouser.com/en/ProductDetail/Microchip/MCP1827S-3302E-EBVAO?qs=W%2FMpXkg%252BdQ5AjGztZ%252B4L5g%3D%3D) |
| 1 | 2N7002WT1G | N-Channel MOSFET | $0.20 | $0.20 | [Mouser](https://no.mouser.com/en/ProductDetail/onsemi/2N7002WT1G?qs=Jh7l0IbPjidRgzyVQt6Xnw%3D%3D) |
| 1 | CPT-1775-3TH | 3 V Through-Hole Buzzer | $1.13 | $1.13 | [Mouser](https://no.mouser.com/en/ProductDetail/Same-Sky/CPT-1775-3TH?qs=yc9RBI4tIAK9HFcgM%252BStOQ%3D%3D) |
| 1 | ESP32-S3-WROOM-1-N16R8 | ESP32-S3 Module (16 MB Flash, 8 MB PSRAM) | $6.71 | $6.71 | [Mouser](https://no.mouser.com/en/ProductDetail/Espressif/ESP32-S3-WROOM-1-N16R8?qs=Li%252BoUPsLEnvQc9gW6AMhZg%3D%3D) |
| 1 | ESP32-S3-WROOM-1U-N8 | ESP32-S3 Module (8 MB Flash, U.FL) | $5.64 | $5.64 | [Mouser](https://no.mouser.com/en/ProductDetail/Espressif/ESP32-S3-WROOM-1U-N8?qs=Li%252BoUPsLEntthfxdhgRI1w%3D%3D) |
| 1 | GW17.07.0250E | 2.4 GHz IPEX Antenna | $8.31 | $8.31 | [Mouser](https://no.mouser.com/en/ProductDetail/Taoglas/GW17.07.0250E?qs=AL7xPqYNrmTPXhCuHzQycg%3D%3D) |
| 1 | 693072010801 | MicroSD Card Connector | $3.39 | $3.39 | [Mouser](https://no.mouser.com/en/ProductDetail/Wurth-Elektronik/693072010801?qs=7gQLVZk5cPmw4uU1mAcUFg%3D%3D) |
| 1 | TS391AX50 | Sn63/Pb37 No-Clean Solder Paste (50 g) | $13.89 | $13.89 | [Mouser](https://no.mouser.com/en/ProductDetail/Chip-Quik/TS391AX50?qs=1mbolxNpo8c66lK8U%252Bbg8g%3D%3D) |
| 1 | HP20 | ALIENTEK HP20 Mini Hot Plate (200 W) | $114.03 | $114.03 | AliExpress |
| 1 | — | PCB + SMT Stencil (incl. shipping) | $41.49 | $41.49 | JLCPCB |

### Additional Costs

| Item | Cost (USD) |
|---|---:|
| Mouser shipping & taxes | $47.68 |
| AliExpress shipping | $3.26 |

### Estimated Total

| Category | Cost (USD) |
|---|---:|
| Components & tools | **$200.95** |
| Shipping & taxes | **$50.94** |
| **Grand Total** | **$251.89** | *Approx 255 to be safe*

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

