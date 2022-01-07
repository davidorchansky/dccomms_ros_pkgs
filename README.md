# dccomms_ros_pkgs


| CI System | Status  |
|--|--|
| Travis | [![Build Status](https://travis-ci.org/dcentelles/dccomms_ros_pkgs.svg?branch=master)](https://travis-ci.org/dcentelles/dccomms_ros_pkgs) |
| ROS build farm (Jenkins) | [![Build Status](http://build.ros.org/job/Mdev__dccomms_ros_pkgs__ubuntu_bionic_amd64/badge/icon)](http://build.ros.org/job/Mdev__dccomms_ros_pkgs__ubuntu_bionic_amd64/) |

ROS packages with network simulation utilities. The NS3 library is used, which has been integrated as a git submodule.

### Dependencies
The C++ compiler must support C\+\+11, C\+\+14 and C\+\+17 (tested in Ubuntu 20.04).

### Install and Build
Clone this repository into the src folder of your catkin workspace with the *--recursive* option and build the workspace:
```bash
~/ros_ws/src$ git clone --recursive https://github.com/dcentelles/dccomms_ros_pkgs.git
~/ros_ws/src$ cd ..
~/ros_ws$ colcon build
```
### Using the library
Check the Wiki pages for more info.



