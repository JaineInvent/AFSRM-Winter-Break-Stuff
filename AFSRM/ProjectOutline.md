# PCB coil AFSRM outline 
- Dimensions unknown..for now, I just wanna play with kicad lol 
- Still need to decide on motor driver/control sensors
## Coils[Jaine R.]
1. Using KiCad and Biot-Savart python script I want to find the optimal coil shape to use. 
2. Biot-Savart python isn't useful for torque or energy calculations, but it's useful to see magnetic flux/leakage. 
3. I want more flux in the z-direction, to go through the salient poles of the rotor, so I can find geometry that minimizes flux in the x or y direction. 
4. Note: In a normal motor, you'd want x-axis flux, but, AFSRMs torque is determined by least magnetic reluctance between rotor and stator, rather than 'pulling B-feild' or induction.
Reference for Biot-Savart Script:   
## Heating and Torque simulations [Jaine R.]
1. Heating can be simulated using solidworks 
2. Torque, eddy current losses, etc using Maxwell 

## Laminated Steel sheets
1. Steel sheets are used to reduce eddy currents and losses. 
2.  ...more coming soon...eventually

## BMS(Battery Management System)-[Kezia S.]
1. This is eventually supposed to be an e-bike motor, capable of going back and forth between a generator and a motor. 
2. That will require a battery, which requires discharge and charging controls. 



