# Lenovo ThinkPad T14 Gen 1 - OpenCore Configuration

<img align="right" src="/img/t14-gen-1-monterey.png" alt="macOS Monterey running on the T14 Gen 1" width="425">

[![macOS](https://img.shields.io/badge/macOS-Monterey-brightgreen.svg)](https://developer.apple.com/documentation/macos-release-notes)
[![macOS](https://img.shields.io/badge/macOS-Mammoth-brightgreen.svg)](https://developer.apple.com/documentation/macos-release-notes)
[![OpenCore](https://img.shields.io/badge/OpenCore-0.8.0-blue)](https://github.com/acidanthera/OpenCorePkg)
[![License](https://img.shields.io/badge/license-MIT-purple)](/LICENSE)

<a href="https://paypal.me/askwakhid/"><img src="img/blue.svg" height="40"></a>
<a href="https://trakteer.id/wakhid/"><img src="img/trakteer.png" height="40"></a>
&nbsp;
If you enjoyed this project — or just feeling generous, consider buying me a coffee. Cheers! :coffee:


**DISCLAIMER:**  
This OpenCore EFI works fine on my Thinkpad T14 Gen 1.
I am not responsible for any damages you may cause.  
Should you find an error or improve anything — whether in the config or in the documentation — please consider opening an issue or pull request.

&nbsp;

## 💻 My Hardware

| Category  | Component                                  |
| --------- | ------------------------------------------ |
| CPU       | Intel(R) Core(TM) i5-10210U CPU @ 1.60GHz  |
| GPU       | Intel UHD Graphics 630                     |
| SSD       | WD SN720 512GB M.2 NVMe SSD                |
| Memory    | 16GB DDR4 2666Mhz                          |
| Camera    | 720p Camera + IR Camera                    |
| Audio     | Intel Smart Sound Technology: Realtek HDA ALC257 (aka ALC3287)    |
| WiFi & BT | Intel Wi-Fi 6 AX201 802.11ax 2x2 with BT5.2 (Soldered on)           |
| Display   | 14" Full HD (1920x1080) IPS, touch         |

&nbsp;

## 🔄 Update Tracker

| Software  | Version                                                       |
| --------- | --------------------------------------------------------------|
| [MacOS](https://www.apple.com/macos/)                            | 12.6.2   |
| [OpenCore](https://github.com/acidanthera/OpenCorePkg/releases)  | 0.8.8    |

&nbsp;

## Status

<details>  
<summary><strong>✅ What's working</strong></summary>
</br>
 
- [X] Intel WiFi & Bluetooth (thanks to [itlwn](https://github.com/OpenIntelWireless/itlwm))
- [X] Brightness / Volume Control
- [X] Battery Information
- [X] Audio Out (Audio Jack & Speaker)
- [X] Audio In (Microphone Only from Audio Jack)
- [X] USB Ports & Built-in Camera
- [X] Graphics Acceleration
- [X] Trackpoint / Touchpad
- [X] Power management / Sleep
- [X] FaceTime / iMessage (iServices)
- [X] HDMI
- [X] Automatic OS updates
- [X] Handoff / Universal Clipboard
- [X] SIP / FireVault 2
- [X] USB-C
- [X] Thunderbolt 3


</details>

<details>  
<summary><strong>⚠️ What's not working</strong></summary>
</br>
- [ ] Internal Microphone, common issue laptop with Intel Smart Sound Technology ( Intel SST )
- [ ] Safari DRM ```Use Chromium powered Browser or Firefox to watch Amazon Prime Video, Netflix, Disney+ and others```
- [ ] AirDrop & Continuity
- [ ] Fingerprint Reader (Disabled with NoTouchID kext)
- [ ] Touchscreen ( I will working on this as soon as possible )

</details>

<details>  
<summary><strong>🔄 Not tested</strong></summary>
</br>

- [ ] Sidecar Wireless
- [ ] Apple Watch Unlock
- [ ] WWAN
- [ ] Dualbooting Windows / Linux (with OpenCore)
- [ ] Sidecar (Cable) / AirPlay to Mac


</details>

&nbsp;

## ⭐️ Feedback
Did you find any bugs or just have some questions? Feel free to provide your feedback using the Discussions tab.

&nbsp;

## 📜 License

This repo is licensed under the [MIT License].

OpenCore is licensed under the [BSD 3-Clause License](https://github.com/acidanthera/OpenCorePkg/blob/master/LICENSE.txt).


&nbsp;

## Credits

- [Apple](https://apple.com) for macOS.
- [Acidanthera](https://github.com/acidanthera) for OpenCore and all the lovely hackintosh work.
- [Dortania](https://dortania.github.io/OpenCore-Install-Guide/config-laptop.plist/icelake.html) For great and detailed guides.
- [Baio1977](https://github.com/Baio1977/) Ventura EFI for T14 Gen 1.

---
```Copyright (c) 2022 Wakhid Nusa. <askwakhid@gmail.com>```
