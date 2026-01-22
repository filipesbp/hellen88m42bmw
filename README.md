To replace Motronic 1.7 for M42 engine

Pinout of hellen88bmw rev.c changed:

Added JP15 connected do GND 

Added JP69 JP70 to IN_KNOCK1_RAW and IN_KNOCK2_RAW

Removed KNOCK_RAW1 and 2 because proximity of JP69 JP70 does same.

Added CR24 to pin 74

Added CR25 to pin 76.

Removed CR9 because proximity of JP46 does the same.

Part of https://github.com/andreika-git/hellen-one family
Modification of https://github.com/rusefi/hellen88bmw board

Wiring:

 Ground Pins - 6, 15, 28, 34, (39), (40), 41, 43, (44), (45), 55, 71, 76, (84).
 
   () Not wiring harness but available on ECU.
   
 ECU Power from switch relay 10A fuse Pin - 56.
