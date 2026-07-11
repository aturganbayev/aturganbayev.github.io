+++
title = "TurtleBot3 Obstacle Avoidance & ArUco Marker Navigation"
weight = 3
[extra]
github = "https://github.com/aturganbayev/CSCI5551-EE5271_Turtlebot_Navigation"
report = "/files/CSCI5551_Final_Project.pdf"
icon = "/assets/icons/robot-vacuum.svg"
background = "#273377"
color = "#fff"
+++

**Tools & Technologies:** TurtleBot3 Burger, ROS2 Humble, LiDAR, Raspberry Pi camera, Gazebo, RViz, Python

* Developed a LiDAR-based obstacle avoidance pipeline on TurtleBot3 Burger using two ROS2 nodes: `obstacle_detector` (monitors the front LiDAR sector and publishes Boolean obstacle topics) and `obstacle_avoidance` (overrides velocity commands to turn and back away when an obstacle is within 30 cm).
* Integrated a Raspberry Pi camera onto TurtleBot3 Burger, a non-standard hardware addition, calibrated its intrinsic parameters using a ROS2 checkerboard calibration package, and added a static TF frame to correctly represent the camera pose relative to the robot base link.
* Implemented ArUco marker tracking and following: the `aruco_follower` node fuses camera-derived heading to the marker with LiDAR range measurements to drive the robot to a target distance while stopping when the marker leaves the camera's field of view.
* Validated both algorithms first in Gazebo simulation, then transferred them to the real robot with LiDAR noise filtering adjustments for reliable real-world performance.

{{ youtube(id="5Qi0RW_q2Dw") }}
