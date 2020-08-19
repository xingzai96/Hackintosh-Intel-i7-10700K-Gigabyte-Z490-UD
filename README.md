# OpenCore - Hackintosh Intel i7-10700K Gigabyte Z490 UD (With IGPU using HDMI Port)

![About this mac](/img/Screenshot2020-08-20at2.35.25AM.png)

# Summary
Manage to successfully installed MacOS Catalina 10.15.6 on Gigabyte Z490 UD **without** a dedicated graphic cards (Intel UHD Graphics 630) **using HDMI port**

# Tutorial I Followed
https://dortania.github.io/OpenCore-Install-Guide/

# Hardware
- Processor: Intel i7-10700k
- GPU: Intel UHD Graphics 630
- Mobo: Gigabyte Z490 UD
- SSD: Western Digital Black M.2 NVME 1TB
- RAM: CORSAIR DDR4 VENGEANCE PC3000 32GB 
- Wifi/BT: BCM94360

# BIOS Setting
To Be Update

# Working
- [x] **Wifi and Bluetooth** - Even with incomplete bluetooth patch (did not fix it in current EFI, do refer - https://dortania.github.io/OpenCore-Install-Guide/ktext.html#wifi-and-bluetooth if required to do it properly)
- [x] **Audio** - Front analog output working only - both input and output
- [x] **USB** - All port working (2.0, 3.0, 3.1), did not test transfer speed
- [x] **iGPU UHD630 with HDMI-output** - Currently on 2k resolution, Able to play smoothly on full hd resolution for Starcraft 2 and Dota 2
- [x] **Sleep/Wake**
- [x] **Shutdown**
- [x] **Restart**

# Not working
- [ ] **Back panel audio input & output**

# Not tested
- [ ] **USB speed**
- [ ] **Ethernet** - Using WIFI only currently
- [ ] **MacOS update** - Don't want to messed up since im using as my main PC
- [ ] **OC** - Plan to do it in near future (I hope)

# Benchmarks
To Be Update

# Credits
- https://dortania.github.io/OpenCore-Install-Guide/ (For general Guidance)
- https://github.com/georgetree/hackintosh-10700k-Gigabyte-Z490-Vision-g (For IGPU HDMI Framebuffer Patch fix)
