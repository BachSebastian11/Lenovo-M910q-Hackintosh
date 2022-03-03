# Lenovo-M910q/710q-Hackintosh
OpenCore 0.7.6 compatible with macOS Monterey for Lenovo ThinkCentre M910q/710q   
Mine unit is come with a Xeon 2176M, but should works with any M910q/710q platform with modified BIOS to support 8th gen CPUs
![image](https://github.com/nvt194/Lenovo-M910q-Hackintosh/blob/main/Screenshots/about.png?raw=true)

### System Specs :

| Component        | Specifications                         |
| ---------------- | -------------------------------------- | 
| CPU              | Intel® Xeon™ E-2176M(Mobile)           | 
| iGPU             | Intel® UHD Graphics P630               |
| RAM              | 2 * Samsung 8GB DDR4 2666Mhz           | 
| NVMe             | T-Force CARDEA Zero Z440 1TB           | 
| LAN              | Intel I219-V                           | 
| Audio            | Realtek ALC294                         | 
| WiFi & Bluetooth | Apple BCM943224 with adapter to NGFF   | 
| SMBIOS           | MacMini8,1                             |
| BootLoader       | OpenCore 0.7.6                         |

### What Works :

- [x] Intel UHD Graphics P630 iGPU DP Output 
- [x] DP to HDMI Adapter 
- [x] ALC294 Internal Speakers 
- [x] ALC294 & DP Audio Output 
- [x] ALC294 Audio Input 
- [x] All USB Ports 
- [x] Intel I219-V
- [x] Apple Wi-Fi & Bluetooth, not sure about advanced Apple features like Airdrop, Handoff since I don't use iPhone
- [x] NVRAM 

### UEFI Firmware :

* Modified M710q BIOS to support 8th gen CPUs

* Disable: CSM

## Credits 

- [dfc643] obviously.
- [wxjiyc](https://github.com/wxjiyc/Lenovo-M710q-QNCT-Hackintosh) based on @wxjiyc's EFI files.
- [Apple](https://apple.com) for macOS.
- [Dortania](https://github.com/dortania) for great and detailed guides.
