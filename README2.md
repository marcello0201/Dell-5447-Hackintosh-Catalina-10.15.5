## Dell Inspiron 5447

![Screenshot](https://github.com/marcello0201/Dell-5447-Hackintosh-Catalina-10.15.5/blob/master/Bios%20setings/MacOS.png)

- Bios version: A12
- Processor: Intel Core i7 4510U @ 2.00 GHz
- Graphics: Intel HD Graphics 4400
- Memory: 16GB DDR3L 1600 Mhz
- Disk: SanDisk 1TB SSD
- Clover Version: Clover_r5107
- System: MacOS Catalina 10.15.5 (19F96)

## Supported:

- Video / HDMI / Backlight
- Webcan
- Audio / Microphone / Headphones
- Keyboard / Touchpad 
- Battery
- USB 3.0 / 2.0
- LAN

## Not supported:

- Wifi & bluetooth: Atheros AR9565
    - Replace the card with DELL DW 1560
- Video Card: Radeon r7 M265 (Disabled by SSDT)
- SD Card Reader: RTS5179 (Disabled by SSDT to save energy) 
- Elan USB TouchScreen.

How to use kext files see: https://github.com/marcello0201/Dell-5447-Hackintosh-Catalina-10.15.5/blob/master/EN_Tutorial.md

-------------------

## Release notes:
- Increased Vram from 1536MB to 2048MB.
- Jack fix_v2 - automatically closes the terminal at startup.
- Activation of sleep after closing the lid and automatically wakes up when opened.
- Activation of USB ports via SSDT.
