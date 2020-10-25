# AsusTUFX570GamingPlusWIFI
A OpenCore EFI configuration for ASUS TUF Z570 Gaming Plus (WIFI)
- macOS Big Sur Beta 10 (20A5395g)
- iMacPro1,1 SMBios emulated
- OpenCore 0.6.2
- with Canopy (GUI)

### Drivers
- HfsPlus
- OpenCanopy
- OpenRuntime

### Kext
- Airportitlwm: For bringing Wifi to work
- AMDRyzenCPUPowerManagement: CPU PowerManagement
- AppleALC: For Audio
- AppleMCEReporterDisabler: Not really needed, simple having it for a backup
- IntelBluetoothFirmware: For Bluetooth
- IntelBluetoothInjector
- Lilu: Necessary for quite all plugins as underlaying library
- RealtekRTL8111: To make LAN work
- VirtualSMC: Faking SMBios and so on
- WhateverGreen

### My system configuration for EFI build currently is
- AMD Ryzen 9 3900X
- ASUS TUF X570 Gaming Plus (WIFI)
- 32GB Corsair Vengeance RGB Pro 2x16GB
- ASUS Radeon X560
- 500GB NVMe Samsung 970 Evo Plus

### What does work
- Wifi
- Bluetooth, sometimes has hickups
- Handoff
- iServices (you do need to generate SMBios data to get it work)
- xCode 12.1

### What does not
- Airdrop
