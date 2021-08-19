RPLIDAR ROS package for Noetic
=====================================================================

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

```roslaunch rplidar_ros view_rplidar.launch (for RPLIDAR A1/A2)```


or


```roslaunch rplidar_ros view_rplidar_a3.launch (for RPLIDAR A3)```

You should see rplidar's scan result in the rviz.

You can also use this repository to see the ros topics used and message types. Using this information you can use hector slam to make a Simoultaneous Localization and mapping robot. Currently working on that repository.
