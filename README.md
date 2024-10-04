# PaybackOS

## What is PaybackOS

PaybackOS is a lightweight OS, meant for CLI use, it plans to have a ELF program loading, and a disk driver for FAT32 or any filesystem for that matter, and a disk reading function to get the raw data.

## Install guide
First install grub-mkresuce (preinstalled on debian 12), grub-pc-bin (on BIOS machines this is already here will not screw up a UEFI machine), i686-elf-gcc, i686-elf-binutils, mtools, xorriso optionally qemu-system-x86_64, git, make, then run make and if you want to run in qemu make run, to install the i686-elf tools use brew like this
```bash
brew install i686-elf-gcc
```
this will also install binutils then for the other tools install it like this

```bash
sudo apt install grub-pc-bin mtools xorriso qemu-system-x86 git make
```
then run
```bash
git clone https://github.com/PaybackOS/PaybackOS
cd PaybackOS
```
This will clone PaybackOS, now run this to build and run it.
```bash
make
make run
```
