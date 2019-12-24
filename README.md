# Linear-Quadratic-Gaussian-Control-Inverted-Pendulum-On-A-Cart

**To stabilize the full nonlinear system of an Inverted Pendulum on a Cart using combination of [Kalman Filter](https://en.wikipedia.org/wiki/Kalman_filter) and LQR controller** 

#### Objectives Achieved: 

- Modeled MIMO dynamic systems using state-space techniques.
- Numerically Linearized the full nonlinear system.
- Analyzed the open-loop and closed-loop stability of any state-space representation.
- Designed linear state-feedback controller using pole placement techniques.
- Designed optimal linear state-feedback controllers using Linear Quadratic Regulator (LQR) technique.
- Designed Kalman Filter, which is an optimal full-state estimator, given Gaussian white noise disturbances and measurement noise.
- Combined the optimal full-state feedback LQR with the optimal full-state estimator (LQE or Kalman Filter) to obtain the sensor-based linear quadratic Gaussian (LQG) controller.

<p align="center"><img src="auv_animate.gif">  </p>



#### Languages Used:
- Matlab
- Latex 

#### Use of each file:
- **Kalman_Filter_InvertedPendulum.mlx** - Executable file with clearly defined problem statement and approach
- **Kalman_Filter_InvertedPendulum.pdf** - Published Document for a quick check of Solutions and Code
- **animate_auv.p** - Animation code used throughout the code for easy visual and intuitive check
- **auv_animate.mp4** - Sample Example of auv motion when animate_auv.p is executed
