# Known Issues
- Silk swapped for R17 and C19
- Alignment holes for J1 are too small
- Add paste aperatures for SD-Card socket (J5)
- Add paste aperatures for GND hole pads on USB connector (J1)
- Add buffers on UART0 (my external tools are back-powering through the F1C200s 
ESD diodes)
- Remove UART0 RX/TX from LEDs and replace with other GPIO (LEDs are always on 
and 115200 baud is too fast for any meaningful blinking)
- Button or jumper to enter FEL Mode by holding SPI0_CS low.
