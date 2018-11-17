# ASUS H110M-D Hackintosh

Configured for macOS 10.14.1 Mojave as iMac17,1

## System Configuration:

* Intel Core i5-6600 3.1 GHz
* 16 GB DDR4 RAM (2x8 GB 2133 and 2400 sticks)
* 120 GB SSD
* Sapphire RX 460 2 GB (has DisplayPort, DVI-D, HDMI ports)

## Working

* Intel HD 530 standalone via WhateverGreen
* Sapphire RX 460 2GB as main card via WhateverGreen
* Networking via Realtek8111
* ALC887 via AppleALC

## Miscellaneous Kexts
* [NoVPAJpeg to support viewing JPEGs using Preview](https://www.insanelymac.com/forum/topic/334881-how-to-fix-quick-look-and-preview-issues-in-mojave/)

## BIOS Configurations
* CSM (Compatibility Support Module): Disabled
* Intel Virtualization: Disabled (You can enable this later after setup)
* VT-d: Disabled (You can enable this later after setup)
* Primary Display: PCIE
* iGPU Multi-Monitor: Disabled
* Serial Port: Off
* Parallel Port: Off

## Sources
* https://github.com/volca/asus-h110m-k-d3-hackintosh
