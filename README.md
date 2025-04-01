# CANTester2
Connection tester for various cables + a CAN bus terminator resistance tester

## Connection Tester
Tester for M-M cables for the following connectors commonly used in HKU Robocon robots:
- 4P4C
- Picoblade 6P
- 2.54mm 7P
- JST GH 4P & 7P
- JST XH 2, 3, 4P 
Turns on LEDs on the transmit side in sequence and sends the signal through the connected cable. If the cable is connected properly, all the LEDs on the receiver should turn on in the same order. 
### Instructions
1. Plug both sides of your cable (Transmit & Receive)
2. The lights marked 1-8 on both sides of the bottom box should turn on in order. If not, your cable is broken.

## Terminator Resistance Tester
Tester for CAN Terminators. LED turns on if the resistance between CANH and CANL (Pins 2 and 3) is 120R. 
### Instructions
1. Plug in your CAN terminator (4P4C with a 120R in the middle two pins).
2. LED in the box will turn on if middle two pins are 120R.
