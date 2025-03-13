To replace Motronic 1.7 for M42 engine

Pinout of hellen88bmw rev.c changed:

Added JP15 connected do GND

Added JP69 JP70 to IN_KNOCK1_RAW and IN_KNOCK2_RAW

Removed KNOCK_RAW1 and 2 because proximity of JP69 JP70 does same.

Added CR24 to pin 74

Added CR25 to pin 76.

Removed CR9 because proximity of JP46 does same.

Part of https://github.com/andreika-git/hellen-one family
Modification of https://github.com/rusefi/hellen88bmw board

