# ONE_MIX_YOGA_3_PRO_HACKINTOSH
Project to implement macOS support on the OMY3

Full support for macOS 10.14.0 - 12.6.x (Only tested on Catalina & Monterey...Not all EFI releases work with all macOS versions so please confirm you have installed the correct EFI for the OS version you are trying to run)

If you see anything that could be added or changed don't hesitate to make a pull request.

![MacMix 3 Monterey](/MONTEREY.png)

##
## Compatibility
This EFI was created usuing the 10510Y version...it is assumed to be working with all other variants including non pro as well but testers are welcome

## Full Instruction Guide

### [Chapter 1) Quick Start Install](/1-QuickStart.md)
### [Chapter 2) Changing the Display Orientation](/2-Orientation.md)
### [Chapter 3) Enabling HiDPI Mode](/3-HiDPI.md)
### [Chapter 4) Setting Resolutions Over 1080p](/4-1080p&up.md)
### [Chapter 5) Booting Other OS's](/5-AlternativeOperatingSystems.md)


## What works 

- Graphic Acceleration (4K support still needs testing)
- OpenCore Boot-Loader orientation corrected to landscape mode
- Bluetooth
- Brightness(Both Buttons and slider are reversed u fortunately)
- Audio
- Power Management
- Battery 
- USB
- Keyboard
- Sleep / Wake
- Fully Automated FAN
- TrackPoint 
- HDMI / Type-C
- Windows boot from OpenCore
- TouchScreen / Stylus
- Internal Wi-Fi 
- FileVault Supported
- Recovery Supported
- Sleep Button Support

## Planned Features

- Auto rotate screen

## What doesn't work

- Fingerprint Sensor
- Card Reader
- Accelerometer

## Known Issues (all intermittent)

- Black Screen wake
- Shut Down Reboot
- Sleep button broken


## Credits
Special thanks to my Minibook bro [@Balopez](https://github.com/balopez83/One-Mix-3-Hackintosh) for all of his assistance <br>
[Dortania's Hackintosh guide](https://dortania.github.io/OpenCore-Install-Guide/) <br>
[One-Netbook for making the great Yoga 3](https://www.1netbook.com/) <br>
