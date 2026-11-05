# GC9A01 round display VIK adapter

## Overview

This is a VIK module made to add a VIK connector to the [GC9A01](https://www.aliexpress.us/item/3256803883388742.html) breakout board.

## Fabrication and BOM

For PCB fabrication, you can use the files in the production folder.

- gerbers.zip - the file used to fabricate the pcb
- bom.csv - used for PCBA. You can also use the part numbers in this file to look up the exact parts as [lcsc.com](https://lcsc.com)
- positions.csv - used for PCBA

Using the 3 files above, this has been tested at [jlcpcb.com](https://jlcpcb.com)

## VIK module certification

| Category                | Classification          | Response           |
| ----------------------- | ----------------------- | ------------------ |
| FPC connector           | Required                | ✅                 |
| Breakout pins           | Recommended             | ❌                 |
| Uses: SPI               | Optional                | ✅                 |
| SPI used for SPI only   | Strongly recommended    | ✅                 |
| Uses: I2C               | Optional                | ❌                 |
| I2C used for I2C only   | Strongly Recommended    | ❌                 |
| I2C pull ups            | Required                | N/A                |
| Uses: RGB               | Optional                | ❌                 |
| Uses: Extra GPIO 1      | Optional                | ✅                 |
| Uses: Extra GPIO 2      | Optional                | ✅                 |
| Standard PCB Size/Mount | Strongly recommended    | ❌                 |

## PCB images

![pcb front](images/gc9a01-module-front.png)

![pcb back](images/gc9a01-module-back.png)
