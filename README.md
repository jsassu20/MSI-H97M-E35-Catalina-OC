# MSI-H97M-E35 (Haswell) 
### Custom iMac Hackintosh Build (OpenCore)

macOS 10.15.x Catalina 

![](Utilities/Images/MSI-H97M-E35.jpg)

```  
- Intel 4th Generation Architecture (Haswell)
- Intel HD Graphics 4600 (OOB Support)
- Realtek ALC887 Audio Codec (Layout-ID = 3)
- Intel Series 9 Chipset Family
- macOS 10.15.x (Catalina)
- OpenCore Configuration (Runs Awesome)
- AirPort AC WiFi 1.3Gb/s (Broadcom BCM94360CD) * 
  - PCIe x2 adapter with Apple's proprietary 12+6 pin port is required.
  - Bluetooth functionality uses the motherboards internal USB hub which needs to connect to a 9 pin USB 2.0 header on the motherboard.
  - The cable can be modified to work with any available USB port if no header exists 
    * Included cable is a standard 4 pin USB 2.0 cable with a MB header plug
    * Cut off the header and Splice in a male USB 2.0 plug from any USB cable
    * Just solder the 4 colored wires on both cables to eachother  
      - Red to Red
      - Black to Black 
      - White to White 
      - Green to Green (Green to Yellow if one cable has no green wire)     
- All native macOS Catalina features work as long as you upgrade the WiFi card to a supported configuration
```
![](Utilities/Images/MSI-H97M-E35-USB-Ports.png)
#

### PayPal

- If you like my work then please feel free to donate. Every little bit helps! jsa55u@icloud.com | Paypal.me/Sass86oh

#

### iMessage (Contact me whenever for help)

- Jsass20@gmail.com (or Jsassu20@me.com)

#

## Credits

The Hackintosh Community:

- Without which I would not have been able to learn everything I have been able to learn. I want to thank you all this community is amazing!

   
## Hardware Configuration:

```  
- Intel 4th Generation Core i5-4590 Processor
  * Quad Core CPU @ 3.0 GHz (up to 4.0 GHz with Turbo Boost) 

- AMD Radeon RX 5500XT (MSI 8GB GDDR6 Version)
  * Works OOB with macOS 10.15.1 and later
  * No configuration needed but whatevergreen needs to be removed from kext or the boot process results in a black screen after Apple logo finishes loading during boot 
  * Onboard Intel HD Graphics 4600 Works OOB without any prior configuration or whatevergreen kext requirements)
  * Works with Dual graphics output to seperate displays

- Apple Airport WiFi & Bluetooth Card from Apples Current iMac Pros
  * Broadcom BCM94360CD Card w/ 4 Antenna Connectors
  * Best card Apple offers with their Pro systems  
    - Wireless AC (1300 MB/s) 
    - Bluetooth 4.0 with full Continuity support OOB  
```
    
## Build Features:

- This is a 100% working macOS Catalina setup! Nothing needs to be changed! Just swap your files with mine and enjoy! (WiFi upgrade needed for complete functionality)

- AppStore Purchases, iMessage, FaceTime, Instant Hotspot, Continuity, Handoff, AirDrop, iTunes Purchases, System Update, Siri, Metal, Sleep, Power Settings, Backlight Control, Touchpad Gestures (3 and 4 Finger Including Swipes) AirPort Extreme Functionality, Bluetooth, Location Services, iCloud Features are Fully supported with the proper AirPort card. Battery functioning properly thanks to hot patched files.  

- Find My Mac only works with real AirPort card! If you lock the device via iCloud with a PC WiFi card (even with a supported chipset) you're gonna find    yourself in a situation you don't want to deal with. 

[](https://github.com/jsassu20/MSI-H97M-E35-Catalina-OC/blob/master/Utilities/Images/Broadcom%20BCM94360CD%20Airport%20Card.png?raw=true)
[](https://github.com/jsassu20/MSI-H97M-E35-Catalina-OC/blob/master/Utilities/Images/Broadcom%20BCM94360CD%20Adapter.png?raw=true)
