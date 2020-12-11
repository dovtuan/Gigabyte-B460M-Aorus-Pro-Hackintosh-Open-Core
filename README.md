
# Specifications
```
Gigabyte B460M Aorus Pro (Bios: F4)
 - Audio: Realtek® ALC1200 codec
 - Ethernet: Intel® Ethernet Connection I219V12
Intel Core i5 10400 SHR3C
Ram 2 x 8GB corsair vengeance lpx 2666CL16
SSD WD BLACK SN750 250GB NVME PCIe Gen3 x4 (WDS250G3X0C)
VGA Gigabyte Radeon™ RX 570 GAMING 4G MI
Wifi + Bluetooth BCM943602CS (WTXUP)
Monitor Samsung U28E590D 28-inch 4k
```
![9](/images/9.png)
![13](/images/13.png)
# OpenCore (Version: 0.6.4 - stable) + macOS Catalina (Version 10.15.5+) or macOS Big Sur (Version 11.0+)
- https://dortania.github.io/OpenCore-Install-Guide/
- https://github.com/acidanthera/OpenCorePkg/releases/tag/0.6.4
# Kexts include
- AppleALC (1.5.5)
- IntelMausi (1.0.4)
- Lilu (1.5.0)
- USBPorts
- VirtualSMC (1.1.9)
- WhateverGreen (1.4.5)
- XHCI-unsupported
# Work??
- Intel Quick Sync
- Handoff, Air Drop
- Rear Jack Audio Output + Input and Front Jack
- Ethernet
- Wifi
- Bluetooth
- All USB Port
- Restart, Sleep and Shutdown 
- TRIM native 
- Etc
# Not Work??
- Etc
# Result
![8](/images/8.png)
![2](/images/2.png)
![10](/images/10.png)
![11](/images/11.png)
![5](/images/5.png)
![iStat](/images/Screen%20Shot%202020-10-08%20at%2010.05.23.png)

# Note For You

1. Choose the config file for your case:
- iGPU Only then rename config_iGPU_only.plist to config.plist
- iGPU + RX4xx_RX5xx (Polaris) then next to step 2
- iGPU + RX5xxx (Navi) then rename config_iGPU+RX5xxx_Navi.plist to config.plist

2. The file config.plist. Please change MLB, SystemSerialNumber, SystemUUID
![12](/images/12.png)
