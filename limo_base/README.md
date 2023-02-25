# Limo Base

This package is the main driver that communicates with the Limo platform

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

Normally this package is used by the limo_bringup package, but in some cases could be launched manually with

    roslaunch limo_base limo_base.launch

## More Documentation

[Limo Startup - Limo Docs](https://limo-agx.github.io/starting_limo.html)