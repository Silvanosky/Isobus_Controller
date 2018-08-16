# Isobus_Controller
Project aiming to control a Tractor using Isobus protocol on the tractor can bus.

This project use a Raspberry Pi with the PiCAN 2 module connected to the CAN bus of the tractor.

## Kernel module

To enable isobus compatibility on the socketcan module you need to rebuild
the module for the Raspberrypi

You can rebuild the kernel on your Raspberry pi or do a cross-compilation:

https://www.raspberrypi.org/documentation/linux/kernel/building.md
