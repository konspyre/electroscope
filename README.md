# Toy Electroscope

This is an Electroscope done up using a design from Alan "vk2zay" Yates in his [Making Electrets](http://www.youtube.com/watch?v=1DR-tTU8uIM) video.

![Toy Electroscope](http://open.konspyre.org/assets/images/electroscope/top-old-ver-kapton.png)

(Older version using 0603 LEDs and square pads on the left, current version is on the right)

### [Boring blog post](http://open.konspyre.org/blog/2014/05/30/electroscope/)

### [Fabrication (OSHPark shared project)](https://www.oshpark.com/shared_projects/KFA2jmSs)

### Bill of Materials

This BOM specifies the amount needed for _one_ board.

| Quantity | Description | Digikey Part Number | Board Placement |
| -------- | ----------- | ----------- | --------------- |
| 3        | 2N3906      | [MMBT3906FSCT-ND](http://www.digikey.com/product-detail/en/MMBT3906/MMBT3906FSCT-ND/458972) | Right (label: 2N3906) |
| 3 	   | 2N3904	 | [MMBT3904FSCT-ND](http://www.digikey.com/product-detail/en/MMBT3904/MMBT3904FSCT-ND/458971) | Left (label: 2N3904) |
| 2        | 100 ohm resistor (0603 imperial) | [1276-5038-1-ND](http://www.digikey.com/product-detail/en/RC1608J101CS/1276-5038-1-ND/) | Bottom (label: 100 ohm) |
| 2        | 100k ohm resistor (0603 imperial) | [1276-5110-1-ND](http://www.digikey.com/product-detail/en/RC1608J104CS/1276-5110-1-ND) | Middle (label: 100k ohm) |
| 2	   | 1M ohm resistor (0603 imperial) | [311-1.00MHRCT-ND](http://www.digikey.com/product-detail/en/RC0603FR-071ML/311-1.00MHRCT-ND/) | Top (label: 1M ohm) |
| 1        | 9v female PCB mount snap | [BSPCF](http://www.digikey.com/product-search/en?vendor=0&keywords=BSPCF) | 9V+ terminal (verify before soldering by attaching to a 9V battery -- reworking afterwards is difficult without specialized tools/materials) |
| 1        | 9v male PCB mount snap | [BSPCM](http://www.digikey.com/product-search/en?vendor=0&keywords=BSPCM) |  9v- terminal |

#### LEDs

_Pick either the 3mm LEDs or surface mount 0805s -- the 3mm LEDs are recommended_

| Quantity | Description | Digikey Part Number | Board Placement |
| -------- | ----------- | ----------- | --------------- |
| 2        | 3mm LEDs | (Red: [160-1704-ND](http://www.digikey.com/product-search/en?vendor=0&keywords=160-1704-ND) / Green: [160-1958-ND](http://www.digikey.com/product-search/en?vendor=0&keywords=160-1958-ND) | Bottom (verify orientation before soldering!) |
| 2        | 0805 imperial LEDs | (Orange: [350-2040-1-ND](http://www.digikey.com/product-search/en?vendor=0&keywords=350-2040-1-ND) / Yellow: [350-2041-1-ND](http://www.digikey.com/product-search/en?vendor=0&keywords=350-2041-1-ND) | Bottom (verify orientation as with the 3mm LEDs) |

#### Antenna

There is no part for this, so you'll have to make your own. A simple loop soldered together usually
works well (the twisted termination used in the photos is just a fancy flourish).

### License

[Creative Commons Attribution/Share-Alike](http://creativecommons.org/licenses/by-sa/4.0/)

Original design/schematic by [Alan "vk2zay" Yates](http://twitter.com/vk2zay)


