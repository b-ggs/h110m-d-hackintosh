# ASUS H110M-D Hackintosh 
Configured for macOS 10.14.1 Mojave as iMac17,1

## System Configuration:

* Intel Core i5-6600 3.1 GHz
* 16 GB DDR4 RAM (2x8 GB 2133 and 2400 sticks)
* 120 GB SSD
* Sapphire RX 460 2 GB (has DisplayPort, DVI-D, HDMI ports)
* Realtek RTL8111H

## Working

* Intel HD 530 standalone via WhateverGreen
* Sapphire RX 460 2GB as main card via WhateverGreen
* Networking via Realtek8111 via [Mieze's RTL8111 drivers](https://github.com/Mieze/RTL8111_driver_for_OS_X)
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

## Remarks
* If you place any kexts in /S/L/E or /L/E, you will need to rebuild the cache by navigating to each directory and running `sudo kextcache -i /`
* If you are booting between Windows 10 and macOS and your Ethernet connection acts up in System Preferences -> Network, boot to Windows and fire up Device Manager and open the network card. Navigate to Advanced -> Set Wake on Magic Packet to Disabled.

## Sources
* https://github.com/volca/asus-h110m-k-d3-hackintosh
