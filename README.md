# mr_manipulator

## Description
This repository presents an implementation of a 3DoF manipulator.
The manipulator is built with LX16-A servos from LewanSoul and 3D printing, featuring 3 load cells in each joint.
The low-level conntrol and kinematics are controlled by a esp32-wroom microcontroller within a schematic for communication with the servors.
A ROS 1 package was developed to represent the URDF model of the robot and clone it's motion for visualization. It also alows to send command and adjust parameters, see below.

## Composition
- [mr_manipulator_ros](https://github.com/jakkkobo/mr_manipulator_ros.git) - ros package to communicate, interact and command the real manipulator.
- [mr_manipulator esp32](https://github.com/jakkkobo/rm_manipulator_esp32.git) - Esp32 embedded firmware to control the real robot.

## Architecture

//TODO

## Control board schematic

![](https://github.com/jakkkobo/mr_manipulator/blob/master/images/circuit_schematic.png)

## Results
x5 speed

![](https://github.com/jakkkobo/mr_manipulator/blob/master/images/all_features.gif)

