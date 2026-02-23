# pivic-hardware
Hardware design files for the PIVIC MOS VIC-I 6560/6561 replacement project

## Related projects
[User Documentation](https://github.com/sodiumlb/pivic-docs)
[Firmware](https://github.com/sodiumlb/ocula-pivic-firmware)

## Important notes
PIVIC hardware has been designed for low cost assembled production. It is not recommended to attempt manual assembly of anything other than through-hole components (headers, connectors).

The DVI adapter and cable is optional.

## Main OCULA PCB
See pcb directory for design files for PCB production and PCBA of all surface mounted components. 

It is recommended to use stacking pin-headers to create flat pins on PIVIC to allow best possible socket compatibility. Alternatively turned pin headers provide the most robust and easiest to assemble IC pin alternative, but these will damage wiper based sockets.

## DVI adapter
The DVI adapter is optional. See the dvi-adapter for PCB and 3D print adapter design files. The required cable spec is FFC, 20cm, 20pin, 0.5mm pitch, reverse direction (contacts are on opposing side on each end).

The 3D printed VIC-20 adapter is designed to fit screwless in the cassette or user port.

## Using stacking pin row headers to create IC pins
While there are many options for adding IC pins to PCBs, the solution that has provided the best low-cost way to get close to compatible with original IC pins, is to create them from long pinned PCB stacking headers. These have flat pins in a more spring-like metal that serves this alternative application well. 

This example shows 1x20 row 11mm stacking pin row headers on OCULA, but same applies for the PIVIC.
![Example stacking pin headers](https://github.com/sodiumlb/ocula-hardware/raw/main/images/pin_row_1x20_11mm_stacking.jpg)
![OCULA low-profile pin jigg](https://github.com/sodiumlb/ocula-hardware/raw/main/images/ocula_low_profile_jigg.jpg)
![OCULA low-profile pins](https://github.com/sodiumlb/ocula-hardware/raw/main/images/ocula_low_profile_pins.jpg)
![OCULA low-profile mounted in system](https://github.com/sodiumlb/ocula-hardware/raw/main/images/ocula_low_profile_in_system.jpg)

# Disclaimer
PIVIC is an open source project by and for itsﬂ users. It is provided AS-IS. For more information see each sub-project license agreement.