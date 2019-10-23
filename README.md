
## Laser Tower for my CAT 
Pseudo-randomly moves a servo tower (on X and Y axis) and lights up a laser.

## Set up
x_servo is attached to pin 9 (and +5V and GND) and moves in the X plain.

y_servo is attached to pin 6 (and +5V and GND) and moves in the Y plain.

Laser is attached to pin 13 (and GND).

## How it works : 
The program randomly chooses a new position for the laser inside a square you can define with the variables.
It checks if the new position is different from the old one.
It moves the tower to the new position and stays still for a time the vars min_freeze and max_freeze 
(this aims to reproduce the behaviour of an insect landing somewhere for a bit and then flying off, 
that's the variable you need to increase if your cat is fucking fat...).
Ans starts the process over and over again. 

ALL DAY BABY

