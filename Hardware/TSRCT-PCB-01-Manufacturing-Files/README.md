# TSRCT-PCB-01 manufacturing files

Files for PCB fabrication and assembly (PCBA) of TSRCT-PCB-01.

| Item | Contents |
|---|---|
| `Gerber_Drill.zip` | Gerber and drill files, common to all variants (KiCad 10.0.6, 2 layers, 1.6 mm, 90 x 80 mm) |
| `Pt100-Manufacture-Files/` | BOM and position (centroid) file, both channels populated for Pt100 |
| `Pt1000-Manufacture-Files/` | BOM and position (centroid) file, both channels populated for Pt1000 |
| `Pt100-Pt1000-Hybrid-Manufacture-Files/` | BOM and position (centroid) file, channel 1 Pt100, channel 2 Pt1000 |

The three variants use the same PCB and the same component positions. Only four parts differ:

| Variant | Rref-1 | Rref-2 | C-CH1 | C-CH2 |
|---|---|---|---|---|
| Pt100 | 430 ohm 0.1 % (ERA-6AEB431V) | 430 ohm 0.1 % (ERA-6AEB431V) | 100 nF (CL21B104KBCNNNC) | 100 nF (CL21B104KBCNNNC) |
| Pt1000 | 4.3 kohm 0.1 % (ERA-6AEB432V) | 4.3 kohm 0.1 % (ERA-6AEB432V) | 10 nF (CL21B103KBANNNC) | 10 nF (CL21B103KBANNNC) |
| Hybrid | 430 ohm 0.1 % (ERA-6AEB431V) | 4.3 kohm 0.1 % (ERA-6AEB432V) | 100 nF (CL21B104KBCNNNC) | 10 nF (CL21B103KBANNNC) |

Each BOM lists 42 placements, and its Ref, Val and Package columns match the position file in the same folder.
The RTD wire-configuration solder jumpers and the test points are not BOM parts; the jumpers are set by hand after assembly.
