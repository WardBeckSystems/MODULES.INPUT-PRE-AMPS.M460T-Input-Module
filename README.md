# M460T · Input Pre Amps

Ward-Beck Systems M460T, 1974|7. Wiki page: [M460T on WBSps.ca](https://wardbecksystems.github.io/WBSps.ca/PAGES/M460T.html)

| Folder | What is in it | Files |
|---|---|---|
| [SCHEMATICS/](SCHEMATICS/) | electrical drawings: schematics, functional diagrams, component layouts, wiring | 0 |
| [MECHANICAL/](MECHANICAL/) | front panels, cover plates, metalwork, assemblies; the front panel as vectors | 0 |
| [PINOUTS/](PINOUTS/) | the RTO-144 connector: connection sheets, connector layouts, rear views | 21 |
| [MANUALS/](MANUALS/) | manuals, manual pages, price lists, brochures, documents | 0 |
| [PHOTOS/](PHOTOS/) | photographs of the module | 0 |
| [SOFTWARE/](SOFTWARE/) | program listings, firmware, the plugin | 0 |
| [KICAD/](KICAD/) | KiCad schematics traced from the drawings, the symbol, PCB projects | 1 |
| [OCR/](OCR/) | the note of every file: date, origin, title block, OCR text | 4 |

## Pinouts

_Pinouts: the RTO-144 edge connector (connection sheets, connector layouts and rear views, strapping), and the pinout / connections drawings made from them. The module root `RTO.json` lists every contact._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKVUJBZTFCM2dRVmM/view?resourcekey=0-KZIVjb4U-apVDjdW8rMS1g" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKVUJBZTFCM2dRVmM&resourcekey=0-KZIVjb4U-apVDjdW8rMS1g" width="240" alt="1974 - M460T - Input Module - Pin Outs (2).pdf"></a><br><sub>1974|7 · Input Module - Pin Outs (2)</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKYmwycDFYTXhZcFk/view?resourcekey=0-zPIpHa2MFlQpzTytcldYUA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKYmwycDFYTXhZcFk&resourcekey=0-zPIpHa2MFlQpzTytcldYUA" width="240" alt="1974 - M460T - Input Module - Pin Outs.pdf"></a><br><sub>1974|7 · Input Module - Pin Outs</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKNF9BMWJ2cWlPRkE/view?resourcekey=0-V6NqBYHiIqJaMPMnBO4wig" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKNF9BMWJ2cWlPRkE&resourcekey=0-V6NqBYHiIqJaMPMnBO4wig" width="240" alt="1974 - M460T - Pin Out P1.jpg"></a><br><sub>1974|7 · Pin Out P1</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKU2ZvUEZpNG5nY1U/view?resourcekey=0-7QxYYW2v6AWZ2-hoid2Lhw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKU2ZvUEZpNG5nY1U&resourcekey=0-7QxYYW2v6AWZ2-hoid2Lhw" width="240" alt="1974 - M460T - Pin Out P2.jpg"></a><br><sub>1974|7 · Pin Out P2</sub></td></tr>
</table>

Not on Google Drive yet: `M460T - RTO-144 Connections.pdf`

## RTO-144 pinout

22 contacts (P1), 22 contacts (P2). Every contact, with where it was read: [`RTO.json`](RTO.json).

| Pin | Signal | Kind | Pair | Confidence |
|---|---|---|---|---|
| 1 | MIC IN | in | A1 + | high |
| 5 | BUS RIGHT OUT | out | A3 + | high |
| 12 | DIRECT OUT | out | A4 + | high |
| 17 | LINE IN | in | A2 + | high |
| 18 | COMMON | ground |  | high |
| 19 | FADER RETURN | in | B4 + | high |
| 19 | -25 V | power |  | high |
| 20 | CH ON SWITCH OUT | control | B3 + | high |
| 20 | COMMON | ground |  | high |
| 21 | INSERT RETURN | in | B2 + | high |
| 21 | +25 V | power |  | high |
| 22 | INSERT OUT | out | B1 + | high |
| 22 | CHASSIS | ground |  | high |
| A | MIC IN | in | A1 - | high |
| E | BUS RIGHT OUT | out | A3 - | high |
| N | DIRECT OUT | out | A4 - | high |
| U | LINE IN | in | A2 - | high |
| W | FADER RETURN | in | B4 - | high |
| X | CH ON SWITCH OUT | control | B3 - | high |
| Y | INSERT RETURN | in | B2 - | high |
| Y | +24 V | power |  | high |
| Z | INSERT OUT | out | B1 - | high |

**Straps:** CH ON LAMP: JMP.Z.W · CH ON GND : JMP.X.18 · 24V Jumper: JMP.Y.21 · CH ON GND : JMP.3 · Insert +: JMP.22.21 · Insert -: JMP.Z.Y · Fader +: JMP.20.19 · Fader - : JMP.X.W

## KiCad

_KiCad: a schematic (`.kicad_sch`) traced from each electrical drawing, the module symbol (`.kicad_sym`) and its PCB projects. Traced schematics are the line work only: redraw with symbols over them._

- [M460T.kicad_sym](KICAD/M460T.kicad_sym)

---
Archive: Anthony Peter Kuzub · [WBSps.ca](https://WBSps.ca) · [WBSps.Kuzub.com](https://WBSps.Kuzub.com)
