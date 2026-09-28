+++
[extra]
profile_picture = "/images/profile-sm.jpg"
name = "Azamat Turganbayev"
subtitle = "Robotics Engineer and Researcher"
about_me = """
I'm a robotics engineer with research interests in robot manipulation, perception, and human-centered robotics. I'm currently pursuing an MS in Robotics at the University of Minnesota.

You can find my skills, education, and experience in the timeline below, along with my publications and talks.
"""

##########
# SKILLS #
##########

[[extra.skills]]
group = "Programming Languages & Libraries"
items = ["Python", "C/C++", "MATLAB", "OpenCV"]

[[extra.skills]]
group = "Robotics Frameworks & Tools"
items = ["ROS / ROS2", "UR5", "URScript", "RoboDK", "Gazebo", "Linux", "Git", "Docker"]

[[extra.skills]]
group = "Modeling & Simulation"
items = ["SolidWorks", "MATLAB/Simulink", "QUARC", "3D printing"]

[[extra.skills]]
group = "Control Systems"
items = ["PID control optimization", "Real-time systems", "Motion planning"]

################
# TOP PROJECTS #
################

[[extra.top_projects]]
name = "Tactile Surface Exploration with UR5"
icon = "/assets/icons/robot-arm.svg"
link = "projects/tactile-ur5"
calltoaction = "Read More"
background = "#3776AB"
color = "#fff"
description = """
Built an end-to-end pipeline for automated tactile exploration of a silicone cone with a UR5 collaborative arm, from CAD-derived surface geometry to executed touch sequences with synchronized contact-force recording on both simulated and physical robots.
"""

[[extra.top_projects]]
name = "UR5 Flashlight Assembly"
icon = "/assets/icons/flashlight.svg"
link = "projects/ur5-flashlight"
calltoaction = "Read More"
background = "#434343"
color = "#fff"
description = """
Programmed a UR5 collaborative robot via the RoboDK Python API to autonomously assemble a three-part flashlight without human intervention. Defined Cartesian targets and implemented a multi-stroke pre-threading routine.
"""

[[extra.top_projects]]
name = "TurtleBot3 Obstacle Avoidance"
icon = "/assets/icons/robot-vacuum.svg"
link = "projects/turtlebot3"
calltoaction = "Read More"
background = "#273377"
color = "#fff"
description = """
Developed a LiDAR-based obstacle avoidance pipeline on TurtleBot3 Burger and integrated a Raspberry Pi camera for ArUco marker tracking and following, verified in Gazebo and real-world implementation.
"""

[[extra.top_projects]]
name = "Shoulder Exoskeleton"
icon = "/assets/icons/medical-bag.svg"
link = "projects/shoulder-exoskeleton"
calltoaction = "Read More"
background = "#009de0"
color = "#fff"
description = """
Designed and built a 5-DOF hybrid robotic shoulder exoskeleton, enabling full-range shoulder rotations while preserving alignment with the human glenohumeral joint center of rotation.
"""

[[extra.top_projects]]
name = "Miniature Shoulder Model"
icon = "/assets/icons/cog.svg"
link = "projects/miniature-shoulder"
calltoaction = "Read More"
background = "#004791"
color = "#fff"
description = """
Designed a 5-DOF miniature shoulder coupling mechanism combining a 2-DOF crank-rocker four-bar linkage with a 3-DOF cable-driven parallel mechanism. Derived forward and inverse kinematics and built a 3D-printed prototype.
"""

############
# TIMELINE #
############

[[extra.timeline]]
title = "Foundation Year Program"
subtitle = "Nazarbayev University"
subtitle_link = "https://cps.nu.edu.kz/foundation"
date = "Aug 2018 - May 2019"
icon = "/assets/images/cps.png"
background = "#ea6868"
foreground = "#fff"
content = """
This is where my journey into robotics began. It was during this year that I chose robotics as my major, setting the course for everything that followed.
"""

[[extra.timeline]]
title = "BS in Robotics and Mechatronics"
subtitle = "Nazarbayev University"
subtitle_link = "https://seds.nu.edu.kz/bachelor_in_re"
date = "Aug 2019 - June 2023"
icon = "/assets/images/seds.png"
background = "#eb7627"
foreground = "#fff"
content = """
Graduation Project: Shoulder Rehabilitation Robotic Exoskeleton. Coursework: Electromechanical Systems, Mechanical Design with CAD, Image Processing, Linear Control Theory, Microcontrollers, Robotics: Kinematics and Dynamics. Full Scholarship.
"""

[[extra.timeline]]
title = "Undergraduate Research Assistant"
subtitle = "Nazarbayev University"
subtitle_link = "https://seds.nu.edu.kz/bachelor_in_re"
date = "April 2022 - Nov 2023"
icon = "/assets/images/nu.png"
background = "#0b2545"
foreground = "#fff"
content = """
Investigated biomechanical aspects of human-robot interaction to improve the efficacy of stroke recovery. Built early 3D-printed prototypes that became the basis for the full-scale exoskeleton.
"""

