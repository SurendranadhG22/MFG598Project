# MFG598Project
The UAV Landing project is a sophisticated ROS simulation for guiding UAVs to land on both stationary and moving targets using dynamic control strategies. It integrates the hector_quadrotor model and hector_gazebo for lifelike simulations, featuring advanced velocity estimation and PID tuning, supported by Python and visualized through RViz.
Here's a concise README.md for the UAV Landing project:

---

# UAV Landing Project

## Overview
This ROS-based project enables unmanned autonomous vehicles (UAVs) to autonomously land on both stationary and moving targets. Utilizing the `hector_quadrotor` model and `hector_gazebo` for simulations, the project aims to advance UAV landing strategies.

## Features
- **Dynamic Target Tracking**: Adjust landing strategies based on real-time movements of targets.
- **Velocity Estimation**: Use advanced algorithms to estimate target velocity.
- **PID Tuning**: Optimize control parameters for precise landings.
- **Visualization**: Utilize RViz for real-time 3D visualization of UAV operations.

## Installation
Clone this repo into your ROS workspace:
```
cd ~/catkin_ws/src
git clone https://github.com/yourusername/uav_landing.git
cd ..
catkin_make
```

## Usage
Launch the simulation with:
```
roslaunch uav_landing main.launch
```

## Contributing
Feel free to fork this repository and submit pull requests or open issues to suggest improvements.

---

This README provides essential information about the project, how to set it up, and how to contribute to its development.
