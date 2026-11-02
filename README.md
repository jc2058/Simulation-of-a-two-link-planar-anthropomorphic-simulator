[README-robot-arm.md](https://github.com/user-attachments/files/34281575/README-robot-arm.md)
# Computed torque control of a two-link robot arm

MSc Robotics coursework at Queen Mary University of London (2025). A MATLAB/Simulink model of a nonlinear two-link planar arm with a computed torque controller.

## What I tested

- Open-loop dynamics and closed-loop trajectory tracking
- Tip-mass ratios of 0, 0.1, 0.2, 0.5, 1, 2 and 10
- A phased move made in 30° steps to reflect limited motor capability
- Mismatches between the payload assumed by the controller and the true payload

## Main findings

The controller linearised and decoupled the dynamics, and tracking remained satisfactory as the payload increased, with higher torque demand and more overshoot. Even small payload mismatches degraded tracking.

## Files

- `robotics_coursework_simulation.slx`: Simulink model
- The PDF report: full method and results