[[extra.timeline]]
title = "Senior Research Assistant"
subtitle = "CEMRR"
subtitle_link = "https://cemrr.nu.edu.kz/en"
date = "Nov 2023 - April 2025"
icon = "/assets/images/cemrr.png"
background = "#dde6f7"
foreground = "#fff"
content = """
Conducted advanced research on robotic-assisted rehabilitation, focused on enhancing upper limb recovery for stroke survivors. Led the design and development of a full-scale hybrid robotic shoulder exoskeleton.
"""

[[extra.timeline]]
title = "Robotics Laboratory Assistant"
subtitle = "Nazarbayev University"
subtitle_link = "https://seds.nu.edu.kz/sedslaboratories"
date = "Nov 2023 - July 2025"
icon = "/assets/images/seds.png"
background = "#eb7627"
foreground = "#fff"
content = """
Managed laboratory operations and technical coordination, keeping facilities and equipment ready for complex robotics research and coursework.
"""

[[extra.timeline]]
title = "MS in Robotics"
subtitle = "University of Minnesota"
subtitle_link = "https://cse.umn.edu/mnri/masters-robotics-overview"
date = "Sept 2025 - Dec 2026"
icon = "/assets/icons/umn-logo.svg"
icon_scale = 1.7
background = "#ffcc33"
foreground = "#7a0019"
content = """
Studying Machine Learning Fundamentals, Robotics, Robot Vision, Introduction to Intelligent Robotics Systems, and 3D Bioprinting under the [Bolashak Scholarship](https://bolashak.gov.kz/en/o-kompanii).
"""

[[extra.timeline]]
title = "Research Assistant"
subtitle = "Tactile Robotics Laboratory"
subtitle_link = "https://tact.nu.edu.kz/"
date = "May 2026 - Sept 2026"
icon = "/assets/images/tactile.png"
background = "#f0f0f0"
foreground = "#fff"
content = """
Developed an automated tactile exploration system for a UR5 robot arm, enabling systematic, calibrated surface-contact mapping with synchronized force sensing on simulated and physical robots.
"""

################
# PUBLICATIONS #
################

[[extra.publications]]
authors = "A. Niyetkaliyev, **A. Turganbayev**, M. Karasheva, R. Zhylkaidarov and Y. Turlybek"
title = "Exploring the Potential of Four-Bar Linkages in Robotic Exoskeletons: A Comprehensive Review"
venue = "Journal of Mechanical Design, vol. 147, no. 10, April 2025"
link = "https://asmedigitalcollection.asme.org/mechanicaldesign/article-abstract/147/10/100801/1213536/Exploring-the-Potential-of-Four-Bar-Linkages-in?redirectedFrom=fulltext"
doi = "10.1115/1.4068107"

[[extra.publications]]
authors = "M. Karasheva, **A. Turganbayev**, A. Aimysheva and A. Niyetkaliyev"
title = "Design of a 3D Printed Miniature Model for Human-Robot Mechanism Coupling for Shoulder Rehabilitation"
venue = "2023 8th International Conference on Robotics and Automation Engineering (ICRAE), Singapore, Singapore, 2023, pp. 58–65"
link = "https://ieeexplore.ieee.org/document/10458641"
doi = "10.1109/ICRAE59816.2023.10458641"

[[extra.publications]]
authors = "S. Omirbayev, I. Issa, Z. Kuangaliyev, **A. Turganbayev** and A. Niyetkaliyev"
title = "The Use of Four-Bar Mechanisms in Robotic Exoskeletons"
venue = "2022 International Conference on Advanced Mechatronic Systems (ICAMechS), Toyama, Japan, 2022, pp. 149–156"
link = "https://ieeexplore.ieee.org/document/10003280"
doi = "10.1109/ICAMechS57222.2022.10003280"

#########
# TALKS #
#########

[[extra.talks]]
date = "May 5, 2026"
type = "Project Presentation"
title = "Printability of Different PEGDA Concentrations"
venue = "BMEN5361: 3D Bioprinting (Spring 2026), University of Minnesota, Twin Cities, MN"

[[extra.talks]]
date = "Dec 9, 2025"
type = "Project Presentation"
title = "Vision-Based ArUco Marker Navigation and Obstacle-Avoiding Algorithm for TurtleBot3 Burger Robot"
venue = "EE 5271: Robot Vision (Fall 2025), University of Minnesota, Twin Cities, MN"

[[extra.talks]]
date = "Dec 1, 2025"
type = "Project Presentation"
title = "Vision-Based ArUco Marker Navigation and Obstacle-Avoiding Algorithm for TurtleBot3 Burger Robot"
venue = "CSCI 5551: Introduction to Intelligent Robotic Systems (Fall 2025), University of Minnesota, Twin Cities, MN"

[[extra.talks]]
date = "May 2, 2023"
type = "Project Presentation"
title = "Shoulder Rehabilitation Robotic Exoskeleton"
venue = "ROBT 491: Graduation Project (Spring 2023), Nazarbayev University, Astana, Kazakhstan"

[[extra.talks]]
date = "Dec 19, 2022"
type = "Conference Presentation"
title = "The Use of Four-Bar Mechanisms in Robotic Exoskeletons"
title_link = "https://ieeexplore.ieee.org/document/10003280/"
venue = "2022 International Conference on Advanced Mechatronic Systems (ICAMechS), Toyama, Japan"

+++
