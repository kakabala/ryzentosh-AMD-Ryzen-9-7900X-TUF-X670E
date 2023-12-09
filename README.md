# Ryzentosh for AMD Ryzen 9 7900X + X670E-PLUS Wifi

## Specification
|  Component  | Model  |
| ------------ | ------------ |
| CPU  | AMD Ryzen 9 7900x |
| Motherboard | TUF Gaming X670E-PLUS Wifi  |
| RAM  | 64GB (2x16GB) Trident Z Neo DDR5  |
|  GPU  | Gigabyte Radeon RX 6600 XT Gaming OC  |
| Ethernet  | Realtek RTL8125  |
| Wifi + Bluetooth  | BCM94360CD Wifi Card  |

## ACPI
- SSDT-CPUR
- SSDT-IGPU-DISABLE.aml
- SSDT-DTPG.aml
- DSDT-X670E-TUF-WIFI-patched.aml
- SSDT-EC-USBX.aml
- SSDT-SBUS-MCHC-AMD.aml


## Kext
- Lilu
- VirtualSMC
- LucyRTL8125Ethernet
- WhateverGreen
- AppleMCEReporterDisabler
- AMDRyzenCPUPowerManagement
- AppleALC
- RestrictEvents
- USBToolBox
- UTBMap
- RadeonSensor
- SMCRadeonGPU
- SMCAMDProcessor
- USBToolBox
- UTBMap
- NVMeFix
- Innie
- IOSkywalkFamily
- IO80211FamilyLegacy
- IO80211FamilyLegacy.kext/Contents/PlugIns/AirPortBrcmNIC
- AMFIPass

## Not Tested
- USB4/Thunderbot

## Not Working
- M2 Wifi 6: MT7921K is not supported

### MacOS version : Sonoma (14.x)
### SMBIOS : MacPro7.1
### Motherboard Bios version : 1813

