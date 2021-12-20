----------------------------------------------------------------------------
4MB RAM expansion for Atari 520ST(M)
(c)2020, Anders Granlund
----------------------------------------------------------------------------
Tested on a C070243 Rev.I motherboard, your mileage may vary.
----------------------------------------------------------------------------


----------------------------------------------------------------------------
IMPORTANT:
----------------------------------------------------------------------------
1)
There is a misstake on this board that needs fixing with
a bodge wire. See "board_fix.jpg" for where to solder
that wire.

2)
The board must be soldered directly to the motherboard.
Do not install sockets as there will not be enough clearance for the keyboard.



----------------------------------------------------------------------------
BOM:
----------------------------------------------------------------------------
C1-C6 = 100nF (0805 size)
R1-R2 = 68 ohm (0805 size)
R3 = 33 ohm (0805 size)
2x 5118160 DRAM's in SOJ42 package


----------------------------------------------------------------------------
HOWTO:
----------------------------------------------------------------------------

* Desolder the existing RAM and solder the new board in
place. 

* Solder the bodge wire as seen in "board_fix.jpg"

* Solder the four wires from the RAM board header
to the motherboard (MAD9, CAS1L, CAS1H, RAS1)

All four signals can be found on the MMU and you can solder
to the socket pins on the underside of the motherboard.
Alternatively you may find solder points for CAS1L,CAS1H,RAS1
on the topside on some motherboards but MAD9 is normally only
found on the MMU.

MMU pins:
RAS1  = 18
CAS1L = 21
CAS1H = 22
MAD9  = 64
