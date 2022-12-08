## Not Actively Maintained!

# [SUCCESS] Mi-Notebook-14-Hackintosh (Ventura 13.0)
Tested on i3 & i5 models, yet to test on i7(horizon)



## Laptop Specs

| Specifications | Detail                                                  |
| ------------------- | ------------------------------------------- |
| Laptop model      | Mi Notebook 14 2020     |
| Processor           | Intel Core i5-10210U / i3-10110U        |
| Memory              | 8GB Samsung DDR4 2666MHz              |
| Hard Disk           | SATA SSD Controller                |
| Integrated Graphics | Intel UHD Graphics 620                     |
| Sound Card          | Realtek ALC256                             |
| Wireless Card       | Intel Wireless AC 9462                        |
| Touchpad            | I2C ELAN2304                               |


## What Works
- Intel UHD Graphics
- Wifi (Use heliport if inbuilt wifi is buggy).
- Bluetooth
- Touchpad including Gestures
- Keyboard
- HDMI
- Webcam (Tested on i3 model)
- Audio (Both Speaker and Headphones)
- Microphone (Headphone & Bluetooth. Headphone fix below)
- Battery Manager
- Brightness
- iServices
- Almost Everything Important xD.

## What's Broken
- Internal microphone
- Inbuilt wifi is buggy sometimes (won't connect).
- Touchpad gestures (Three-finger swipe back, pinch zoom) randomly stop working for a few seconds once in a while (others like mission control gestures are not affected).
- AirDrop
- You tell me :)

## Microphone Fix (Headset)
- Download Combojack [here.](https://github.com/hackintosh-stuff/ComboJack)
- Follow the documentation to install combojack.
- Insert headphone, combojack pop-up will appear, select headset from the list.
- Still having an issue, try disabling ambient noise reduction.
- Done. Enjoy..!

# NOTE:- OPEN CONFIG.PLIST AND INSERT APPROPRIATE PLATFORM INFO (SERIAL, UUID ETC) BEFORE INSTALLING.
## Additional:- Internal keyboard doesn't work in opencore boot picker. Use external keyboard.


## Credits
- Thanks to [Acidanthera](https://github.com/acidanthera) for providing [AppleALC](https://github.com/acidanthera/AppleALC), [AppleSupportPkg](https://github.com/acidanthera/AppleSupportPkg), [HibernationFixup](https://github.com/acidanthera/HibernationFixup), [Lilu](https://github.com/acidanthera/Lilu), [OcBinaryData](https://github.com/acidanthera/OcBinaryData), [OpenCorePkg](https://github.com/acidanthera/OpenCorePkg), [VirtualSMC](https://github.com/acidanthera/VirtualSMC), [VoodooInput](https://github.com/acidanthera/VoodooInput), [VoodooPS2](https://github.com/acidanthera/VoodooPS2), and [WhateverGreen](https://github.com/acidanthera/WhateverGreen).
- Thanks to [RehabMan](https://github.com/RehabMan) for providing [EAPD-Codec-Commander](https://github.com/RehabMan/EAPD-Codec-Commander), [EFICheckDisabler](https://github.com/RehabMan/hack-tools/tree/master/kexts/EFICheckDisabler.kext), [OS-X-Clover-Laptop-Config](https://github.com/RehabMan/OS-X-Clover-Laptop-Config), [OS-X-Null-Ethernet](https://github.com/RehabMan/OS-X-Null-Ethernet), and [SATA-unsupported](https://github.com/RehabMan/hack-tools/tree/master/kexts/SATA-unsupported.kext).
- Thanks to [VoodooI2C](https://github.com/VoodooI2C) for providing [VoodooI2C](https://github.com/VoodooI2C/VoodooI2C).
- Thanks to [ComboJack](https://github.com/hackintosh-stuff/ComboJack)
- Thanks to [Hasodikis](https://github.com/Hasodikis) (OC 0.6.4).
- Thanks to [lietxia](https://github.com/lietxia) (OC 0.8.6).
- Thanks to [Me](https://github.com/itsdrnoob) for fixing everything xDxD.