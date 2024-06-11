# code_utils

This is a forked version of [this](https://github.com/gaowenliang/code_utils/) repository, updated to be compatible with modern libraries and ROS1 Noetic. It provides utility functions to [imu_utils](https://github.com/gaowenliang/imu_utils).

### Changes

- Updated code for OpenCV 4.x
- Fixed some CMake issues
- Fixed dependancy tree

### Installation

This is just a dependancy of imu_utils, so you can clone this into your catkin workspace along with imu_utils if you want to build from source.

The [noetic-docker](https://github.com/Ulysses-Ecosystem-Engineering/noetic-docker) repo contains imu_utils built and installed along with its dependancies and Kalibr for full stereo-inertial calibration.
