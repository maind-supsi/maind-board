# MAIND BOARD
PCB board for the Arduino Nano family developed during the [MAInD - Master of Arts in Interaction Design](https://maind.supsi.ch/master-interaction-design/) at [SUPSI - University of Applied Sciences and Arts of Southern Switzerland](https://www.supsi.ch/home_en.html).

The MAInD board has been developed as an educational tool supporting the ongoing transition to using MicroPython with Arduino.

The MicroPython codes and libraries and the project developed by the MAInD students are documented in this repository:

:point_right: [MAInD Master SUPSI - Micropython with Arduino](https://master-interaction-design.notion.site/MAInD-Master-SUPSI-Micropython-with-Arduino-772c06aa0dee4c35a509a4daac6c72dd).


## MAIND board V1.0 (offical release)

![alt text](https://github.com/maind-supsi/maind-board/blob/main/MAIND-board-V1.0/PCB_MAIND_board_V1.0.png "PCB MAIND board V1.0")

This is the first official release after two years of development and testing during Tangible Interfaces and Physical Computing courses at the MAInD.

The fixes and improvements consist of labeling fixes, pin swapping, and the final silkscreen on the back.


## MAIND board V0.2

![alt text](https://github.com/maind-supsi/maind-board/blob/main/MAIND-board-V0.2/PCB_MAIND_board_V0.2.png "PCB MAIND board V0.2")

The second version of the board is a great improvement with more connections and an external USB-C power connection for the Neopixels and Servo motors.

All the grove connectors have also a second row with standard female headers for better wiring flexibility.

The I2C connectors can be individually set to 5V or 3.3V with the soldering pads.

It can host any of the Arduino Nano 33 family boards.

It is required to solder the "VUSB" pad on the Arduino board to power it from the USB-C connector.

The 5V rail features 600uF of integrated total buffer capacity to properly provide power for Neopixels and Servo motors.



## MAIND board V0.1

![alt text](https://github.com/maind-supsi/maind-board/blob/main/MAIND-board-V0.1/PCB_MAIND_board_V0.1.png "PCB MAIND board V0.1")

The first version of the board was developed for MAIND edition 2021-2022.

The board features connectors for the grove system, a power header with 5V, 3.3V and GND, and a connection for a Neopixel strip or a Servo motor.

The side slots allow great mounting flexibility.

It can host any of the Arduino Nano 33 family boards.
