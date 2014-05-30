# Toy Electroscope

[!Toy Electroscope](http://open.konspyre.org/assets/images/electroscope/top1.png)

### Fabrication (OSHPark shared project)

[Click here](https://www.oshpark.com/shared_projects/KFA2jmSs)

### Bill of Materials

This BOM specifies the amount needed for _one_ board.

| Quantity | Description | Part Number | Board Placement |
| -------- | ----------- | ----------- | --------------- |
| 3        | 2N3906      | MMBT3906FSCT-ND | Right (label: 2N3906) |
| 3 	   | 2N3904	 | MMBT3904FSCT-ND | Left (label: 2N3904) |
| 2        | 100 ohm resistor (0603 imperial) | 1276-5038-1-ND | Bottom (label: 100 ohm) |
| 2        | 100k ohm resistor (0603 imperial) | 1276-5110-1-ND | Middle (label: 100k ohm) |
| 2	   | 1M ohm resistor (0603 imperial) | 311-1.00MHRCT-ND | Top (label: 1M ohm) |
| 1        | 9v female PCB mount snap | BSPCF | 9V+ terminal (verify before soldering by attaching to a 9V battery -- reworking afterwards is difficult without specialized tools/materials) |
| 1        | 9v male PCB mount snap | BSPCM |  9v- terminal |

#### LEDs

_Pick either the 3mm LEDs or surface mount 0805s -- the 3mm LEDs are recommended_

| Quantity | Description | Part Number | Board Placement |
| -------- | ----------- | ----------- | --------------- |
| 2        | 3mm LEDs | (Red: 160-1704-ND / Green: 160-1958-ND) | Bottom (verify orientation before soldering!) |
| 2        | 0805 imperial LEDs | (Orange: 350-2040-1-ND / Yellow: 350-2041-1-ND) | Bottom (verify orientation as with the 3mm LEDs) |


#### Antenna

There is no part for this, so you'll have to make your own. A simple loop soldered together usually
works well (the twisted termination used in the photos is just a fancy flourish).
