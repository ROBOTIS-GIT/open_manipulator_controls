# OpenMANIPULATOR Controls [![Build Status](https://travis-ci.org/ROBOTIS-GIT/open_manipulator_controls.svg?branch=master)](https://travis-ci.org/ROBOTIS-GIT/open_manipulator_controls)

## How to Run
```bash
(MoveGroup + JointTrajectoryController)
# Gazebo Simulation
$ roslaunch open_manipulator_controllers joint_trajectory_controller.launch

# Real Robot
$ roslaunch open_manipulator_controllers joint_trajectory_controller.launch sim:=false

(GravityCompensationController)
# Gazebo Simulation
# Set trasmission to effort and motor mode to current first
$ roslaunch open_manipulator_controllers gravity_compensation_controller.launch 

# Real Robot
$ roslaunch open_manipulator_controllers gravity_compensation_controller.launch sim:=false
```
