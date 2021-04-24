# Asus ROG GL502VT Hackintosh macOS Big SUR wıth OPENCORE

This is a guide to hackintoshing the ASUS ROG GL502VT on macOS Big SUR.


## Specs

//\\\ | Asus ROG GL502VT
------------ | -------------
Model | GL502VT-FY034T
Motherboard chipset | Intel HM170
Processor |	Intel Skylake Core i7-6700HQ CPU, quad-core 2.6 GHz (3.5 GHz TBoost)
Screen |	15.6 inch, 1920 x 1080 px resolution, matte, IPS, non-touch
Video |	Integrated Intel HD 530 + Nvidia GTX 970M 2GB
Memory |	16 GB DDR4 2133Mhz (2xDIMMs)
Storage |	500 GB SSD (Samsung SSD 850 EVO M.2 500GB) + 1 TB 2.5″ HDD (HGST HTS721010A9E630)
Connectivity |	Wireless Intel Dual Band 8260 , Realtek RTL8111, Bluetooth 4.0
Ports | 1x USB 2.0,	2x USB 3.0, 1x USB 3.1, HDMI, mic, earphone, SD card reader, LAN
TouchPad | Asus Precision Touchpad (ELAN1200 - I2C HID)
Audio | Realtek ALC255

# What works

* Intel HD 530
* HDMI
* Bluetooth
* All USB ports
* Keyboard
* TouchPad 
* Fn Keys (F1 to F12) (ASUS SMC: https://github.com/hieplpvip/AsusSMC)
* Keyboard Backlighting (ASUS SMC: https://github.com/hieplpvip/AsusSMC)
* Ethernet (LAN)
* WiFi(https://github.com/OpenIntelWireless/)
  Install HeliPort to your OS : (https://github.com/OpenIntelWireless/HeliPort)
* UVC HD Webcam
* Speaker + Internal Microphone ( ALCID = 3,  your alcid may be different :https://dortania.github.io/OpenCore-Post-Install/universal/audio.html#finding-your-layout-id)

# What doesn't work

* Battery Status(I didn't try to fix.)
* NVIDIA Optimus (impossible to get working at the moment)


I followed the Dortania Guides: https://dortania.github.io/OpenCore-Install-Guide/ please look at it for any issues
