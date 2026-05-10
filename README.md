# Self-Stabilizing Robot (MATLAB)

A MATLAB project to design and simulate a self-stabilizing robot, modeled as an inverted pendulum on a cart.

## THEORY
This stabilization problem is a classic control theory and engineering challenge, 
which is often used to test control algorithms. 

The equations of motion for the angle, θ and horizontal position, x are:

<img width="1087" height="287" alt="image" src="https://github.com/user-attachments/assets/6043c255-d0a2-42ca-b263-f498ae382563" />

Here, m is the mass of the robot body, ℓ is the length of the robot body, g is the gravitational acceleration, M is the mass of the robot base, and 
b is a damping coefficient representing friction. F is the force applied to the robot base, which is a value that you will control. 

## The project tasks:

### Model the unforced Pendulum: 
Created a Simulink model for an unforced pendulum.

### Model the forced Pendulum: 
Edited the model from the previous task to incorporate the force on the pendulum due to the cart.

### Integrate into an Existing Model: 
Integrated the forced pendulum model into a system model along with the provided cart subsystem.

### Implement a Controller: 
Finally, implemented a control algorithm to apply the necessary force to the cart, stabilizing the pendulum in the upright position.

## FEATURES
Simulation of robot stabilization using MATLAB/Simulink.
Configurable control strategies (PID, LQR, etc.).
Real-time visualization of robot behavior.
Modular design for easy extension.
