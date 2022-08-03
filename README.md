# Genesys 2 Root Repository

This repository contains all demos for the Genesys 2.

For more information about the Genesys 2, visit its [Resource Center](https://digilent.com/reference/programmable-logic/genesys-2/start) on the Digilent Wiki.

Each demo contained in this repository is documented on the Digilent Wiki, links in the table below.

| Wiki Link | Demo Master Branch | Submodules Used |
|-----------|--------------------|-----------------|
| [Genesys 2 DMA Audio Demo](https://digilent.com/reference/programmable-logic/genesys-2/demos/dma-audio) | DMA-Audio/master  | HW, SW |
| [Genesys 2 HDMI Demo](https://digilent.com/reference/programmable-logic/genesys-2/demos/hdmi) | HDMI/master  | HW, SW |
| [Genesys 2 Keyboard Demo](https://digilent.com/reference/programmable-logic/genesys-2/demos/keyboard) | Keyboard/master  | HW |
| [Genesys 2 OLED Demo](https://digilent.com/reference/programmable-logic/genesys-2/demos/oled) | OLED/master  | HW |


## Repository Description

This repository is designed to offer a unified and comprehensive approach to all of the aspects of the demos that we provide for the Genesys 2, across multiple tools. By cloning this repo recursively you will receive the repositories for Vivado projects (HW), Vitis workspaces (SW), and Petalinux projects (OS). Each submodule may have its own submodule dependencies which will also be pulled when cloning. An important aspect of this structure is the fact that the SW and OS heavily depend on hardware hand-off files from the HW repository.

This repository also provides releases containing project and image files used by the various tools involved. Releases provide files that are directly usable, without requiring the use git or any scripting systems. Documentation of each demo, as well as instructions for using their releases, can be found by visiting the corresponding pages on the Digilent Wiki, links below. All releases in this repository can be found in this repository's [releases page](https://github.com/Digilent/Genesys-2/releases), however, use of the wiki pages to find specific well-tested releases is advised.

For instructions on how to use this repository with git, and for additional documentation on the submodule and branch structures used, please visit [Digilent FPGA Demo Git Repositories](https://reference.digilentinc.com/reference/programmable-logic/documents/git) on the Digilent Wiki. Note that use of git is not required to use this demo.
