# Solanum

![](photos/solanum.jpg)

Solanum is a 34-key diodeless split keyboard based around Pro Micro compatible MCU modules. It features support for both wired and wireless builds and has been designed to be easily hand-assembled. The PCB is reversible and hotswap with support for Kailh Choc (v1) switches. 

## Features

The layout of Solanum differs from the typical 34-key split in that it has only one thumb key, and a reachy pinky key. Nominal key spacing is 19x18mm. All columns features a slight splay; the pinky columns are splayed more aggressively.

The top face of the switchplate (i.e., the face which is visible on the left hand side of the keyboard) features a botanical illustration of *Solanum melongena*, the eggplant.

![](renders/image-4.png)

Solanum includes support for a splitkb.com tenting puck

![](renders/image-3.png)

It features a TRRS port for wired builds, and
a dedicated battery JST and power switch for wireless builds.

![](renders/image.png)

## BOM

- 2x PCB
- 2x switchplate
- 2x Pro Micro compatible MCU module
- 34x Kailh Choc hotswap sockets
- 34x Kailh Choc switches
- 34x 1u Choc keycaps
- 12x nylon M2 screws
- 12x nylon 1mm M2 washers
- 12x nylon M2 nuts

For wired build:
- 2x PJ-320A TRRS jack
- 1x TRRS cable

For wireless build:
- 2x JST S2B-PH-K-S
- 2x C&K OS102011MA1QN1

Optional:
- 2x splitkb tenting pucks
- 2x 3D printed MCU cover (from [extras/](extras/))
- 4x 6mm M2 standoffs

## Build guide

[https://docs.eggs.works/docs/build-guides/solanum/](https://docs.eggs.works/docs/build-guides/solanum/)

## Firmware

ZMK: https://github.com/eggsworks/zmk-config/

QMK: https://github.com/eggsworks/qmk_firmware/tree/solanum/keyboards/eggsworks/solanum

## License

Solanum is provided under the terms of the [GPL v3](LICENSE). The following portions are derived from other projects:

- Choc, Pro Micro, TRRS, and jumpers used on the JST footprint: [keyboard_reversible.pretty](https://github.com/50an6xy06r6n/keyboard_reversible.pretty) by 50an6xy06r6n (MIT License)
- Tenting puck: [tenting_puck](https://github.com/splitkb/tenting_puck) by splitkb.com (MIT License)
- JST, SPDT, and mounting holes: [KiCad footprint library](https://kicad.github.io/footprints/) (CC BY-SA 4.0)
