# Limo Bringup

This package contains all standard startup scripts for Limo hardware.  It will start the driver that controls the platform as well as any drivers needed to use the on-board sensors

## Set Up

Clone this repo into your workspace, install dependencies, build and source

    git clone https://github.com/limo-agx/limo.git
    git clone https://github.com/limo-agx/limo_robot.git
    git clone https://github.com/orbbec/ros_astra_camera.git
    cd ..
    rosdep install --from-paths src --ignore-src -y
    catkin_make
    source devel/setup.bash

## Usage

    roslaunch limo_bringup limo_start.launch

## More Documentation

[Limo Startup - Limo Docs](https://limo-agx.github.io/starting_limo.html)