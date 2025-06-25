# Dell Inspiron 7501 Hackintosh

|||
|  ----  | ----  |
|CPU|Intel Core i5-10300H|
|GPU|Intel(R) UHD Graphics(UHD 630)|
|dGPU|NVIDIA GTX 1650(disabled)|
|WLAN&Bluetooth|Intel(R) AX201
|Display|15.55 in. 1080P
## Notice 
You need use [github.com/USBToolBox/tool](https://github.com/USBToolBox/tool/) to rebuild UTBMap.kext or USBMap.kext

Touchpad just work as a mouse

Internal Microphone is not work

dGPU is disabled because no driver can use

## Changelog
### 2024.08.01
Work on macOS Sonoma 14.4
 - Upgrade OpenCore & Kexts
 - Bluetooth is working now
 - Fix Screen-Backlight not working for about 3 minutes at startup
