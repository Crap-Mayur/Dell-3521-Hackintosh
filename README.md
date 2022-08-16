## Dell Inspiron 3521 Hackintosh Using Opencore
![Dell Inspiron 3521 BigSur](https://i.imgur.com/wIUltb0.png)

## Installation Guide Followed
 OpenCore Install Guide https://dortania.github.io/OpenCore-Install-Guide/
 
## IMP FOR BOOTING
 You will Need to gen serial and add it to config.plist using Gensmbios

## System Configuration
Dell Inspiron 3521
- Audio Device ALC3221 --> ALC282
- Intel i3 3217U - Ivy Bridge
- Intel HD4000 (iGPU)
- Dell Wireless 1705
## What is working
- Intel HD4000 Graphics
- Brightness Control
- HDMI
- Camera
- Battery Status
- LAN
- WiFi
- BlueTooth
- USB Controller
- System Trackpad and keyboard
- External USB Keyboard and Mouse
- Sleep Works

## What is not working
- Card Reader
- Audio

## References & Special thanks to
- [OpenCore](https://dortania.github.io/OpenCore-Install-Guide/)
- [gibMacOS ](https://github.com/corpnewt/gibMacOS)
- [GenSMBIOS](https://github.com/corpnewt/GenSMBIOS)
