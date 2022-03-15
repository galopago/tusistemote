# PROTOTYPE BOARD FOR MCU MODULES AND FITS INSIDE 83x58mm WATERPROOF HOUSING

This board can host MCU modules up to 20 pin per row in a double row configuration. The minimum separation between rows is 2.54 mm and the maximum separation between rows is 27.94 mm, so most common types of MCU modules are supported. The board is designed to fit inside a generic 83x58mm waterproof enclosure. 

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

## DIP IC

Dual in-line package chip placed with 7.62 mm separation between pin rows

![BACK](assets/img/dil.jpg)

## SMALL MODULE

An example showing an Arduino nano with 15.24 mm separation between header rows

![BACK](assets/img/small.jpg)

## BIG MODULE

An example showing a NODE MCU V3 with 27.94 mm separation between header rows.

![FRONT](assets/img/big.jpg)

## ADDITIONAL SPACE

Female headers used for easy reuse of the module, gives additional space for small components or modules.

![MODULE](assets/img/space.jpg)

Panelized PCB version 

![PANEL](assets/img/panel.jpg)

