# prrrrint
My PrintNC setup running on linuxcnc 2.8, involving modified Probe screen v2 which now works. 

Machine itself is a standard size PrintNC build with stepperonline DM556 drivers.

Issues remaining with probe screen:
1. The jog buttons in probe screen don't work. I use the regular gmoccapy jogging screen
2. The probe screen occasionally loses workpiece height between the PrintNC running different gcodes. To make sure, I double check each time before running a program that the workpiece height box is not "0"

The branch "Mesa 7i76e" has a working setup Gmoccappy + Probe Screen

The branch "Mesa- Probe basic" has a working setup with "Probe basic" GUI running on Mesa 7i76e. Some of the subroutines are modified for tool lenght measurement with manual toolchange.
