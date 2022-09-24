##  Chapter 1) Quick Start Install 
## (Windows or Linux as Primary OS - If you would rather have a traditional macOS install then read Chapter 2 before starting)

1. Create a bootable USB using a macOS installer downloaded from the AppStore or using this [tutorial](https://internet-install.gitbook.io/macos-internet-install/). I recommend using the free "Install Disk Creator" by MacDaddy to create the installer USB.
2. Once install disk is created mount EFI partition and copy either the OC folder to your Install Disk's EFI partition you just mounted
3. Boot into Windows or Linux and resize your partition and format as either NTFS or exFAT for you macOS install. If you are installing on a new device that comes with only an SSD and no EMMC then you must resize your EFI partition or simply wipe and reinstall your operating systems. In order to successfully install and run macOS with our EFI folders you must have at least an EFI partition of 200mb (300mb or greater recommended)
4. Boot from this usb then install macOS on the partition you created (please note...must be installed to ssd as macos does not detect emmc)
5. During first boot, after installing the OS, mount your EFI partition and copy over your OpenCore folder found in the EFI folder on your install usb; you must copy/overwrite the same folders on the same partition located on your SSD.
6. Reboot and change BIOS bootloader order to have OpenCore bootloader as first entry
7. Open your config.plist and generate a new serial number [Tutorial here](https://hackintosher.com/forums/thread/generate-your-own-hackintosh-serial-number-board-serial-number-uuid-mlb-rom-in-clover.306/)
9. Install any additional software and drivers if needed for your specific needs
10. Reboot and enjoy!
