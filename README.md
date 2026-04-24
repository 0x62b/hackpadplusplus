# Hackpad++
6-key hot-swappable RGB backlit macropad based on Seeed Studio Xiao NRF52840. Uses ZMK for firmware.
400mAh battery, supports wireless BLE HID operation. I made this to learn more about ZMK for my [keyboard](https://github.com/0x62b/YetAnotherKeyboard)
project.

According to ZMK's [power profiler](https://zmk.dev/power-profiler) we should get about 21 hours of battery life with the RGB at 20% brightness

![Schematic](images/schematic.png)
![PCB](images/pcb.png)
![Full PCB render](images/render.png)
![Case + PCB render](images/fullrender.png)

## Repo Structure
CAD files in `cad/`
KiCad design files in `PCB/`
Production gerbers in `PCB/gerbers`
Firmware in `firmware/`
BOM at `bom.csv`
Case Onshape design [here](https://cad.onshape.com/documents/916857c7e80611f775a72b60/w/b9c69dbfc296334dd1ffd629/e/9b910e13e67ad3b8cb3a877d?renderMode=0&uiState=69eb64186156e8d7dafdc7be)

## 3D Models
https://grabcad.com/library/oled-0-91-128x32-1
https://grabcad.com/library/seeed-studio-xiao-nrf52840-sense-1
https://grabcad.com/library/kailh-polia-switch-cherry-mx-compatible-1
https://grabcad.com/library/11mm-metal-shaft-rotary-encoders-tht-vertical-w-push-on-switch-1
https://grabcad.com/library/dsa-keycap-for-cherry-mx-switches-1