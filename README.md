# AsusTUFX570GamingPlusWIFI
A OpenCore EFI configuration for ASUS TUF X570 Gaming Plus (WIFI)
- macOS Big Sur
- iMacPro1,1 SMBios emulated
- OpenCore 0.6.3
- with Canopy (GUI)

## Create bootable USB stick
[Follow this guide](https://dortania.github.io/OpenCore-Install-Guide/installer-guide/#creating-the-usb)
To create a bootable USB Stick or simular. It's needed to boot into MacOS (Installer) with OpenCore.

## Edit BIOS
You need to adjust some BIOS settings
[Follow this guide](https://dortania.github.io/OpenCore-Install-Guide/AMD/zen.html#amd-bios-settings)


## My Efi
This setup is completely basic. Just needed kexts and drivers to make MacOS running smoothly.
If you want to improve or extend i don't give any support on that.

### Drivers
- HfsPlus
- OpenCanopy
- OpenRuntime

### Kext
- Airportitlwm: For bringing Wifi to work
- AMDRyzenCPUPowerManagement: CPU PowerManagement
- AppleALC: For Audio
- AppleMCEReporterDisabler: Not really needed, simple having it for a backup
- Lilu: Necessary for quite all plugins as underlaying library
- RealtekRTL8111: To make LAN work
- VirtualSMC: Faking SMBios and so on
- WhateverGreen: Making graphics using my Radeon X560 work

### My system configuration for EFI build currently is
- AMD Ryzen 9 3900X
- ASUS TUF X570 Gaming Plus (WIFI)
- 32GB Corsair Vengeance RGB Pro 2x16GB
- ASUS Radeon X560
- 500GB NVMe Samsung 970 Evo Plus

### What does work
- Wifi
- LAN
- Bluetooth, sometimes has hickups
- Handoff
- iServices (you do need to generate SMBios data to get it work)
- xCode 12.1

### What does not
- Airdrop
