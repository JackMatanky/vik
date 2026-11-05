# Peacock trackpad

This design includes both a controller pcb and a vik module, integrated into one. So, there will be certifications on both.

Git repository:  
<https://github.com/george-norton/peacock>

Schematics and pcb image available in the github repo

## Controller pcb certification

| Category                 | Classification          | Response           |
| -----------------------  | ----------------------- | ------------------ |
| FPC connector            | Required                | ✅                 |
| Breakout pins            | Recommended             | ✅                 |
| Supplies: SPI            | Required                | ✅                 |
| Supplies: I2C            | Required                | ✅                 |
| I2C on main PCB          | Discouraged             | ❌                 |
| I2C pull ups             | Informative             | N/A                |
| Supplies: RGB            | Required                | ✅                 |
| Supplies: Extra GPIO 1   | Required                | Analog/Digital     |
| Supplies: Extra GPIO 2   | Required                | Analog/Digital     |

## Module pcb certification

| Category                | Classification          | Response           |
| ----------------------- | ----------------------- | ------------------ |
| FPC connector           | Required                | ✅                 |
| Breakout pins           | Recommended             | ✅                 |
| Uses: SPI               | Optional                | ❌                 |
| SPI used for SPI only   | Strongly recommended    | N/A                |
| Uses: I2C               | Optional                | ✅                 |
| I2C used for I2C only   | Strongly Recommended    | ✅                 |
| I2C pull ups            | Required                | 3.3k               |
| Uses: RGB               | Optional                | ❌                 |
| Uses: Extra GPIO 1      | Optional                | ✅                 |
| Uses: Extra GPIO 2      | Optional                | ❌                 |
| Standard PCB Size/Mount | Strongly recommended    | ❌                 |
