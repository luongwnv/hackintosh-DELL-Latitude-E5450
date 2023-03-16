# Dell-Latitude-E5450-OC-Hackintosh

OpenCore based EFI for Dell Latitude E5450


![5450](https://user-images.githubusercontent.com/93620854/212493683-61976fbe-e65b-4da9-b317-eb0577cdfc99.png)



## Tested macOS Version

- macOS Mojave 10.14.6
- macOS Catalina 10.15.7
- macOS BigSur 11.7.3
- macOS Monterey 12.6.3


## System Configuration

- CPU:  Intel Core i5-5300U
- iGPU: Intel HD Graphics 5500
- RAM:  16GB DDR3L 1600Mhz
- SSD:  Crucial MX500 500GB
- WiFi: Intel Wireless 8260NGW
- Display: 1920*1080 FullHD IPS
- Sound Card: Realtek ALC293 (ALC3235)
- LAN: Intel I218-LM

### BIOS Version

A24


### Bootloader

OpenCore 0.8.3


### SMBIOS

MacBookPro12,2



## What's working

 
 - [x] CPU Speedstep

 - [x] iGPU acceleration

 - [x] Battery Management
 
 - [x] Sleep/Wake
 
 - [x] Internal Speakers
 
 - [x] Internal Microphone
 
 - [x] WiFi - using HeliPort - https://github.com/OpenIntelWireless/HeliPort
 
 - [x] Bluetooth

 - [x] Ethernet

 - [x] HDMI + audio over HDMI

 - [x] Touchpad with Gestures + Trackpad + Buttons

 - [x] Web Camera

 - [x] USB 3.0

 - [x] SD card reader 

 - [x] Native hotkeys support with Fn keys (Volume Fn+F2/F3 and Screen Brightness Fn + F11/F12)
 


## What's not working


- [ ] Smart card reader


## What's not tested yet


- WWAN card


## Additional Notes

Don't forget to generate your own SMBIOS with https://github.com/corpnewt/GenSMBIOS. 

- ENJOY!
