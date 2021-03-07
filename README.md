## Xenform_Kicad
#### Some Custom Kicad Symbols and Footprints
#### by Scott Kildall



### Overview
I have several custom symbols and footprints for parts and circuits, that I've created with Kicad 5.0

### Todo
Move resistor footprint over
Resolve Wemos Lolin D32 Pro symbol + check footprint

### Parts

(1) TRS Jack:

This is a common TRS jack (stereo audio). I'm not using the inner 2 pins, which are connected to ground, except for mounting. The middle pin is also GND, so this is redundant.

https://www.newark.com/cliff-electronic-components/fc68133/stereo-jack-3-5mm-5pos-pcb/dp/75Y0813
![](images/trs_jack.jpg)

(2) Adafruit Metro Mini

(3) 4051_MUX
CD4051B Through-hole chip. Since I added a custom footprint for this, I also added the symbol to my .lib file.

Pin #1 = Ch 4
Pin #2 = Ch 6
Pin #3 = IO (X)
Pin #4 = Ch 7
Pin #5 = Ch 5
Pin #6 = InH (GND)
Pin #7 = VEE (GND)
Pin #8 = VSS (GND)
Pin #9 = S3 (C)
Pin #10 = S2 (B)
Pin #11 = S1 (A)
Pin #12 = Ch 3
Pin #13 = Ch 1
Pin #14 = Ch 0
Pin #15 = Ch 2
Pin #16 = VDD (V+)

(4) B6B-XH JST header
This one seems to be missing from some other symbol libraries and footprints, so I amalgamated my own.

there are two footprints associated here, I use the -AM version for my work.

JST_XH_B6B-XH-AM
JST_XH_B6B-XH-A

(5) PJ-320D

This is a TRRS jack that is, by default, a surface-mount option, I have created a thru-hole version and also mvoed the SMT version to my collection.

(6)
Potentiometer_Bourns_PTV09A

Footprint-only, this is exactly the footprint for my 10K pots.

### Custom Symbols
I have several custom symbols and footprints for these projects, located here


### Custom Footprints
Located in the Xenoform_Kicad.pretty folder
(1) 3.5mm_TRS_jack.kicad_mod
(2) Adafruit_MetroMini.kicad_mod
(3) 4051_MUX

(4) JST_XH_B6B-XH
JST_XH_B6B-XH-AM
JST_XH_B6B-XH-A

(5) PJ320D
Jack_3.5mm_PJ320D_Horizontal.kicad_mod: surface-mount footprint for PJ320D

Jack_3.5mm_PJ320D_ThruHole.kicad_mod: through hole footprint for PJ320D

(6)
Potentiometer_Bourns_PTV09A-1_Single_Vertical

(7) Lolin_D32_Board
Footprint for ESP32 Lolin D32 Pro

(8) MAX98357_Breakout
Footprint for MAX98357 breakout

(9) Resistor_TRT.kicad_mod
Footprint for 1/4 watt resistor, very simple

(10) LolinD32.kicad_mod
Simple footprint for LolinD32
