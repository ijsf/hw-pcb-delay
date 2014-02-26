# PCB delay line prototype board

This PCB has been designed as an experimental prototype board containing copper PCB traces in microstrip formation with a controlled tranmission propagation delay (Tpd).

This board has been designed using Cadence ORCad Capture and Cadence Allegro PCB Editor 16.6.

## Version history

### Revision 1.0

This revision contains two copper traces with an estimated Tpd of 1ns (`DL1`) and 2ns (`DL2`).

## Remarks

### Allegro Gerber generation

In order to generate the appropriate Gerber layers, use the provided `ns_gerber.il` script. Use the following commands in Allegro:

	skill
	load("...path to ns_gerber.il")
	ns_gerber

