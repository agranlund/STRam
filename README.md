
[fixing with a bodge wire]: /board_fix.jpg


# Atari 520ST(M)<br>4MB RAM Expansion

*Tested on* ***C070243 Rev.I*** *, your mileage may vary.*

---

### Important

1. The board needs **[fixing with a bodge wire]**

2. The expansion board **must** be installed<br>
   directly onto the motherboard.<br>

   Using sockets **won't** leave enough<br>clearance for the keyboard

---

### BOM

|    |    Component     | Value | Size | Package |
|:--:|:----------------:|:-----:|:----:|:-------:|
|    | **C1** - **C6**  | 100nF | 0805 |         |
|    | **R1** - **R2**  |   68Ω | 0805 |         |
|    |      **R3**      |   33Ω | 0805 |         |
| 2x | **5118160 DRAM** |       |      |   SOJ42 |

---

### Installation

- De-solder the existing RAM.

- Solder the expansion board in place.

- Solder the four wires from the expansion<br>
  board to the motherboard.

  Signals: **MAD9**, **CAS1L**, **CAS1H**, **RAS1**

  **MAD9** can usually only be found on the **MMU**

  The **CAS** & **RAS** pins can be soldered to on the<br>
  underside of the motherboard as well as,<br>
  ***on some boards***, on the topside as well.

    |  Name | MMU Pin |
    |:-----:|:-------:|
    |  RAS1 |    18   |
    | CAS1L |    21   |
    | CAS1H |    22   |
    |  MAD9 |    64   |
