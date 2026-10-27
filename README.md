# IRIS 7.0: LiDAR-Free Autonomous Robot

Low-cost autonomous robot using camera, ToF, and IMU (no LiDAR) for
perception, mapping, localization, obstacle detection, and path planning.
Developed in Gazebo with ROS 2, then deployed on STEVAL-ROBKIT1 via micro-ROS.

## Team
- <
1.Member Name:Kedar Sadawrate​​
Hardware Implementation & Architecture ​

2​.​Yash Redekar ​: Implementation of ROS2 and Micro ROS​

3​​.Debajyoti Pramanick​: Implementation of ROS2 and Micro ROS​

4​​.Asha Sharma​: Establish a reliable camera and ToF data acquisition pipeline on the STEVAL-ROBKIT, with a rule-based baseline.​
>

## Status
- [ ] Simulation environment (Gazebo + ROS 2)
- [ ] Perception
- [ ] Mapping and localization
- [ ] Navigation
- [ ] micro-ROS deployment on STEVAL-ROBKIT1

## Repo layout
- `docs/`: design notes and diagrams
- `firmware/`: micro-ROS / STM32 code for STEVAL-ROBKIT1
- `ros2_ws/src/`: ROS 2 packages (perception, mapping, navigation)
- `ml/`: data, notebooks, and exported models
- `scripts/`: data logging and utilities
- `tests/`: tests
