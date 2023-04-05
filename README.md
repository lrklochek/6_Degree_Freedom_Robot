# 6_Degree_Freedom_Robot

* The power system consists of 6 servo motors
* All bracket fittings are made of 2mm thick aluminum plate
* Imported cup bearings are used at the steering joints

## Servo Specification:
* Model: MG996R analog steering gear
* Working voltage: 4.8V-7.2V
* No-load current: 100mA
* Machine torsion: 10kg.cm
* Limit angle: 180°
* Gear material: Metal gear
* The Servos require a separate 5 V power supply rated at 2 amps

## Assembly of mechanical structure
The kit comes without instructions. A very good video to support assemble can be found at https://www.youtube.com/watch?v=hTZ2z_C9dSU
The servos must be supplied with a separate 5VDC power supply rated at 2 amps.
## Important Considerations for Coding

An important feature of the code is a method to reduce the speed that the arm transitions from original destination to final destination.
The method involves creating a function that moves the arm from the initial position to the final position in 1 degree increments or decrements. This eliminates the large interia that would result in the arm moving between positions at maximum speed resulting in stress on the metal gears.

## IR Control

