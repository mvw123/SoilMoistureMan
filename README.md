Soil Moisture Man [WIP]
===============

WARNING: THIS PROJECT WILL CAUSE ELECTROLYSIS AND SO THE PLATING ON THE LEGS WILL DEGRADE OVER TIME. SOME CONTAMINATION OF THE SOIL WILL OCCUR. DO NOT USE ON EDIBLE PLANTS. 

The Soil moisture man CAD files are drawn using Eagle CAD free edition. 
Simulation files are included. These use Simetrix (windows only) http://www.simetrix.co.uk/site/index.html

The Soil Moisture Man is an educational "open source hardware" project which flashes warning LEDs when your plants soil becomes dry. 
This stops you under-watering and killing your plants. 
* The device uses standard electronic circuits to measure the resistance of the soil. 
* Transistors and variable resistor test the soil moisture level and switch the circuit on when required
* An Astable multivibrator is used to flash the LEDs at a certain frequency and duty cycle. 
* This is NOT a commercial product and is not suitable for commercial sale. It is to be used solely for educational use. We do not warrant its use in any way shape or form. 

To use the soil moisture man, you need to calibrate the device to flash its LEDs when your soil becomes dry to the point where it will need watering. 
You do this by :- 
* Select a plant whose soil has just reached the point where it needs watering, but where the soil is not dry or parched.
* Insert the gold coloured legs into the soil next to a plant, up to the point where the gold flashing on the legs stops. Inserting the device further could damage the circuitry.
* Turn VR1 until the LEDs just start to flash consistently. 


CAD C [WIP]
===========

CAD C is being updated due to some minor issues on CAD B which have been raised in github.
Battery lifetime is being tested. 

CAD B [TESTED - Some issues present] 
=====

Changed the circuit around from CAD A. 
The Astable multivibrator is now turned on by the soil moisture sensor transistor. 
This saves some small amounts of power and thus increases the battery life.
BOM parts updated and new VR1 chosen

CAD A [FAULTY] 
=====

Initial schematic release.
Ignore this version, it has been superseded by CAD B
Released to OSH park with a bug. 
The ground track was missing on the VR1 trimmer
The CAM file output did not work correctly due to the solder mask resist keep out area size. it needed pulling back from the edge of the PCB.
Final component selection was not completed and has now changed on CAD B. 
The circuit design changed on CAD B. 


