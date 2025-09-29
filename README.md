# KOMETA aka MOKETA

![All](image/gallery/preview.png)

KOMETA is a split keyboard built around Choc switches, designed for wireless operation with Pro Micro–sized microcontrollers. Its key feature is a mid-mount, hot-swappablecontroller design. To enable this, the PCB includes a USB-C port cutout, ensuring compatibility with popular wireless boards like: nice!nano or SuperMini

[Build Guide](https://github.com/inpudiy/KOMETA/blob/main/doc/buildguide.md) - [ZMK Firmware](https://github.com/inpudiy/kometa-zmk/releases)


## Features

- Pro Micro-format microcontroller, compatible with mid-mount hot-swap installation
- Optimized for wireless: hardware power switch, reset button, battery solder pads, no LEDs, and ZMK firmware
- Choc V1/V2 switches with MX spacing (19 × 19 mm)
- 42-key layout with column stagger, inspired by the Jian keyboard
- 3D-printed case

## PCB Image

![Bottom](image/pcb/bottom.svg)
![Top](image/pcb/top.svg)


## BOM (Bill of Materials)

| Component                                                    | Qty |
| ------------------------------------------------------------ | --- |
| Pro Micro board: Super Mini nRF52840 / nice!nano             | 2   |
| MSK12C02 Slide Switch                                        | 2   |
| 301230 battery                                               | 2   |
| TS342A2P                                                     | 2   |
| Silicone bumpers (6x2 mm)                                    | 8   |
| Machine Pin Header Female                                    | 48  |
| PG1350 hot-swap socket                                       | 42  |
| Diode 1N4148WS (SOD-323)                                     | 42  |
| CHOC V1/2 switches                                           | 42  |
| M2 Hexagon Nut                                               | 12  |
| M2 Thin Flat Head Screw 8mm                                  | 12  |
