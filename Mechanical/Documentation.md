# 1/2/26
- A 3D model was created to display conceptual ideas of the AFSRM
- Thermal features were not a result of analysis, PCBs were not optimized yet, and there are no sensors within the case.
  
**What I learned** 
- The bearing holder within the "stator case" is the biggest problem is the bearing.
- Bearing is 7mm thick
- Creating an inner holder for the bearing makes the motor 40mm.
- Without the bearing holders, maximum thickness would be 26mm.
- Thus, the radii to thickness issue can be addressed through bearings

**Next Steps**
- Determine if PCB Stacking is necessary based on Biot-Savart model/optimization/torque calculator
- Create a way to hold PCB in motor, without reducing coil area for holes.

Author: Jaine R.

# 1/3/26
PCB STACKING is impractical using physics principles and pcb connection techniques:
- PCB stacking through pins and connectors would introduce air gaps between energized trace coils. 
- Magnetic feild decreases exponentially with distance, and thus negative affects would add up
- wiring and controls would be bulkier 

For now the design will be tested with a 2-layer PCB for cost and simplicity. 
If torque is too low, then the design will contain 4-layer PCB. 

Author: Jaine R. 
