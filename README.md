# kb-daughterboard

![](https://github.com/melonbred/kb-daughterboard/blob/main/images/kb-db.png?raw=true)

## Introduction

This project is a USB-C daughterboard that provides with ESD protection and a standard 4-pin JST connector. Dimensions are approximately 42 x 11mm and has two M2 screw mounts. This daughterboard was heavily influenced by the [C3 Unified Daughterboard](https://github.com/ai03-2725/Unified-Daughterboard) project. While the C3 Unified Daughterboard is a great product, this daughterboard offers a different footprint and vertical JST connector.

## Features
Similarly to the Unified Daugherboard, this daughterboard features the following:
- Overcurrent protection through a PTC fuse
- Overvoltage protection through a TVS diode
- Single-path USB-C shield grounding to a metal chasis. ESD is disappited through a resistor and diode.

Please note that this daughterboard does not include resistors for the USB data lines which may be required for some microprocessors. If these resistors are required for your application, please provide them on the PCB mainboard.

There are also two versions of this daughterboard. One with the USB-C receptacle flush to the PCB; The other with the USB-C receptacle protruded out. Please see the .step files for reference.

## Production
Please note that the produection files were prepared with JLCPCB's SMT assembly in mind. Should you deicide to proceed with a different manufacturer, the Bill of Materials (BOM) and position files may need to be modified.



## Acknowledgment

This project was collaboration with [matthewdias](https://github.com/matthewdias).

As mentioned above, this project was heavily influenced by the [C3 Unified Daughterboard](https://github.com/ai03-2725/Unified-Daughterboard). 
