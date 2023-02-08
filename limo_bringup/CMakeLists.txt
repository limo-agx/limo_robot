cmake_minimum_required(VERSION 3.0.2)
project(limo_bringup)

find_package(catkin REQUIRED)

if (CATKIN_ENABLE_TESTING)
    find_package(roslaunch REQUIRED)
    roslaunch_add_file_check(launch/limo_start.launch)
endif()