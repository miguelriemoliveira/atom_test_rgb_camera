# ATOM test rgb camera 

This is a test robotic system to test simple calibrations in ATOM:

https://github.com/lardemua/atom

The system contains a single sensor:
- **cameras** - One RGB camera mounted on the tripod.

# How to run

First launch the gazebo simulation:

    roslaunch atom_test_rgb_camera_bringup bringup.launch

This brings up Gazebo and Rviz. In Rviz it is possible to move the pattern around using interactive markers.

You can record a bag file using:

    roslaunch atom_test_rgb_camera_bringup record.launch

# Installation

##### Add to .bashrc:
```
export TURTLEBOT3_MODEL="waffle"
export ROS_BAGS="/home/<username>/bagfiles"
export ATOM_DATASETS="/home/<username>/datasets"
```
