# Cmod A7 Root Repository

## Cmod A7-15T GPIO Demo

### Description

This branch contains sources for the Cmod A7-15T GPIO Demo.

This VHDL project demonstrates the basic use of most of the Cmod-A7's general purpose I/O.

* The two user LEDs are tied to the two push buttons
* The RGB LED is set to smoothly change colors
* The UART bridge outputs a beginning message and a status message whenever a button is pressed

For more information on the CmodA7-15T GPIO Demo, including setup instructions, visit its [Demo Page](https://reference.digilentinc.com/reference/programmable-logic/cmod-a7/demos/gpio) on the Digilent Wiki.

For more information on the Cmod A7, including other demos that may be available, see its [Resource Center](https://reference.digilentinc.com/reference/programmable-logic/cmod-a7/start) on the Digilent Wiki.

### Git Navigation Information

For instructions on how to use this repository with git, and for additional documentation on the submodule and branch structures used, please visit [Digilent FPGA Demo Git Repositories](https://reference.digilentinc.com/reference/programmable-logic/documents/git) on the Digilent Wiki. Note that use of git is not required to use this demo. Digilent recommends the use of project releases, for which instructions can be found in each demo wiki page, linked above.

To see other demos in this repository, see the master branch's [README](https://github.com/Digilent/Cmod-A7).

Some demos do not require some submodules, in these cases, they are still provided to ease switching between demos in git. When unused, the submodule folder is largely empty, except for a readme containing only the heading "Root commit". This demo contains the following submodules:

| Submodule | Used by this demo |
|-----------|-------------------|
| HW        | Yes        |
| SW        | No         |

This demo was moved into this repository during 2020.1 updates. Its history prior to these updates can be found in its old repository, linked below:
* https://github.com/Digilent/Cmod-A7-15T-GPIO

### Requirements

The following are required for use of this demo. For more information on how to get any hardware or software you may be missing, see the Demo Page, linked above.

* Cmod A7-15T
* MicroUSB Programming Cable
* Vivado 2020.1 installation
