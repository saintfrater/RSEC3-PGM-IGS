# RSEC3-PGM-IGS
re-do of custom/hybrid component from PGM-IGS 

On an PGM-IGS board, there are some "custom" hybrid IC's called RSEC3.

Those ICs are somehow fragile and are not available on the market.

gc8tech has reverse engineer the IC's schematics and kindly share it with the community.

## Schematics
![Equivalent Schematics](https://raw.githubusercontent.com/saintfrater/RSEC3-PGM-IGS/main/img/schematics.png)

Since no PCB has been draw for this, here is my attempt to fill this gape.

## Version 1
![PCB Version 1](https://raw.githubusercontent.com/saintfrater/RSEC3-PGM-IGS/main/img/PCB-V1.png)

## Version 2
![PCB Version 2](https://raw.githubusercontent.com/saintfrater/RSEC3-PGM-IGS/main/img/PCB-V2.png)

## BOM
| Reference | Value | Footprint | Q |
| --------- | ----- | --------- | - |
| R1-R4  | 100R | Resistor_SMD R_0603_1608Metric | 4 |
| R5-R8  | 10K  | Resistor_SMD R_0603_1608Metric | 4 |
| RSEC1  |      | 2.54mm pitch Angle Row Header Connector | 1 |
