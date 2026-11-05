# Procyon trackpad

This design is a trackpad vik module. For a description of the design, schematics, pcb, and usage, see the git repository below.

Git repository:  
<https://github.com/george-norton/procyon>

## Module certification

| Category                | Classification          | Response           |
| ----------------------- | ----------------------- | ------------------ |
| FPC connector           | Required                | ✅                 |
| Breakout pins           | Recommended             | ❌                 |
| Uses: SPI               | Optional                | ✅                 |
| SPI used for SPI only   | Strongly recommended    | ✅                 |
| Uses: I2C               | Optional                | ✅                 |
| I2C used for I2C only   | Strongly Recommended    | ✅                 |
| I2C pull ups            | Required                | 3.3k               |
| Uses: RGB               | Optional                | ❌                 |
| Uses: Extra GPIO 1      | Optional                | ✅                 |
| Uses: Extra GPIO 2      | Optional                | ✅                 |
| Standard PCB Size/Mount | Strongly recommended    | ❌                 |
