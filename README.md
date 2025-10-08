Here’s a working OpenCore Hackintosh EFI for the Surface Laptop 1 running macOS Ventura 13.7.4

<img width="1440" alt="Screenshot 2025-05-31 at 9 06 58 PM" src="https://github.com/user-attachments/assets/10c6848f-416b-4d48-8d67-6e006efb20c1" />

Drag this into your EFI partition, and you should be good to go!

Disable SIP and install this driver for WIFI: (https://github.com/chris1111/Wireless-USB-Big-Sur-Adapter)

(I use the TP-Link Archer T2U Nano Wifi stick)

Surface Laptop 1 (2017)  
CPU: Intel Core i5-7200U, GPU: Intel UHD Graphics 620, Ram: 8GB 1867 MHz LPDDR3, Storage: 128GB NVME SSD. 

Working:  
Keyboard: ✓,  
Trackpad: ✓,  
Graphics: ✓,  
Wifi: ✓, (Needs usb wifi stick. Internal Marvell card not supported),  
Apple ID services: ◧, (Some things work. Such as App Store, and more), 
Touchscreen: ✗, 
Sleep/wake: ✓, 
Camera: ✗,  
Sound: ✓,  
Siri: ✓. 
