Tiny Function Generator is a project by Technoblogy.com.

It outputs a Frequency from 1Hz to 5,000Hz. Sinewave, Triangle Wave, SquareWave, pulses, Sawtooth and Noise (no frequency adjustments avaialble on Noise setting)

Rotary encoder increases/decreases Frequency, while the Center Push-Switch selects Waveform.

This circuit is based on his schematic and code -  I added a voltage regulator and Battery Connector (2X CR2032 coin-cell batteries) to make it very portable.

MUST USE the SpenceKonde ATTinyCore library to program the ATTiny85 via the Arduino IDE !!!
(https://github.com/SpenceKonde/ATTinyCore/issues/288) 
Burn the bootloader, then upload the code.
See the Technoblogy.com website for full details !
http://www.technoblogy.com/show?2FCL

The Output is marked "+" , while there are TWO Grounds to choose; one is a "virtual" ground desiganted by "--", and there is a power supply ground designated by "GND" . 
Choose the one best for your project.

Through-hole Power Switch manufacturer part #EG1213 or
DigiKey #EG1906-ND

Battery Holder for two CR2032 Batteries= DigiKey #BH800S-ND .

Rotary Encoder manufacturer part #EN11-HSM1AF15 or DigiKey #987-1188-ND .

OLED is generic 128x32 .

Verified Working.
