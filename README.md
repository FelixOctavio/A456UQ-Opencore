# This repo is not maintained anymore

# Opencore (Hackintosh EFI) for ASUS A456UQ (i7 7500U + 940MX)
Tested on Ventura 13.1

![Ini Screenshot](/Screenshot.png)

## Specification:
+ CPU : Intel Core i7 7500U 2.90 Ghz
+ iGPU : Intel HD Graphics 620
+ dGPU : Nvidia GeForce 940MX (disabled)
+ Storage : Crucial MX500 512GB SSD + 1TB HDD HGST HTS541010A9E680
+ RAM : Samsung M471A5143EB0-CPB 4GB 2133Mhz DDR4 (Soldered) + Micron 16ATF1G64HZ-2G1B1 8GB 2133Mhz Dual Rank DDR4
+ Wifi + Bluetooth : Qualcomm Atheros AR956x
+ Audio : Conexant CX8050
+ Ethernet : Realtek RTL8111
+ USB Ports : 1x USB 2.0, 1x USB 3.0, 1x USB 3.1 Type-C non-Thunderbolt
+ Touchpad : I2C ELAN1200
+ Screen Size : 14"
+ Screen Res : 1366 x 768p (My original panel (1080p) are broken, so i use another panel)

## Works:
+ IGPU
+ Sleep
+ Touchpad
+ Audio + 3.5mm audio jack
+ Internal Mic
+ LAN
+ USB Ports
+ Touchpad
+ Built-in Webcam
+ HDMI port (Need to replug every boot)
+ VGA Port
+ Ethernet port
+ Brightness
+ Asus FN hotkey
+ Battery Indicator

## Not work:
+ iCloud / iService (untested)
+ Appstore (untested)
+ Wifi and bluetooth
+ Card reader (untested + not detected in mac)

Note:
- Battery drain while sleep
