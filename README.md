# TWRP device tree for Xperia 1V

Xperia 1V (codenamed _"pdx234"_) is a high-end smartphone from Sony.

It was announced & released on May 2023.

## Device specifications

Basic   | Spec Sheet
-------:|:-------------------------
SoC     | Snapdragon® 8 Gen 2 (SM8550)
CPU     | 1x3.2 GHz Cortex-X3 & 2x2.8 GHz Cortex-A715 & 2x2.8 GHz Cortex-A710 & 3x2.0 GHz Cortex-A510
GPU     | Adreno 740
Memory  | 12/16 GB RAM
Shipped Android Version | 13.0
Storage | 256/512 GB
Battery | Li-Ion 5000 mAh, non-removable, graphene-enhanced
Display | 1644 x 3840 pixels, 21:9 ratio (~642 ppi density), 6.50 inches, OLED, 120Hz, Dolby Vision, HDR10+

## Device picture

![Xperia 1V](https://sony.scene7.com/is/image/sonyglobalsolutions/00_02_Large_static_D?$largeImage$&fmt=png-alpha)

## Features

Works:

- [X] ADB
- [X] Decryption
- [X] Display
- [X] Fasbootd
- [X] Flashing
- [X] MTP
- [X] Sideload
- [X] USB OTG
- [X] Vibrator

## To use it:

```
fastboot flash recovery recovery.img
```
