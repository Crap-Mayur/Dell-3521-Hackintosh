## Dell Inspiron 3521 Hackintosh Using Opencore
![Dell Inspiron 3521 BigSur](https://i.imgur.com/7NNG1gg.png)

## Installation Guide Followed
 OpenCore Install Guide https://dortania.github.io/OpenCore-Install-Guide/

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

## What is not working
- Card Reader
- Sleep not working, so goto `System Preferences > Energy Saver`, set `Computer sleep` and `Display sleep` to never and uncheck Wake for network access

## References & Special thanks to
- [OpenCore](https://dortania.github.io/OpenCore-Install-Guide/)
- [Boot to Recovery](https://apple.stackexchange.com/questions/367336/macos-boot-to-recovery-mode-command-line)
- [gibMacOS ](https://github.com/corpnewt/gibMacOS)
- [GenSMBIOS](https://github.com/corpnewt/GenSMBIOS)
