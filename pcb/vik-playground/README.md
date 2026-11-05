# VIK playground

## Overview

This is a VIK module designed to allow you to experiment and prototype.  

It includes:  

- MCP23017 I/O expander
- 74hc595 shift register
- WS2812B 5050 leds
- MX/Choc V1/Gateron low profile switch footprint, both hotswap and solderable
- Row/Column and Direct Pin switch configuration (default is Row/Column)
- EC11 footprint

All pins are broken out. If you have female headers connected, you can experiment with your wiring, write firmware, and prototype / test features.  

Big thank you to GeorgeN for the suggestion for this module  
Thanks to [petejohanson](https://github.com/petejohanson/) for providing additional tips along the way  

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
| Breakout pins           | Recommended             | ✅                 |
| Uses: SPI               | Optional                | ✅                 |
| SPI used for SPI only   | Strongly recommended    | ✅                 |
| Uses: I2C               | Optional                | ✅                 |
| I2C used for I2C only   | Strongly Recommended    | ✅                 |
| I2C pull ups            | Required                | ✅                 |
| Uses: RGB               | Optional                | ✅                 |
| Uses: Extra GPIO 1      | Optional                | ✅                 |
| Uses: Extra GPIO 2      | Optional                | ✅                 |
| Standard PCB Size/Mount | Strongly recommended    | ❌                 |

## PCB images

![pcb front](images/vik-playground-front.png)

![pcb back](images/vik-playground-back.png)
