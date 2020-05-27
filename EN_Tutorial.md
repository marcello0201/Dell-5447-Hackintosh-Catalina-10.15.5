## Tutorial how to install kexts

- EFI / CLOVER / kexts / Other: Where are most Kexts to operate the system.
- / Library / Extensions /: These kexts support the DW1560's bluetooth.
- DisplayProductID-5f1: The notebook display support folder must be placed in the directory in its entirety.
- / usr / bin: Support CodecCommander.kext, correcting the ALC255 audio.
- Jack fix_v2 - Repairs the noise sound when using P2 headphones, and must be initialized with the system.

## Where to put kext:

- / Library / Extensions /

     * BrcmBluetoothInjector.kext

     * BrcmFirmwareRepo.kext

     * BrcmPatchRAM3.kext

- / System / Library / Displays / Contents / Resources / Overrides

     * DisplayProductID-5f1

- / usr / bin

     * hda-verb

- System preferences / Users and groups / start items

     * Jack fix_v2

## Problems with sleep ?

In this notebook model, to ensure that sleep works correctly on Mac OS, it is necessary to update the cpu firmware to allow sleep to work correctly, following this tutorial you can perform the update, but remembering AND AT YOUR OWN RISK.

https://github.com/marcello0201/Dell-5547-Hackintosh/tree/master/Management-Engine-Firmware

Common bugs see: 

## Bios settings

![Screenshot](https://github.com/marcello0201/Dell-5447-Hackintosh-Catalina-10.15.5/blob/master/Bios%20setings/1.png)
![Screenshot](https://github.com/marcello0201/Dell-5447-Hackintosh-Catalina-10.15.5/blob/master/Bios%20setings/2.png)
![Screenshot](https://github.com/marcello0201/Dell-5447-Hackintosh-Catalina-10.15.5/blob/master/Bios%20setings/3.png)
![Screenshot](https://github.com/marcello0201/Dell-5447-Hackintosh-Catalina-10.15.5/blob/master/Bios%20setings/4.jpg)
