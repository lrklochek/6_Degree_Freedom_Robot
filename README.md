# 6 Degrees of Freedom Robot Arm

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
<img alt="Image of the IR Remote" src="images/IR_Remote.jpg">

  * **Red Power Button** – sets arm to Home position
  * **ST/RPT** Resets all stop execute functions
  * **0** starts a complete tower build sequence
  * **1** starts a Home to Position 1 to Home sequence
  * **2** starts a Home to Position 2 to Home sequence
  * **3** starts a Home to Position 3 to Home sequence
  * **4** starts a Home to Position 4 to Home sequence
  * **5** starts a Home to Position 5 to Home sequence
  * **6** starts a Home to Position 5 level 2 to Home sequence
  * **7** starts a Home to Position 5 level 3 to Home sequence
  * **8** starts a Home to Position 5 level 4 to Home sequence

The IR control allows selecting 9 different Robot Arm operations. 
Selecting "0" start 1 complete 4 block tower building operations.
Selecting "1" starts a single Arm movement from Home position to Position 1, and then back to Home.
Similarly selecting "1" through "8" will start a single Arm movement to posiitons 2 through 5-level-4 Positions.
To start another another sequence requires resetting the stop execute function. This is done by depressing the ST/RPT button.

## Display
<img alt="Display" src="images/Display Scaled .jpg">
