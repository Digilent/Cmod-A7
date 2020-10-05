# Cmod A7 Root Repository

## Cmod A7-15T XADC Demo

### Description

This branch contains sources for the CmodA7-15T XADC Demo.

This project is a Vivado demo using the Cmod A7-15T's analog-to-digital converter ciruitry, push buttons and the RGB LED, written in Verilog. 
When programmed onto the board, voltage levels between 0 and 1 Volts are read off of the JXADC header. The RGB LEDs brightness increases as the voltage increases. 
When BTN1 is pressed, the demo switches the xadc channel 4 to channel 12 that is connected to pin 15 and 16 respectively.

For more information on the Cmod A7-15T XADC Demo, including setup instructions, visit its [Demo Page](https://reference.digilentinc.com/reference/programmable-logic/cmod-a7/demos/xadc) on the Digilent Wiki.

For more information on the Cmod A7, including other demos that may be available, see its [Resource Center](https://reference.digilentinc.com/reference/programmable-logic/cmod-a7/start) on the Digilent Wiki.

### Git Navigation Information

For instructions on how to use this repository with git, and for additional documentation on the submodule and branch structures used, please visit [Digilent FPGA Demo Git Repositories](https://reference.digilentinc.com/reference/programmable-logic/documents/git) on the Digilent Wiki. Note that use of git is not required to use this demo. Digilent recommends the use of project releases, for which instructions can be found in each demo wiki page, linked above.

To see other demos in this repository, see the master branch's [README](https://github.com/Digilent/Cmod-A7).

Some demos do not require some submodules, in these cases, they are still provided to ease switching between demos in git. When unused, the submodule folder is largely empty, except for a readme containing only the heading "Root commit". This demo contains the following submodules:

| Submodule | Used by this demo |
|-----------|-------------------|
| HW        | Yes         |
| SW        | No         |

This demo was moved into this repository during 2020.1 updates. Its history prior to these updates can be found in its old repository, linked below:
* https://github.com/Digilent/Cmod-A7-15T-XADC

### Requirements

The following are required for use of this demo. For more information on how to get any hardware or software you may be missing, see the Demo Page, linked above.

* Cmod A7-15T
* Vivado 2020.1 Installation
* MicroUSB cable
* Wires and a circuit to measure