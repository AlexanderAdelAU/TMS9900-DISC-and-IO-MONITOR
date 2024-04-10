# TMS9900-DISC MONITOR

The Memory Resident Monitor is responsible for providing the core IO and DISC interfaces required to the Single Board Computer.   
For example all the XOP Defintions are defined, such as CALL, PUSH, POP, RET etc as well as all the interfaces routines required
to interface to a Western Digital type Floppy Disc Controller (FDC 1797), if implemented.   The Disc IO provides a basic BIOS but relies on a
CP/M type DOS system to be fully functional. 

The Monitor is unlikely to be immediately reusable in your current system unless you use a WD1797 Floppy Disc Controller, but some to the routines can be ported as needed.
