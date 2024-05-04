# Hardware

| [Readme](../README.md) | [Using the Badge](BADGE.md) | [Playing the Game](GAME.md) | [Software Development](DEVELOP.md) | [Badge Hardware](HARDWARE.md) |
| ---------------------- | --------------------------- | --------------------------- | ---------------------------------- | ----------------------------- |

`/hardware/` contains the kicad board design files and full details about
design and manufacturing. The hardware on the badge includes:

-  Raspberry Pi 2040, derived from the seeed xiao 2040
-  16MB spi flash for code and files
-  128x64 OLED display with SH1106 controller over I2C
-  IRDA PHY used directly on UART.
-  5-way d-pad for input
-  2 neopixel LEDs
-  AA battery plus boost voltage converter
-  USB-C connector plus vreg for usb power
-  power switch to switch between USB and Battery power
-  test points for reset, boot, and swd
