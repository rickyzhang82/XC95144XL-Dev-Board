# XC95144XL Dev-Board

![](https://github.com/DL2DW/XC95144XL-Dev-Board/blob/main/Images/XC95144XL-Devboard.jpg)



I've designed a small development board to hold a Xilinx XC95144XL in TQFP-100 format. Additionally I have a voltage regulator for the 3.3V of the CPLD and a 50MHz oscillator.

All I/Os are led out as female headers. The distance between the individual blocks is chosen so that an adapter board with a pitch of 2.54mm can be plugged on top without any problems.

Or use with appropriate jumper Wires with a breadboard. 

The JTAG is designed in today's standard 2.54mm pitch as a simple IDC female connector. 



# Building

The construction is kept quite simple, and only a few parts are needed. I have omitted switches and buttons. Only two LEDs are present, but they only indicate the 5V and 3.3V power supply.

The board is preferably intended to be operated at 5V, since the I/Os of the Xilinx XC9500XL series are also 5V tolerant.

The 5V can be supplied at the lower connector strip. Additionally, 3.3V can also be taken from there, e.g. to connect an SD card reader.

The circuit board viewed from above:

![](https://github.com/DL2DW/XC95144XL-Dev-Board/blob/main/Images/XC95144XL-Devboard-3D.jpg)



# BOM

Here is the list of components needed. I have chosen the manufacturers as examples. Of course, compatible components from other manufacturers can also be selected. Only the Xilinx CPLD cannot be replaced by other types.



| Quantity | Designator                       | Manufacturer       | Manufacturer  Part | Description                                      |
| -------- | -------------------------------- | ------------------ | ------------------ | ------------------------------------------------ |
| 2        | C1,  C2                          | KEMET              | C0805C106K8RACTU   | Kemet  C0805CxxxK8RACTU Series H=1.4mm           |
| 8        | C3,  C4, C5, C6, C7, C8, C9, C10 | KEMET              | C0603C104J3RACTU   | CAP  100nF SMD 0603 C0603C104J3RACTU             |
| 5        | CN1,  CN2, CN4, CN5, CN6         | Harwin             | M20-7831042        | Female  Pin Header 02x10 Straight P2.54mm H8.5mm |
| 1        | CN3                              | Samtec             | TSS-107-01-G-D     | IDC  Header 2x7 P2.54mm Straight                 |
| 1        | D1                               | Wurth  Electronics | 150060SS55040      | LED  Red SMD 0603                                |
| 1        | D2                               | Wurth  Electronics | 150060BS55040      | LED  Green SMD 0603                              |
| 2        | R1,  R2                          | Yageo              | RC0603FR-071KL     | 1k  Ohm R 0603 SMD                               |
| 1        | U1                               | Exar               | SPX5205M5-L-3-3/TR | SOT-23-5                                         |
| 1        | U2                               | Xilinx             | XC95144XL-7TQ100C  | TQFP-100  P0.5mm XC95144XL-7TQ100C               |
| 1        | X1                               | EuroQuartz         | XO53050UITA        | 50.000MHZ  Oscilator EuroQuartz XO53050UITA      |



If you liked my project, I would be very happy about a small coffee donation.

[![ko-fi](https://www.ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/R6R62T6RN)



# License

The contents of this repository, with the exception of the Docs and Software directories, are released under the following license:

- the "Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License" (CC BY-NC-SA 4.0) full text of this license is included in the [LICENSE.CC-NC-BY-SA-4.0](https://github.com/DL2DW/XC95144XL-Dev-Board/blob/main/LICENSE.CC-NC-BY-SA) file and a copy can also be found at https://creativecommons.org/licenses/by-nc-sa/4.0/
