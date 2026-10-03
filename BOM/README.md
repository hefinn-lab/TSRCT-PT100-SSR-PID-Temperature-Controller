# Reference BOM

`BOM.xlsx` is the reference bill of materials for TSRCT-PCB-01. It is intended for manual ordering and assembly: it lists Digi-Key part numbers and can be uploaded to Digi-Key's BOM tool. Quantities are for one board. The red rows are the sensor-dependent parts; order the reference resistors and channel capacitors that match each channel's sensor type (Pt100 or Pt1000).

For automated assembly (PCBA), use the files in [`Hardware/TSRCT-PCB-01-Manufacturing-Files`](../Hardware/TSRCT-PCB-01-Manufacturing-Files/) instead. That folder holds a separate BOM and position file for each population (Pt100, Pt1000, and Pt100/Pt1000), formatted for assembler upload, together with the Gerber and drill files.

Both use the same reference designators as the schematic and PCB.
