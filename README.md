# M460T Input Module · Input Pre Amps

Ward-Beck Systems M460T, 1974|7. Wiki page: [M460T on WBSps.ca](https://wardbecksystems.github.io/WBSps.ca/PAGES/M460T.html)

| Folder | What is in it | Files |
|---|---|---|
| [SCHEMATICS/](SCHEMATICS/) | electrical drawings: schematics, functional diagrams, component layouts, wiring | 1 |
| [MECHANICAL/](MECHANICAL/) | front panels, cover plates, metalwork, assemblies; the front panel as vectors | 2 |
| [PINOUTS/](PINOUTS/) | the RTO-144 connector: connection sheets, connector layouts, rear views | 32 |
| [MANUALS/](MANUALS/) | manuals, manual pages, price lists, brochures, documents | 1 |
| [PHOTOS/](PHOTOS/) | photographs of the module | 1 |
| [SOFTWARE/](SOFTWARE/) | program listings, firmware, the plugin | 1 |
| [KICAD/](KICAD/) | KiCad schematics traced from the drawings, the symbol, PCB projects | 2 |
| [OCR/](OCR/) | the note of every file: date, origin, title block, OCR text | 4 |

## Pinouts

_Pinouts: the RTO-144 edge connector (connection sheets, connector layouts and rear views, strapping), and the pinout / connections drawings made from them. The module root `RTO.json` lists every contact._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKVUJBZTFCM2dRVmM/view?resourcekey=0-KZIVjb4U-apVDjdW8rMS1g" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKVUJBZTFCM2dRVmM&resourcekey=0-KZIVjb4U-apVDjdW8rMS1g" width="240" alt="1974 - M460T - Input Module - Pin Outs (2).pdf"></a><br><sub>1974|7 · Input Module - Pin Outs (2)</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKYmwycDFYTXhZcFk/view?resourcekey=0-zPIpHa2MFlQpzTytcldYUA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKYmwycDFYTXhZcFk&resourcekey=0-zPIpHa2MFlQpzTytcldYUA" width="240" alt="1974 - M460T - Input Module - Pin Outs.pdf"></a><br><sub>1974|7 · Input Module - Pin Outs</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKNF9BMWJ2cWlPRkE/view?resourcekey=0-V6NqBYHiIqJaMPMnBO4wig" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKNF9BMWJ2cWlPRkE&resourcekey=0-V6NqBYHiIqJaMPMnBO4wig" width="240" alt="1974 - M460T - Pin Out P1.jpg"></a><br><sub>1974|7 · Pin Out P1 · <a href="PINOUTS/1974%20-%20M460T%20-%20Pin%20Out%20P1%20(EXTRACTED).svg">vectors</a></sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKU2ZvUEZpNG5nY1U/view?resourcekey=0-7QxYYW2v6AWZ2-hoid2Lhw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKU2ZvUEZpNG5nY1U&resourcekey=0-7QxYYW2v6AWZ2-hoid2Lhw" width="240" alt="1974 - M460T - Pin Out P2.jpg"></a><br><sub>1974|7 · Pin Out P2 · <a href="PINOUTS/1974%20-%20M460T%20-%20Pin%20Out%20P2%20(EXTRACTED).svg">vectors</a></sub></td></tr>
</table>

Not on Google Drive yet: `M460T - RTO-144 Connections.pdf`

## RTO-144 pinout

Read from 4 pinout pictures (each its own `.pinout.json` beside it); the RTO-144 sheet agrees on 25 of 25 contacts. Every contact, with where it was read: [`RTO.json`](RTO.json). How a picture becomes this table: [the pinout decision tree](https://github.com/WardBeckSystems/WBSps.ca/blob/main/2026/Engineering/PINOUTS.md).

| Pin | Signal | Kind | Port | Confidence |
|---|---|---|---|---|
| P1-1 | MIC IN | in | MIC INPUT | high |
| P1-2 | MIC IN SHIELD | shield | MIC INPUT shield | high |
| P1-3 | RS1 BUS | bus | RS1 | high |
| P1-4 | FB2 BUS | bus | FB2 | high |
| P1-5 | FB1 BUS | bus | FB1 | high |
| P1-6 | AUX4 BUS | bus | AUX4 | high |
| P1-7 | AUX3 BUS | bus | AUX3 | high |
| P1-8 | AUX2 BUS | bus | AUX2 | high |
| P1-9 | AUX1 BUS | bus | AUX1 | high |
| P1-10 | PFL BUS | bus | PFL | high |
| P1-11 | N/C | nc |  | high |
| P1-12 | SOLO BUS | bus | SOLO | high |
| P1-13 | N/C | nc |  | high |
| P1-14 | N/C | nc |  | high |
| P1-15 | N/C | nc |  | high |
| P1-16 | ATT IN SHIELD TIE | shield |  | high |
| P1-17 | LINE IN | in | LINE IN | high |
| P1-18 | ATT OUT SHIELD TIE | shield |  | high |
| P1-19 | BOOSTER IN | in | BOOSTER IN | high |
| P1-20 | CH ON OUT | control_out | CH ON OUT | high |
| P1-21 | CH ON IN | control_in | CH ON IN | high |
| P1-22 | PRE OUT | out | PRE OUT | high |
| P1-A | MIC IN | in | MIC INPUT | high |
| P1-B | N/C | nc |  | high |
| P1-C | RS1 BUS | bus | RS1 | high |
| P1-D | FB2 BUS | bus | FB2 | high |
| P1-E | FB1 BUS | bus | FB1 | high |
| P1-F | AUX4 BUS | bus | AUX4 | high |
| P1-H | AUX3 BUS | bus | AUX3 | high |
| P1-J | AUX2 BUS | bus | AUX2 | high |
| P1-K | AUX1 BUS | bus | AUX1 | high |
| P1-L | PFL BUS | bus | PFL | high |
| P1-M | N/C | nc |  | high |
| P1-N | SOLO BUS | bus | SOLO | high |
| P1-P | N/C | nc |  | high |
| P1-R | N/C | nc |  | high |
| P1-S | N/C | nc |  | high |
| P1-T | ATT IN SHIELD TIE | shield |  | high |
| P1-U | LINE IN | in | LINE IN | high |
| P1-V | ATT OUT SHIELD TIE | shield |  | high |
| P1-W | BOOSTER IN | in | BOOSTER IN | high |
| P1-X | CH ON OUT | control_out | CH ON OUT | high |
| P1-Y | CH ON IN | control_in | CH ON IN | high |
| P1-Z | PRE OUT | out | PRE OUT | high |
| P2-1 | N/C | nc |  | high |
| P2-2 | GND | ground |  | high |
| P2-3 | LEFT OUT | out | LEFT OUT | high |
| P2-4 | IC (INTERNALLY CONNECTED) | other |  | high |
| P2-5 | RIGHT OUT | out | RIGHT OUT | high |
| P2-6 | IC (INTERNALLY CONNECTED) | other |  | high |
| P2-7 | GND | ground |  | high |
| P2-8 | IC (INTERNALLY CONNECTED) | other |  | high |
| P2-9 | N/C | nc |  | high |
| P2-10 | IC (INTERNALLY CONNECTED) | other |  | high |
| P2-11 | IC (INTERNALLY CONNECTED) | other |  | high |
| P2-12 | DIRECT OUT | out | DIRECT | high |
| P2-13 | IC (INTERNALLY CONNECTED) | other |  | high |
| P2-14 | IC (INTERNALLY CONNECTED) | other |  | high |
| P2-15 | IC (INTERNALLY CONNECTED) | other |  | high |
| P2-16 | PFL CONTROL | control_in | PFL CONTROL | high |
| P2-17 | MUTE CONTROL | control_in | MUTE CONTROL | high |
| P2-18 | CONTROL COMMON | ground |  | high |
| P2-19 | -25 V | power |  | high |
| P2-20 | 25 V COMMON | ground |  | high |
| P2-21 | +25 V | power |  | high |
| P2-22 | CHASSIS | ground |  | high |
| P2-A | N/C | nc |  | high |
| P2-B | GND | ground |  | high |
| P2-C | LEFT OUT | out | LEFT OUT | high |
| P2-D | IC (INTERNALLY CONNECTED) | other |  | high |
| P2-E | RIGHT OUT | out | RIGHT OUT | high |
| P2-F | IC (INTERNALLY CONNECTED) | other |  | high |
| P2-H | GND | ground |  | high |
| P2-J | IC (INTERNALLY CONNECTED) | other |  | high |
| P2-K | N/C | nc |  | high |
| P2-L | IC (INTERNALLY CONNECTED) | other |  | high |
| P2-M | IC (INTERNALLY CONNECTED) | other |  | high |
| P2-N | DIRECT OUT | out | DIRECT | high |
| P2-P | IC (INTERNALLY CONNECTED) | other |  | high |
| P2-R | IC (INTERNALLY CONNECTED) | other |  | high |
| P2-S | N/C | nc |  | high |
| P2-T | RS CONTROL | control_in | RS CONTROL | high |
| P2-U | MUTE CONTROL | control_in | MUTE CONTROL | high |
| P2-V | SOLO CONTROL | control_in | SOLO CONTROL | high |
| P2-W | CH ON | control_in | CH ON | high |
| P2-X | 25 V COMMON | ground |  | high |
| P2-Y | +24 V | power |  | high |
| P2-Z | CH ON LAMP | control_out | CH ON LAMP | high |

**Straps:** JMP.Z.W: P2-Z P2-W · JMP.X.18: P2-X P2-18 · JMP.Y.21: P2-Y P2-21 · JMP.3: P2-20 P2-18 · JMP.22.21: P1-22 P1-21 · JMP.Z.Y: P1-Z P1-Y · JMP.20.19: P1-20 P1-19 · JMP.X.W: P1-X P1-W

## KiCad

_KiCad: a schematic (`.kicad_sch`) traced from each electrical drawing, the module symbol (`.kicad_sym`) and its PCB projects. Traced schematics are the line work only: redraw with symbols over them._

- [M460T.kicad_sym](KICAD/M460T.kicad_sym)
- [index.html](KICAD/index.html)

## Software

- [index.html](SOFTWARE/index.html)

---
Archive: Anthony Peter Kuzub · [WBSps.ca](https://WBSps.ca) · [WBSps.Kuzub.com](https://WBSps.Kuzub.com)
