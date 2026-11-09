899
# Apple II Plus RFI Rev. 2 Clone

This board is a clone of the Apple II Plus RFI motherboard. It is designated as "Rev. 2"
to distinguish it from the original Apple II Plus RFI motherboard (which we refer to as "Rev. 0")
and the board from ReActiveMicro (which we refer to as "Rev. 1"). It was created
based on Mike Willegal’s Apple II Rev. 0 replica board.
While it is not 100% identical to the Apple or ReActiveMicro boards, it functions
exactly like an Apple II Plus RFI. The design has been verified against the
original schematics but has not been physically tested. USE AT YOUR OWN RISK.

## Key Changes



All ROMs have been replaced with 28C16 chips.

8T97 has been replaced with 74LS367

8304 has been replaced with 74LS245

A second "color kill" circuit has been added, triggered by the AN2 signal.

A 5–50 pf trimmer capacitor has been added in series with the 14.318 MHz crystal.
(This was done because the original crystal is difficult to source; the trimmer
is used to fine-tune the color frequency.)


![image](https://github.com/frubem/AppleIIPlus-Motherboard/blob/main/Images/image1.png)
![image](https://github.com/frubem/AppleIIPlus-Motherboard/blob/main/Images/image2.png)
