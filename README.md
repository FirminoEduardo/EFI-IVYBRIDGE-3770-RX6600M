# This is my first EFI, please, leave a feedback.

# Taicon B75 + I7 3770 + RX 6600M

**Latest working macOS**: Monterey 12.6.3
<br>
**Current OpenCore**: 0.8.9

## Complete hardware specs
- Intel i7 3770 @ Stock 4c/8t
- Taicon B75
- RX 6600M - 51risc 8gb
- 2x 8gb 1600mhz Kllisre DDR3

## What works
- macOS Monterey
- Audio
- HDMI/DP (in dGPU - Works OOB)
- All USB ports
- Everything iCloud related (Drive, iMessage, Facetime, unlock with Apple Watch, etc)
- Temperature monitoring for everything except GPU
- DRM content (Netflix, ATV+, Airplay 2 mirroring etc)
- Shutdown/Reboot/Update to newer macOS builds over time

## What doesn't work
- Sleep? Never got the chance to test it, my hackintosh is up 24/7

## Kexts used:
- AppleALC.kext
- Lilu.kext
- RealtekRTL8111.kext
- SMCSuperIO.kext
- SMCProcessor.kext
- VirtualSMC.kext
- WhateverGreen.kext

## Thanks/Credits
- [Opencore Team](https://dortania.github.io/getting-started/)
- [BASE EFI - for 11th Intel Gen - Rocket Lake](https://github.com/luchina-gabriel/BASE-EFI-INTEL-DESKTOP-11THGEN-ROCKET-LAKE)
- tonymacx86.com - in special @etorix and @CaseySJ

## Discord - Universo Hackintosh
- [Access Discord](https://discord.universohackintosh.com.br)
