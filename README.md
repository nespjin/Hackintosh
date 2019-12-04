# Hackintosh

Repositories for Hackintosh’s Tools and Drivers

### BBS
- tonymacx86: [https://www.tonymacx86.com/](https://www.tonymacx86.com/)
### BootLoader

### Clover：[https://github.com/Dids/clover-builder/releases](https://github.com/Dids/clover-builder/releases ) and [https://github.com/CloverHackyColor/CloverBootloader/releases](https://github.com/CloverHackyColor/CloverBootloader/releases)

#### How to install Clover

  > 1.Install Clover on EFI partition by Clover APP on MacOSX platform。

  > 2.Download the cloverx64.efi file to replace the CLOVER folder file of the same name, copy it to the BOOT folder and rename it bootx64.efi

### Drivers (Kext)

- Lilu: [https://github.com/acidanthera/Lilu/releases](https://github.com/acidanthera/Lilu/releases)
> The base package for many of the following related drivers, many of the following related drivers must have this driver in order to work

- VirtulSMC:[https://github.com/acidanthera/virtualsmc/releases](https://github.com/acidanthera/virtualsmc/releases)
> Alternative to FakeSMC

- AppleALC:[https://github.com/acidanthera/APPLEALC/releases](https://github.com/acidanthera/APPLEALC/releases)
> The Driver for Audio，need to set the sound card id，replace the VoodooHDA

- WhatEverGreen:[https://github.com/acidanthera/WHATEVERGREEN/releases](https://github.com/acidanthera/WHATEVERGREEN/releases)
> Graphic card, brightness, video and other drivers are integrated with this, is a very important driver

- CPUFriend:[https://github.com/acidanthera/CPUFriend/releases](https://github.com/acidanthera/CPUFriend/releases)
> CPU frequency

- AirportBrcmFixup:[https://github.com/acidanthera/AirportBrcmFixup/releases](https://github.com/acidanthera/AirportBrcmFixup/releases)
> Wireless network card and bluetooth。Usually a specific model is required

- VoodooPS2:[https://github.com/acidanthera/VoodooPS2/releases](https://github.com/acidanthera/VoodooPS2/releases)
> Keyboard, touch pad, little red dot drive