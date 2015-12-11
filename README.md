# VirtualRobotix Binaries and Drivers Project
==========

## Getting the binaries and drivers

You can either download the binaries and drivers using the "ZIP" button at the top
of the github page, or you can make a clone using git:

```
git clone git://github.com/virtualrobotix/VRX_binary.git
```

All the material contained in this project is available for boards

- VR Brain 4.5
- VR Brain 5.1 and 5.2
- VR Micro Brain 5.1 and 5.2
- VR Brain Core 1.0

and all the firmwares are based on real-time operating system NuttX

## Drivers

In this folder you can find the USB drivers for all VR boards

## Bootloader

In this folder you can find the bootloaders for all VR

## Firmwares

All the firmwares available are contained in VRX/firmwares folder.

- Copter: this folder contain the firmwares for Copter version
- Plane: this folder contain the firmwares for Plane version
- Rover: this folder contain the firmwares for Rover version

In each one of these folders there are 4 kind of firmwares:

- stable: stable version of firmware available for SBUS and PPMSUM radio channel
- beta: beta version of firmware available for SBUS and PPMSUM radio channel
- latest: latest version of firmware available for SBUS and PPMSUM radio channel
- custom: in this folder there are all custom firmwares for VR boards.
  + PPM: this is the version of firmware for PPM multi-channel radio
  + TONEALARM: this is the version (SBUS/PPMSUM and PPM multi-channel) with audio alarm port available only for VR Brain 5 and VR Micro Brain 5
