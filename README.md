# [SUCCESS] Mi-Notebook-14-Hackintosh
Tested on i3 & i5 models, yet to test on i7(horizon)



## Laptop Specs

| Specifications | Detail                                                  |
| ------------------- | ------------------------------------------- |
| Laptop model      | Mi Notebook 14 2020     |
| Processor           | Intel Core i5-10210U         |
| Memory              | 8GB Samsung DDR4 2666MHz              |
| Hard Disk           | SATA SSD Controller                |
| Integrated Graphics | Intel UHD Graphics 620                     |
| Sound Card          | Realtek ALC256                             |
| Wireless Card       | Intel Wireless 9560                        |
| Touchpad            | I2C ELAN2304                               |


## What Works
- Intel UHD Graphics
- Wifi
- Bluetooth
- Touchpad including Gestures
- Keyboard
- Webcam (Tested on i3 model)
- Audio (Both Speaker and Headphones)
- Microphone (Only headset. Fix below)
- Battery Manager
- Brightness
- Almost Everything Important xD.

## What's Broken
- HDMI (Will Update if fixed)
- ~~Bluetooth (Will Update if fixed)~~ FIXED
- ~~Microphone (Will Update if fixed)~~ HEADPHONE MICROPHONE(FIX BELOW)
- iMessages (IG it'll work after SMBIOS edit) 

## Not Tested
- ~~Camera (No inbuilt camera. I forgot to order webcam along with laptop xD).~~ Works on i3 model, not tested on any other.
- Facetime (No Webcam. Will most likely work after changing SMBIOS).

## Microphone Fix (Headset)
- Download Combojack [here.](https://github.com/hackintosh-stuff/ComboJack)
- Follow the documentation to install combojack.
- Go to system Preferences > Sound > Input and choose Line In as input device.
- Insert headphone, combojack pop-up will appear, select headset from the list.
- Still having an issue, try disabling ambient noise reduction.
- Done. Enjoy..!

## iServices
For iServices fix click [here.](https://dortania.github.io/OpenCore-Post-Install/universal/iservices.html)

# NOTE:- OPEN CONFIG.PLIST AND INSERT APPROPRIATE PLATFORM INFO (SERIAL, UUID ETC) BEFORE INSTALLING.

## Additional:- Touchpad will probably not work during installation. Keep Usb Mouse handy.

## Credits
- Special Thanks to [Hasodikis](https://github.com/Hasodikis).
- Thanks to [Acidanthera](https://github.com/acidanthera) for providing [AppleALC](https://github.com/acidanthera/AppleALC), [AppleSupportPkg](https://github.com/acidanthera/AppleSupportPkg), [HibernationFixup](https://github.com/acidanthera/HibernationFixup), [Lilu](https://github.com/acidanthera/Lilu), [OcBinaryData](https://github.com/acidanthera/OcBinaryData), [OpenCorePkg](https://github.com/acidanthera/OpenCorePkg), [VirtualSMC](https://github.com/acidanthera/VirtualSMC), [VoodooInput](https://github.com/acidanthera/VoodooInput), [VoodooPS2](https://github.com/acidanthera/VoodooPS2), and [WhateverGreen](https://github.com/acidanthera/WhateverGreen).
- Thanks to [RehabMan](https://github.com/RehabMan) for providing [EAPD-Codec-Commander](https://github.com/RehabMan/EAPD-Codec-Commander), [EFICheckDisabler](https://github.com/RehabMan/hack-tools/tree/master/kexts/EFICheckDisabler.kext), [OS-X-Clover-Laptop-Config](https://github.com/RehabMan/OS-X-Clover-Laptop-Config), [OS-X-Null-Ethernet](https://github.com/RehabMan/OS-X-Null-Ethernet), and [SATA-unsupported](https://github.com/RehabMan/hack-tools/tree/master/kexts/SATA-unsupported.kext).
- Thanks to [VoodooI2C](https://github.com/VoodooI2C) for providing [VoodooI2C](https://github.com/VoodooI2C/VoodooI2C).
- Thanks to [ComboJack](https://github.com/hackintosh-stuff/ComboJack)
- Thanks to [Me](https://github.com/itsdrnoob) for fixing everything xDxD.