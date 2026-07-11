+++
title = "3D-Printed Miniature Model for Human-Robot Shoulder Coupling"
weight = 5
[extra]
paper = "https://ieeexplore.ieee.org/document/10458641"
icon = "/assets/icons/cog.svg"
background = "#004791"
color = "#fff"
+++

**Tools & Technologies:** SolidWorks, MATLAB, four-bar linkage kinematics, cable-driven parallel mechanisms, 3D printing

* Designed a 5-DOF miniature shoulder coupling mechanism combining a 2-DOF crank-rocker four-bar linkage for the shoulder girdle with a 3-DOF cable-driven parallel mechanism for the glenohumeral joint, modeling the shoulder's three rotational and two translational degrees of freedom.
* Derived forward and inverse kinematics for both the four-bar linkage and the cable-driven mechanism, then validated the equations against a SolidWorks CAD model in MATLAB, matching cable lengths and joint angles to within 1–2 mm and a few degrees.
* Designed a pretension mechanism to eliminate cable slacking and derailment, and built an adjustable 3D-printed prototype with reconfigurable cable connection points for testing different coupling strategies.
* This foundational prototype later informed the full-scale 5-DOF exoskeleton developed at CEMRR.

{{ exo_gallery(images=["/images/mini_shoulder/prototype.jpg", "/images/mini_shoulder/cas.jpg", "/images/mini_shoulder/sketch.jpg"]) }}
