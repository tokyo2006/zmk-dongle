# ZMK Dongle

[Chinese](README.md)
[English](README_en.md)

> A dongle made using the Micro nrf52840 by睫毛哥, I only bought it from Taobao but I asked for a link to the Aliexpress page. you can reference
> Aliexpress: [Micro nrf52840](https://vi.aliexpress.com/item/1005007859027151.html?gatewayAdapt=glo2vnm)

This dongle requires manually flashing the bootloader. The bootloader file is located in the "bootloader" folder. Files in the "PCB" folder can be opened using嘉立创EDA software. Files in the "case" folder are for the housing and can be printed if desired.

## single dongle

This dongle does not have a display. Use it according to your needs.

| Component | Value | Quantity | Package |
|-----------|-------|----------|---------|
| Blue LED  | -     | 1        | 0805    |
| Resistor  | 1.5k  | 1        | 1206    |
| Capacitor | 100nf | 2        | 1206    |
| Reset Button | BX-TS-26-4417TT | 1 | SW-SMD_4P-L5.2-W5.2-P3.70-LS6.5 |
| USB       | USB-A | 1        | USB-A-SMD_U217-041N-4BV81 |
| Main Controller | - | 1 | Micro 52840 by 睫毛哥 |

Case:

- [dongle_down.stl](case/dongle_down.stl)
- [dongle_top.stl](case/dongle_top.stl)

![dongle](image/dongle.png)

## Nice!view dongle

This dongle is exposed nice!view pins, can be welded directly nice!view, can also weld trackballs and other spi communication peripherals.

| Component | Value | Quantity | Package |
|-----------|-------|----------|---------|
| Blue LED  | -     | 1        | 0805    |
| Resistor  | 1.5k  | 1        | 1206    |
| Capacitor | 100nf | 2        | 1206    |
| Reset Button | BX-TS-26-4417TT | 1 | SW-SMD_4P-L5.2-W5.2-P3.70-LS6.5 |
| USB       | USB-A | 1        | USB-A-SMD_U217-041N-4BV81 |
| Main Controller | - | 1 | Micro 52840 by 睫毛哥 |
| nice!view | - | 1 | nice!view |

Case:

- [nice_view_dongle.stl](case/nice_view_dongle.stl)

![nice_view_dongle](image/nice_view_dongle.png)]
