# Switchport-TKL-PCB

Hi all,

This is still a work-in-progress PCB. The technical goal is to improve TKL PCB compatibility via hot-swappable connectors. 

Traditional TKL PCBs usually only have one on-board USB connector and a female wire-to-wire connector, yet due to cross-compatibility issues with TKL cases/plates which can otherwise use assemblies, transferring TKL builds between cases often requires the permanent removal (via snapping) of the on-board USB connector or is entirely impossible.

To these ends, I propose containing individual USB connectors on daughterboards which can be fastened to the main PCB with non-permanent tools (screws). 

The current board utilizes an RP2040.

Layout Compatibility:
- F12/13
- 6.25U/7U

Connectors:
- JST SH-4/Molex Pico-EZMate
- USB-C/Mini USB

Lighting:
- Per-key THT LED
- Indicator THT LED
- Backlit SMD LED
