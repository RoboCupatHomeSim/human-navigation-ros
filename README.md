# ROS Package for Human Navigation

This project is ROS package for the Human Navigation task of the RoboCup@Home Simulation.

See also [wiki page](https://github.com/RoboCupatHomeSim/human-navigation-ros/wiki).

## Prerequisites

Same as below for OS and ROS version.  
https://github.com/RoboCupatHomeSim/documents/blob/master/SoftwareManual/Environment.md#ubuntu-pc

## How to Install

### Install Rosbridge Server

Please see below.  
http://wiki.ros.org/rosbridge_suite

### Install SIGVerse Rosbridge Server

Please see below.  
https://github.com/SIGVerse/ros_package/tree/master/sigverse_ros_bridge

### Install ROS Package of Human Navigation

```bash:
$ cd ~/catkin_ws/src
$ git clone https://github.com/RoboCupatHomeSim/human-navigation-ros.git
$ cd ..
$ catkin_make
```

## How to Execute

### How to Execute Sample ROS Node

This sample ROS node communicates with the Unity application of Human Navigation.  
HSR can be operated with keyboard operation.

```bash:
$ roslaunch human_navigation sample.launch
```

## License

This project is licensed under the SIGVerse License - see the LICENSE.txt file for details.
