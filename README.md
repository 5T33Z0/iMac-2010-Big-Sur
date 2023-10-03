# iMac11,3 OpenCore EFI (27", 2010)

![Bildschirmfoto 2023-08-11 um 18 46 03](https://github.com/5T33Z0/iMac-2010-Big-Sur/assets/76865553/cd91497e-b8bc-40e5-a99c-0c122dfaea1c)

## About
EFI for my 27" `iMac11,3` from 2010. It's based on the EFI generated by OCLP but with a few tweaks to suite my configuration and requirements.

**Supported macOS** (with this GPU and WiFI/BT Card): macOS Big Sur

> **Note**: Requires Post-Install Root Patching with OpenCore Legacy Patcher.

## Specs

**Model**: `iMac11,3` Mid-2010 A1312 [base model](https://everymac.com/systems/apple/imac/specs/imac-core-i3-3.2-27-inch-aluminum-mid-2010-specs.html)

Component | Description
----------|-----------
**CPU** | Intel Core i7-870 (upgraded from i3-550)
**GPU** | ATI Radeon HD 5670 (512 MB)
**RAM** | 16 GB DRR3 by Samsung (1333 Mhz)
**Storage** | Kingston 120 GB SSD (for testing) with custom-made, 3d printed mount.
**Ethernet** | Broadcom BCM5701
**WiFi** | Atheros AR 9280 
**Bluetooth** | Broadcom BCM2046

## Tweaks
Since this iMac would need a GPU upgrade in order to install and run anything newer than Big Sur, a lot of kexts present in the EFI generated by OCLP are not required, so I removed them, thereby reducing the amount of injected kexts from 20 to 11! See details below.

- Deleted Kexts unnecessary for running macOS Big Sur and older:
  Original | Modified
  ---------|----------
  ![og](https://github.com/5T33Z0/iMac-2010-Big-Sur/assets/76865553/aa2dc5d0-da40-4abf-8c70-94caee990180) | ![modded](https://github.com/5T33Z0/iMac-2010-Big-Sur/assets/76865553/25c2181d-a300-44a6-841e-31d2e6cd29c6)
- Uses latest nightly OpenCore and Kext builds
- Changed default BG Color to grey because that's what real iMac 2010 uses.

## Credits
- Acidanthera for OpenCore and kexts
- Dortania for OpenCore Legacy Patcher and OpenCore Legacy Patcher Guide
