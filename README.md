# Infinix X1 Hackintosh OpenCore

## Specifications

| Component | Detail |
|---|---|
| Laptop | Infinix X1 |
| CPU | Intel Core i3-1005G1 |
| iGPU | Intel UHD G1 |
| RAM | 8GB DDR4 |
| SSD | NVMe SSD (256GB) |
| WiFi | Intel Wireless |
| Audio | Realtek ALC269 |
| SMBIOS | MacBookAir9,1 |

---
## Recommended Tools

- ProperTree
- OCAuxiliaryTools
- GenSMBIOS
- Hackintool

---
## Working

- Graphics Acceleration (1536 MB)
- Audio
- Keyboard
- Sleep/Wake
- Brightness Control
- USB Ports
- Intel WiFi
- Bluetooth
- Camera

---

## Not Working / Untested

- Microphone
- AirDrop may not work properly
- DRM limited
- HDMI untested

---

## OpenCore Version

- OpenCore 1.0.7

---

## BIOS Settings

- Disable Secure Boot
- Enable UEFI Boot
- Disable Fast Boot
- SATA Mode: AHCI
- DVMT Pre-Allocated: 64MB or 128MB

---

## Notes

This EFI was made specifically for the Infinix X1 with Intel 10th Gen Ice Lake processors.

It may also work on similar laptops using the same chipset and hardware configuration.

> Please generate your own SMBIOS values before using this EFI.

---

## Credits

- [OpenCore Install Guide](https://dortania.github.io/OpenCore-Install-Guide/?utm_source=chatgpt.com)
- [OpenCorePkg](https://github.com/acidanthera/OpenCorePkg?utm_source=chatgpt.com)
- Acidanthera Team
- Hackintosh Community
- Gemini
- ChatGPT

