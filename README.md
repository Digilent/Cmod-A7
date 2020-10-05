# Cmod A7 Root Repository

## Cmod A7-15T Out-of-Box Demo

### Description

This branch contains sources for the Cmod A7-15T Out-of-Box Demo.

This project demonstrates how to use the Cmod A7-15T's Artix 7 FPGA's Microblaze processor with the SRAM, LED's, RGB LED's, Pushbuttons and the USB UART bridge. Vivado is used to build the demo's hardware platform, and Vitis is used to program the bitstream onto the board and to build and deploy a C application.

Whenever the demo is started from Vitis, the board will go through a memory test and will print out the result to the serial terminal. Whenever one of the buttons is pressed, the line “Button Pressed” is sent. Every time BTN1 is pressed, the LED state changes. The user LEDs create a 2 bit binary counter that increments every time the button is pressed. The RGB LED smoothly transitions between colors.

For more information on the Cmod A7-15T Out-of-Box Demo, including setup instructions, visit its [Demo Page](https://reference.digilentinc.com/reference/programmable-logic/cmod-a7/demos/oob) on the Digilent Wiki.

For more information on the Cmod A7, including other demos that may be available, see its [Resource Center](https://reference.digilentinc.com/reference/programmable-logic/cmod-a7/start) on the Digilent Wiki.

### Git Navigation Information

For instructions on how to use this repository with git, and for additional documentation on the submodule and branch structures used, please visit [Digilent FPGA Demo Git Repositories](https://reference.digilentinc.com/reference/programmable-logic/documents/git) on the Digilent Wiki. Note that use of git is not required to use this demo. Digilent recommends the use of project releases, for which instructions can be found in each demo wiki page, linked above.

To see other demos in this repository, see the master branch's [README](https://github.com/Digilent/Cmod-A7).

Some demos do not require some submodules, in these cases, they are still provided to ease switching between demos in git. When unused, the submodule folder is largely empty, except for a readme containing only the heading "Root commit". This demo contains the following submodules:

| Submodule | Used by this demo |
|-----------|-------------------|
| HW        | Yes         |
| SW        | Yes         |

This demo was moved into this repository during 2020.1 updates. Its history prior to these updates can be found in its old repository, linked below:
* https://github.com/Digilent/Cmod-A7-15T-OOB

### Requirements

The following are required for use of this demo. For more information on how to get any hardware or software you may be missing, see the Demo Page, linked above.

* Cmod A7-15T
* Vivado 2020.1 Installation
* Serial Terminal Emulator
* MicroUSB cable