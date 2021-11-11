# PrintHeadController
A 3D printer controller board

Inspired by the possibility of Klipper 3D printer firmware (https://www.klipper3d.org/ ) that allows to have several I/O controller boards, PrintHeadController is a small board intended to be mounted on the moving print head assembly.

This reduces the cabling effort significantly as only power supply and USB is needed.

PrintHeadController has the following features:
* Based on the RP2040 MCU (the one that is used on the Raspberry PI Pico), so it is supported by the Klipper firmware out of the box
* Single socket for a stepper driver module e.g. DRV8825, various TMC variants
* Supports the SPI configuration of TMC drivers
* 12 V and 24 V capable
* 4 Digital inputs
* 4 MOSFET outputs (e.g. hotend heater, fans)
* 4 Thermistor inputs
* BLTouch support
* Debug pins accessible
* Accelerometer ADXL245 optional on board
