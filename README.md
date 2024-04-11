# Ryzentosh for AMD Ryzen 9 7900X + TUF X670E-PLUS Wifi

## Specification
|  Component  | Model                               |
| ------------ |-------------------------------------|
| CPU  | AMD Ryzen 9 7900x                   |
| Motherboard | TUF Gaming X670E-PLUS Wifi          |
| RAM  | 64GB (2x16GB) Trident Z Neo DDR5    |
|  GPU  | Gigabyte Radeon RX 6600 XT Gaming OC |
| Ethernet  | Realtek RTL8125                     |
| Wifi + Bluetooth  | AX211 Wifi Card                     |

## ACPI
- SSDT-CPUR
- SSDT-IGPU-DISABLE.aml
- SSDT-DTPG.aml
- DSDT-X670E-TUF-WIFI-patched.aml
- SSDT-EC-USBX.aml
- SSDT-SBUS-MCHC-AMD.aml
- SSDT-UIAC.aml
- SSDT-GPRW.aml


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
- SMCRadeonGPU
- USBPorts
- NVMeFix
- Innie
- AirportItlwm_Sonoma144
- AirportItlwm_Sonoma140
- AirportItlwm-Ventura
- AirportItlwm-Monterey
- IntelBluetoothFirmware
- IntelBTPatcher
- BlueToolFixup

## Not Tested
- USB4/Thunderbot

## Not Working
- M2 Wifi 6: MT7921K is not supported
- iService not working on Sonoma 14.4 with Wifi

### MacOS version : Sonoma (up to 14.4.1), Ventura
### SMBIOS : MacPro7.1
### Motherboard Bios version : 1813

