+++
title = "Automated Flashlight Assembly with UR5"
weight = 2
[extra]
github = "https://github.com/aturganbayev/ME5286_UR5_Flashlight_Assembly#me5286-lab-4--ur5-flashlight-assembly"
report = "/files/ME5286_Flashlight_Assembly.pdf"
icon = "/assets/icons/flashlight.svg"
background = "#434343"
color = "#fff"
+++

**Tools & Technologies:** UR5, RoboDK, Python, Cartesian & joint-space motion planning, pneumatic clamping

* Programmed a UR5 collaborative robot via the RoboDK Python API to autonomously assemble a three-part flashlight (head, battery, endcap) without human intervention.
* Defined 15 Cartesian targets for pick-and-place, insertion, and fastening operations; used joint-space motion for fast transits and Cartesian linear motion near contact points to prevent collisions.
* Implemented a multi-stroke pre-threading routine followed by torque-controlled final tightening, coordinated with a pneumatic chuck and optical sensor for stable part fixturing.
* Completed the full assembly sequence in 1 minute 39 seconds, within the 110-second requirement.

{{ youtube(id="OAarKcr0SdI") }}
