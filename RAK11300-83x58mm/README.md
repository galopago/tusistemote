# RAK11300 BREAKOUT BOARD THAT FITS INSIDE 83x58mm WATERPROOF HOUSING

[RAK11300](assets/pdf/RAK11300.pdf) is a LoRa module in a "stamp" factor plus an RP2040 chip. The board is designed to fit inside a generic 83x58mm waterproof enclosure. 

![PCBANDENCLOSURE](assets/img/pcbandenclosure.jpg)

## How to use this repository

The PCB was developed in KiCad V5.1,

## Directory structure

* The root folder contains template KiCad files: project, schematic and PCB 
* /library folder contains additional symbols needed to edit printed schematic
* /modules folder contains additional footprints needed to edit printed circuit board
* /gerber folder contains ready to manufacture files.
* /assets folder contains support files for reade.md

## PCB layout

![LAYOUT](assets/img/pinout.svg)

## Back

The stamp style module is placed on the back of the card.

![BACK](assets/img/back.jpg)

## Front

All of the pins of the module are routed to pcb pads, also, space for 2 AA size battery holder. There are also some traces for breadboarding

![FRONT](assets/img/front.jpg)

Module soldered on the back

![MODULE](assets/img/module.jpg)

Female headers used for debugging or adding a "hat" card with additional electronics.

![MODULE](assets/img/space.jpg)

Panelized PCB version 

![PANEL](assets/img/panel.jpg)

