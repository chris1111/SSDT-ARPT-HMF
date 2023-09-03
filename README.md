# SSDT-ARPT-HMF for Laptop and PC

I create a [SSDT.aml](https://github.com/chris1111/SSDT-ARPT-HMF/blob/Master/SSDT-ARPT-HMF.txt)
for those who don't use DSDT and may have issues
Wifi card in macOS Sonoma 14 or any other version.

Test by me on my HP Probook 650 G1 without Wifi patch on my DSDT.aml

File to place in EFI/OC/ACPI and must be initialized in the config.plist

Download ➤ [SSDT-ARPT-HMF](https://github.com/chris1111/SSDT-ARPT-HMF/blob/Master/SSDT-ARPT-HMF.aml.zip)

Take a good look at the file opened with [MaciASL.app](https://bitbucket.org/RehabMan/os-x-maciasl-patchmatic/downloads/RehabMan-MaciASL-2018-0507.zip)
- The arrow indicates the Device ID what is highlighted is the device of an `Azurewave BCM94352HMB` Wifi Bluetooth compatible card in macOS
  

![SSDT-ARPT-HMF](https://github.com/chris1111/SSDT-ARPT-HMF/assets/6248794/d16c0fc0-dd58-410e-a1a4-60ae96443a68)


If you have a Compatible card of different type and want to insert the ID, open [Hackintool.app](https://github.com/benbaker76/Hackintool/releases)
go to PCIe and find the last 4 Device IDs and change them to SSDT-ARPT-HMF.aml

#### NOTE: Letters must be lowercase in the SSDT-ARPT-HMF file
Follow the arrow at the bottom of the picture

![Hackintool](https://github.com/chris1111/SSDT-ARPT-HMF/assets/6248794/2a2a4631-2392-4115-92e9-dde86af564f4)



