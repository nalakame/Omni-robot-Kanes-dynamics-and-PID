# Omni_robot_dynamics_PID
This Mathematica notebook provides development of a Forward Kinematic model(FKM), Inverse Kinematic Model(IKM), and Dynamic model using Kane's method of a Universal Omni Wheeled mobile robot. Also, a PID trajectory tracking controller was developed to track different trajectories with very small error. 

The following GIF animation shows the behaviour of the robot for a given combiniation of global x, y, and z velocities. The FKM was tested for possible combinations of inputs and demonstrated the expected outputs. 
<img src= "https://github.com/nalakame/Omni_robot_dynamics_PID/assets/106627981/77160d49-5951-4f2d-9072-bf18c7e7fb6a" width=300 height=300>

IKM was develped and tested for different combinations of wheel velocities.
<img src= "https://github.com/nalakame/Omni_robot_dynamics_PID/assets/106627981/bc5f8ec7-c581-4bf7-be9c-82b2d472f45a" width=300 height=300>

The full dynamic model of the robot was developed using Kane's equations including rollers. 
<img src= "https://github.com/nalakame/Omni_robot_dynamics_PID/assets/106627981/daded0bb-a104-44f5-889e-a14609866055" width=300 height=300>

A PID controller was developed for 
<img src= "https://github.com/nalakame/Omni_robot_dynamics_PID/assets/106627981/6c8c41cf-075b-408f-83d0-88c28da786d2" width=300 height=300>

<img src= "(https://github.com/nalakame/Omni_robot_dynamics_PID/assets/106627981/e3a46566-6884-4c32-8d76-3b09ab5f4459" width=300 height=300>

The published Journal paper on this work can be cited using:
Amarasiri, N., Barhorst, A. A., and Gottumukkala, R. (October 19, 2022). "Robust Dynamic Modeling and Trajectory Tracking Controller of a Universal Omni-Wheeled Mobile Robot." ASME. Letters Dyn. Sys. Control. October 2022; 2(4): 040902. https://doi.org/10.1115/1.4055690

Also, the preprint of the paper can be found: https://www.researchgate.net/profile/Nalaka-Amarasiri
