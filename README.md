SoilMoistureMan
===============

Soil moisture sensor CAD files using Eagle CAD free edition

The Soil Moisture Man is an educational "open source hardware" project which allows you flash warning LEDs when your plants soil becomes dry. 
This stops you under-watering and killing your plants. 
* The device uses standard electronic circuits to measure the resistance of the soil. 
* transistors and variable resistor test the soil moisture level and switch the circuit on when required
* An Astable multivibrator is used to flash the LEDs at a certain frequency and duty cycle. 

To use the soil moisture man, you need to calibrate the the device to flash its LEDs when your soil becomes dry to the point where it will need watering. 
You do this by :- 
* Select a plant whose soil has just reached the point where it needs watering, but where the soil is not dry or parched.
* Insert the gold coloured legs into the soil next to a plant, up to the point where the gold flashing on the legs stops. Inserting the device further could damage the circuitry.
* Turn VR1 until the LEDs just start to flash consistently. 


CAD B [NOT TESTED] 
=====

Changed the circuit around from CAD A. 
The Astable multivibrator is turned on by the soil moisture sensor transistor. 
This saves some small amounts of power and thus increases the battery life.
BOM parts updated and new VR1 chosen

CAD A [NOT TESTED] 
=====

Initial schematic release.
Ignore this version, it has been superseded by CAD B
Released to OSH park with a bug. 
The ground track was missing on the VR1 trimmer
The CAM file output did not work correctly due to the solder mask resist keep out area size. it needed pulling back from the edge of the PCB.
Final component selection was not completed and has now changed on CAD B. 
The circuit design changed on CAD B. 


