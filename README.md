# microreaper
Flight code for Miniature Reaper Drone based on Raspberry Pi Zero W

# Introduction
microreaper is a software specifically based for single rotor RC airplanes.

# Hardware and Software pre-requisites
The code needs in order to run properly the following hardware and software pre-requisites
## UAV pre-requisites
* Raspberry Pi Zero W
* IMUs to stabilize airplane
** Supported: MPU9250
* Motor Driver to control servos and rotor
** Supported: PCA9685

## Software pre-requisites
* Python 2.* (not yet tested with Python 3.*)
* python-smbus
* RPi-GPIO (>= 0.5.11)