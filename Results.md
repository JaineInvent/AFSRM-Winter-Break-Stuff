# Notes, Records, and Conclusions from simulations 
### Magnetic feild due to different coil shapes and pcb layers
| Coil configuration | Top \|Bz\| (G) | Bottom \|Bz\| (G) | Turns |
|-------------------:|--------------:|------------------:|--------:|
| Wedge, 2 layers    |15409.76       | 8091.77           |50
| Spiral, 2 layers   |13127.55       | 7417.80           |50


Notes: 
- The number of turns was arbitrarily chosen, however, altering number of turns reveals the same pattern.
- The code behind the simulations changes current directions between the Wedge and the Spiral, thus, by right hand rule and Biot-Savart, relevant B_z are in opposite directions. The table above corrects for this. 
- The divergence of a magnetic feild must be 0. The simulation does not violate this, even though the B-feild is being seperated into top and bottom. Top refers to above the plane where the z-axis being sliced, conversely, bottom refers to below the plane on the z-axis.
- For the wedge and spiral, top is 2x greater than bottom. This asymmetry is due to the coils being in different layers and rotated by 180 deg. By RHR, rotating the coils allows for superpositon of the top B-feild(otherwise the B-feild between layers would cancel), while the bottom B-feild is only effected by 1 coil due to the slice being taken in between the coils.   
- Physically, top represents the start area of the magnetic circuit, while bottom represents flux return path. 
## Simulated B-feild in z-direction:
The z-direction is most relevant in an Axial Flux SRM. This is because the torque results from the magnetic flux passing from the PCB coils through the laminated steel sheets of the rotor. 

| Wedge (2 layers) | Spiral (2 layers) |
|------------------|-------------------|
| <img width="400" height="400" alt="image" src="https://github.com/user-attachments/assets/42c4c0ae-c595-4e1b-a6b4-d2817303e7c9" /> | <img width="400" alt="Spiral Bz" src="https://github.com/user-attachments/assets/d1cb6b8b-57b1-4e89-a33e-d52f2f8d1fc8" /> |
|<img width="400" height="400" alt="image" src="https://github.com/user-attachments/assets/3db6314d-efd2-42a6-a604-1a60566aef7a" />  | <img width="400" height="400" alt="image" src="https://github.com/user-attachments/assets/28002d27-83c0-4dc4-8c71-094229688d30" /> |

In terms of the construction Axial Flux SRM:
The wedge is the better option both due to area fill and greater B_z than the spiral. 

