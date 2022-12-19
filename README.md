# limo_robot
This repository contains ROS packages for limo. 

## Packages

* limo_base: ROS wrapper for limo
* limo_bringup: launch and configuration files to start ROS nodes

## Build from source code
Clone the repository and catkin_make:
```
    cd ~/catkin_ws/src
    git clone https://github.com/limo_agx/limo.git
    git clone https://github.com/limo_agx/limo_robot.git
    cd ..
    rosdep install --from-paths src --ignore-src -yr
    catkin_make
