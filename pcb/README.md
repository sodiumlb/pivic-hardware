# PIVIC PCB Notes
The PCB package consists of EasyEDA SCH schematics and PCB board design source files, and Gerber, BOM and PickAndPlace production files for PCBA.

## BOM Notes
> ***Note*** PCBA online order services may raise an error that J1, R4 and U3 devices are missing in the BOM. This can safely be ignored.
 
The following components are intentionally excluded from the BOM
1. J1 - Serial debug terminal header. Not needed for normal use
2. R4 - Flash pull-up resistor. A 10k pull-up may be needed for different flash chips.
3. U3 - The VIC-1 DIP-40 pin layout. IC pin substitues (pin-headers) must be installed manually after PCBA.

