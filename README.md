# QCOW2 to USB Flasher

A simple and safe Bash script for converting and writing virtual machine disk images in **qcow2** format directly to physical USB storage devices (pendrives, SD cards, external drives).

## Prerequisites

To work properly, the script requires the **`qemu-utils`** package (`qemu-img`), which handles the conversion from the qcow2 format to the raw disk image format.

You can install it on Debian/Ubuntu/Mint-based systems using:
```bash
sudo apt update
sudo apt install qemu-utils

chmod +x Nagranie
sudo ./Nagranie
