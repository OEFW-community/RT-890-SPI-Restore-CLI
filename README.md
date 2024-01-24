# RT-890-SPI-Restore-CLI
RT-890-SPI-Restore-CLI (c) Copyright 2023 Dual Tachyon

## Usage
```
RT-890-SPI-Restore-CLI.exe -l                        List available COM ports
RT-890-SPI-Restore-CLI.exe -p COMx -f firmware.bin   Restore SPI backup
```

## How it works
This Windows CLI utility allows to restore SPI backup made with [radtel-rt-890-flasher](https://github.com/OEFW-community/radtel-rt-890-flasher).

It restores only area used by stock firmware
```
Start: 0x000000, End: 0x2cffff, Size: 0x2d0000
Start: 0x2d0000, End: 0x2f7fff, Size: 0x28000
Start: 0x2f8000, End: 0x319fff, Size: 0x22000
Start: 0x31a000, End: 0x31bfff, Size: 0x2000
Start: 0x3b5000, End: 0x3befff, Size: 0xa000
Start: 0x3bf000, End: 0x3bffff, Size: 0x1000
Start: 0x3c1000, End: 0x3cafff, Size: 0xa000
Start: 0x3d8000, End: 0x3e1fff, Size: 0xa000
Start: 0x31c000, End: 0x3b4fff, Size: 0x99000
```
