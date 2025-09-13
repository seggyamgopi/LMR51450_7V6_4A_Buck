# LMR51450 7.6V / 4A Buck Converter

This project is a DC-DC Buck Converter design based on **Texas Instruments LMR51450**.
It is designed in **KiCad** with the following specifications:

- Input Voltage: 10–35 V
- Output Voltage: 7.6 V
- Maximum Output Current: 4 A
- Features: Input/output filtering, enable control, feedback network

---

## Repository Contents
- `KiCad/` → KiCad project files (.sch, .kicad_pcb, etc.)
- `Gerbers/` → Fabrication files (ready for PCB manufacturing)
- `BOM/` → Bill of Materials (`bom.csv`)
- `Media/` → Snapshots of schematic and PCB routing
- `README.md` → Project description (this file)

---

## Snapshots
**Schematic**  
![Schematic](Media/schematic.png)

**PCB Layout**  
![PCB Routing](Media/pcb_routing.png)

---

## Notes
- Design follows PCB routing guidelines for handling up to 4 A.
- Ensure inductor and capacitors are chosen with correct ratings.
- Replace placeholders with actual part numbers in BOM before ordering.

---

## License
This project is open-source under the MIT License.
