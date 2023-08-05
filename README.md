# SSDT-ARPT-HMF

I create a SSDT.aml for those who don't use DSDT and may have issues
Wifi card in macOS Sonoma 14 or any other version.

Test by me on my HP Probook 650 G1 without Wifi patch on my DSDT.aml

File to place in EFI/OC/ACPI and must be initialized in the config.plist

Take a good look at the file opened with MaciASL.app
The arrow indicates the Device ID what is highlighted is the device of an Azurewave BCM94352HMB Wifi Bluetooth compatible card in macOS

![SSDT-ARPT-HMF](https://github.com/chris1111/SSDT-ARPT-HMF/assets/6248794/1d2ebd4d-2472-4573-ad69-4b868175d3b3)

If you have a Compatible card of different type and want to insert the ID, open Hackintool.app
go to PCIe and find the last 4 Device IDs and change them to SSDT-ARPT-HMF.aml

#### NOTE: Letters must be lowercase in the SSDT-ARPT-HMF file
Follow the arrow at the bottom of the picture

![Hackintool](https://github.com/chris1111/SSDT-ARPT-HMF/assets/6248794/482ebf3f-e6c4-41f3-9cde-7d1c2e251c1f)


