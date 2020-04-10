# Marlin-2.0-Sensorless-Homing

* SKR PRO v1.1 motherboard
* 4x TMC2209 stepper motor drivers (X, Y, Z1, Z2)
* Standard Titan Extruder
* V6 all-metal hotend

I have started this repository to help me enable sensorless homing for the X, Y, and Z axis. 

Progress:

* X axis sensorless homing is working 
* Y axis sensorless homing is working
* Z axis switch probe is working

Currently experimenting with reducing the current to the Z steppers to reduce torque to make StallGuard viable on the Z axis.

This project is for fun and learning!
