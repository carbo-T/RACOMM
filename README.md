# RACOMM: OpenStreetMap and Radar Aided Consistent State Estimation For Autonomous Vehicles

This repository contains the code and related resources of the paper OpenStreetMap and Radar Aided Consistent State Estimation For Autonomous Vehicles.

## System Structure
<div align="center">
  <p align="center"><img src=RACOMM/resources/system_structure_hires.jpg alt="animated"  width="800"/></p>
</div>

## Recent Result in KAIST 03 of MulRan dataset
<div align="center">
  <p align="center"><img src=RACOMM/resources/kaist03_small.gif alt="animated"  width="800"/></p>
</div>

## Dependencies
* `C++` >= 14, `OpenCV` >= 4.2.0, `OpenMP` >= 4.5, `CMake` >= 3.15.0, `Boost` >= 1.71
* [ROS](http://wiki.ros.org/ROS/Installation) (tested with Noetic)
  ```
  sudo apt-get install -y ros-noetic-navigation
  sudo apt-get install -y ros-noetic-robot-localization
  sudo apt-get install -y ros-noetic-robot-state-publisher
  ```
* [gtsam](https://gtsam.org/get_started/) (Georgia Tech Smoothing and Mapping library)
  ```
  sudo add-apt-repository ppa:borglab/gtsam-release-4.0
  sudo apt install libgtsam-dev libgtsam-unstable-dev
  ```
* eigen: ```sudo apt-get install libeigen3-dev```
* pcl: ```sudo apt-get install libpcl-dev```

## Compile

RACOMM can be compiled by catkin_make. In Ubuntu 20.04, the compile step is relatively simple.
Clone this repository to your catkin workspace, e.g., ~/catkin_ws/src, then use the following commands to build RACOMM:
```bin/bash
cd ~/catkin_ws/
catkin_make -j6
```

## Code
### The code will be coming soon…
