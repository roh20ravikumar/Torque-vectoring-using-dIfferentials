# Torque-vectoring-using-dIfferentials
Contributions and results of the "Torque vectoring using differentials" project as a part of the Automotive Stability and Safety course

## My Contributions:
1. Developed, upper and lower-level traction control strategies to track a reference yaw rate to achieve maximum stability.
2. Utilized Carsim for the Vehicle model and developed a low-fidelity 2-DOF bicycle model for the reference tracking generator as well as the
the state evolution equation for the model predictive controller.
3. Leveraged the car sim co-simulation with MATLAB Simulink to implement control strategies using the s-function block.

## [Project Report](https://github.com/roh20ravikumar/Torque-vectoring-using-dIfferentials/blob/main/Group%201_Project%202_Report_AuE%208500.pdf)

### MATLAB Car sim co-simulation:

![image](https://github.com/roh20ravikumar/Torque-vectoring-using-dIfferentials/assets/95481658/7eb7c13f-fbe6-4658-9db7-69e1e104b80b)

### Overall VSC control logic:

![image](https://github.com/roh20ravikumar/Torque-vectoring-using-dIfferentials/assets/95481658/b8384579-6e40-4328-873c-9275b2597e88)

## Results:
### Yaw rate response for Sine with dwell test:

![image](https://github.com/roh20ravikumar/Torque-vectoring-using-dIfferentials/assets/95481658/5675b74d-a2a9-4d18-883c-883d54f2a6b6)

### Yaw rate response for J Turn test:

![image](https://github.com/roh20ravikumar/Torque-vectoring-using-dIfferentials/assets/95481658/90a0e6c9-d500-49ef-8120-52639e6aaf89)

### Lower-level clutch torque application using MPC:

![image](https://github.com/roh20ravikumar/Torque-vectoring-using-dIfferentials/assets/95481658/6f1cf4ce-5324-43ec-9100-3227c82be238)

### Double Lane Change maneuver with and without Torque vectoring or VSC:
https://github.com/roh20ravikumar/Torque-vectoring-using-dIfferentials/assets/95481658/6c9ebf32-f5ae-4d50-b55d-22cd6bddc3b0

