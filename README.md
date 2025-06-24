Inpudiy telegram: https://t.me/inpudiy

# KOMETA aka MOKETA

KOMETA is a split keyboard built around Choc v2 switches, designed for wireless operation with Pro Micro–sized microcontrollers. Its key feature is a mid-mount, hot-swappable controller design. To enable this, the PCB includes a USB-C port cutout, ensuring compatibility with popular wireless boards like: nice!nano or SuperMini

[Build Guide](https://github.com/inpudiy/KOMETA/blob/main/doc/buildguide.md) - [ZMK Firmware](https://github.com/inpudiy/kometa-zmk-config/releases/tag/release)

## Features

- Pro Micro-format microcontroller, compatible with mid-mount hot-swap installation
- Optimized for wireless: hardware power switch, reset button, battery solder pads, no LEDs, and ZMK firmware
- Choc V2 switches with MX spacing (19 × 19 mm)
- 42-key layout with column stagger, inspired by the Jian keyboard 
- 3D-printed case

## PCB Image

![Bottom](https://raw.githubusercontent.com/inpudiy/KOMETA/refs/heads/main/image/pcb/bottom.png)
![Top](https://raw.githubusercontent.com/inpudiy/KOMETA/refs/heads/main/image/pcb/top.png)


## BOM (Bill of Materials)

| Component                                                    | Qty |
| ------------------------------------------------------------ | --- |
| Microcontroller: nRFMicro / Super Mini nRF52840 / nice!nano  | 2   |
| Power switch: MSK-12C02                                      | 2   |
| 301230 battery                                               | 2   |
| Turtle Switch SMD 2-pin (3 × 4 × 2 mm)                       | 2   |
| Silicone bumpers (6 × 2 mm)                                  | 4   |
| Pin Header Female Pin (2.54mm) (or MilMax)                   | 26  | 
| PG1350 hot-swap socket                                       | 42  |
| Diode 1N4148W (SOD-323)                                      | 42  |
| CHOC V2 switches                                             | 42  |
