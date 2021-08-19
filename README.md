RPLIDAR ROS package for Noetic
=====================================================================

To use this repository you need to have Ros noetic properly installed in your machine: http://wiki.ros.org/noetic/Installation

You also need to have bulit your catkin workspace: http://wiki.ros.org/ROS/Tutorials/InstallingandConfiguringROSEnvironment

NOTE: This tutorial assumes you have your catkin_ws folder in your home directory if not simply change directory to your catkin_ws/src and continue from the git clone part (line 29 in this readme file)

ROS node and test application for RPLIDAR Ros Noetic Version

Visit following Website for more details about RPLIDAR:

rplidar roswiki: http://wiki.ros.org/rplidar

rplidar HomePage:   http://www.slamtec.com/en/Lidar

rplidar SDK: https://github.com/Slamtec/rplidar_sdk

rplidar Tutorial:  https://github.com/robopeak/rplidar_ros/wiki

How to build rplidar ros package:
=====================================================================

1) Clone this package:

    ```
    cd catkin_ws/src
    git clone https://github.com/sacchinbhg/Ros-Noetic-RPLidar.git
    cd ..
    catkin_make
    ```

How to run rplidar ros package
=====================================================================

(for RPLIDAR A1/A2)

```roslaunch rplidar_ros view_rplidar.launch``` 


or


(for RPLIDAR A3)

```roslaunch rplidar_ros view_rplidar_a3.launch```

You should see rplidar's scan result in the rviz.

You can also use this repository to see the ros topics used and message types. Using this information you can use hector slam to make a Simoultaneous Localization and mapping robot. Currently working on that repository.
