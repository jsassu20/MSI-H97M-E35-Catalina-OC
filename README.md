# MSI-H97M-E35 (Haswell) 
### Custom iMac Hackintosh Build (OpenCore)

macOS 10.15.x Catalina 

```  
- Intel 4th Generation Architecture (Haswell)
- Intel HD Graphics 4600 (OOB Support)
- Realtek ALC3887 Audio Codec (Layout-ID = 3)
- Intel Series 9 Chipset Family
- macOS 10.15.x (Catalina)
- OpenCore Configuration (Runs Awesome)
- AirPort AC WiFi 1.3Gb/s (Broadcom BCM94360CD) * 
  - WiFi requires a PCIe x2 adapter with Apple's proprietary 12+6 pin port.
  - Bluetooth requires a USB 2 motherboard header (or a free USB 2 port if you modify the included cable)
    - Included cable is a standard 4 pin USB 2.0 cable with a MB header plug
    - Cut off the header and Splice in a male USB 2.0 plug from any USB cable
    - Just solder the 4 colored wires on both cables to eachother  
      - Red to Red
      - Black to Black 
      - White to White 
      - Green to Green (Green to Yellow if one cable has no green wire)     
- All native macOS Catalina features work as long as you upgrade the WiFi card to a supported configuration
```

#

### PayPal

- If you like my work then please feel free to donate. Every little bit helps! jsa55u@icloud.com | Paypal.me/Sass86oh

#

### iMessage (Contact me whenever for help)

- Jsass20@gmail.com (or Jsassu20@me.com)

#

## Credits

RehabMan:

- For a number of different parts of this configuration which have made this build possible including his USBInjectAll.kext configuration, SSDT-DEH01 for disabling the EH01 device and allowing all USB traffic on the XHC device, VoodooPS2Controller.kext which provides a perfect configuration for TouchPad functionality along with SSDT-VPS2 which is based on his SSDT-PS2K Hot Patched file, SSDT-UIAC for providing a template to configure proper USB injection, and a number of other SSDT Hot Patches present in the dsl folder which can be used to configure a number of different situations. RehabMan is an absolute genius when it comes to Hackintosh configurations in the community and I owe the knowledge I've managed to gain over the last year to his tireless efforts and guides in the community.

JcSnider:

- For providing me with an excellent build in the for of his Lenovo ThinkPad X1 Carbon Generation 3 Build which has been the basis of this Hot Patched configuration. A number of the Hot Patched files present in this build come directly from his X1 Carbon configuration and it has been the main reason why I've been able to adapt a build for us T450 users so please thank him for his outstanding work!

AcidAnthera:

- For Lilu.kext and all of the included Lilu Plugins which have made countless configurations possible among a plethora of Hackintosh machines! AcidAnther is a genius coder and developer and without his hard work and effort we would not be able to create the sheer number of hackintosh configurations with universal kexts like we have the ability to do now thanks to his/her development.

Snikii:

- For a number of his Hot Patched files which inspired a lot of the files I've been able to adapt. For his contribution to ThinPad hackintosh configurations which I've used for inspiration. For his install guides on Tonymacx86.com which I've used to learn countless amounts of info from in adapting this configuration. 

The Hackintosh Community:

- Without which I would not have been able to learn everything I have been able to learn. I want to thank you all this community is amazing!

   
## Hardware Configuration:

```  
- Intel 4th Generation Core i5-4590 Processor
  * Quad Core CPU @ 3.0 GHz (up to 4.0 GHz with Turbo Boost) 
- Hynix 16GB Memory with Dual Channel Support 
  * 2x8 DDR3 Modules @ 1600 MHz with 
- Intel HD Graphics 4600 (Works OOB without any prior configuration or 3rd party kext needed)
  * 1536 MB VRAM | Full QE/CI & Metal Support 
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
    
