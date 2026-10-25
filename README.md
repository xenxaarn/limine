# Limine Bootloader custom fork, modified to look clean & modearn

A minimal, x86_64-focused fork of the Limine bootloader.

## Configuration & Build
Configured specifically for legacy BIOS and UEFI x86_64 booting:
```bash
./bootstrap
./configure --enable-bios --enable-bios-cd --enable-uefi-x86-64 --enable-uefi-cd
make
