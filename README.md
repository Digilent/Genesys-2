Genesys 2 Keyboard Demo
==========================

Description
-----------
This branch contains sources for the Genesys 2 Keyboard Demo. This project demonstrates a simple use for the Genesys 2's USB-HID and USB-UART ports. The behavior is as follows:
* When the user presses a key on the keyboard, a PS/2 keyboard scan code is sent to the Genesys 2 over the USB-HID port.
* Scan codes are read and transmitted to a terminal application via the USB-UART bridge.
* When the user releases a key, a scan code of F0XX is transmitted, indicating that the key with PS/2 code XX has been released.
Vivado is used to build the demo's hardware platform.  To use this demo, the Genesys 2 must be connected to a computer over MicroUSB.

For more information on the Genesys 2 Keyboard Demo, including setup instructions, visit its [Demo Page](https://digilent.com/reference/programmable-logic/genesys-2/demos/keyboard) on the Digilent Wiki.

For more information on the Genesys 2, including other demos that may be available, see its [Resource Center](https://digilent.com/reference/programmable-logic/genesys-2/start) on the Digilent Wiki.

Requirements
------------
* **Genesys 2**: To purchase a Genesys 2, see the [Digilent Store](https://digilent.com/shop/genesys-2-kintex-7-fpga-development-board/).
* **Vivado 2019.1 Installation**: To set up Vivado, see the [Installing Vivado and Digilent Board Files Tutorial](https://reference.digilentinc.com/vivado/installing-vivado/start).
* **Serial Terminal Emulator Application**: For more information see the [Installing and Using a Terminal Emulator Tutorial](https://reference.digilentinc.com/learn/programmable-logic/tutorials/tera-term).
* **USB Keyboard**
* **MicroUSB Cables**
* **Genesys 2 Power Supply**

Git Navigation Information
--------------------------
For instructions on how to use this repository with git, and for additional documentation on the submodule and branch structures used, please visit [Digilent FPGA Demo Git Repositories](https://reference.digilentinc.com/reference/programmable-logic/documents/git) on the Digilent Wiki. Note that use of git is not required to use this demo. Digilent recommends the use of project releases, for which instructions can be found in each demo wiki page, linked above.

To see other demos in this repository, see the master branch's [README](https://github.com/Digilent/Genesys-2).

Some demos do not require some submodules, in these cases, they are still provided to ease switching between demos in git. When unused, the submodule folder is largely empty, except for a readme containing only the heading "Root commit". This demo contains the following submodules:

| Submodule | Used by this demo |
|-----------|-------------------|
| HW        | Yes      |
| OS        | No       |
| SW        | No      |

Demo Setup
----------
In order to view or change the demo, the corresponding repositories must be cloned and rebuilt.

1. Repositories for the Keyboard Demo can be found on Github, see the [Vivado project](https://github.com/Digilent/Genesys-2-HW/tree/Keyboard/master).
2. Connect the power supply.
3. Connect a computer to the USB/JTAG port and the USB/UART port via the MicroUSB cables.
4. Flip the POWER switch to the ON position.
5. Program Device from Vivado.

Next Steps
----------
This demo can be used as a basis for other projects by modifying the Vivado project.
Check out the Genesys 2's [Resource Center](https://reference.digilentinc.com/programmable-logic/genesys-2/start) to find more documentation, demos, and tutorials.
For technical support or questions, please post on the [Digilent Forum](forum.digilentinc.com).

Known Issues
------------
* None.

Additional Notes
----------------
For more information on how this project is version controlled, refer to the digilent-vivado-scripts submodule's [README](https://github.com/digilent/digilent-vivado-scripts).

