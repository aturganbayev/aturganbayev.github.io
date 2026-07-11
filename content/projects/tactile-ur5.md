+++
title = "Tactile Surface Exploration with UR5"
weight = 1
[extra]
github = "https://github.com/aturganbayev/tactile_UR5"
icon = "/assets/icons/robot-arm.svg"
background = "#3776AB"
color = "#fff"
+++

**Tools & Technologies:** UR5, URScript, Python, trimesh, NumPy, SciPy (ICP), pandas, Matplotlib, Docker (URSim), ATI Nano17 force sensor, NI-DAQ

* Built an end-to-end pipeline for automated tactile exploration of a silicone cone with a UR5 collaborative arm, from CAD-derived surface geometry to executed touch sequences with synchronized contact-force recording on both simulated and physical robots.
* Sampled 3,000 surface points with normals from the cone STL using `trimesh`, then calibrated to the robot base frame with an axis-constrained, translation-only ICP fit (cone axis pinned vertical to avoid a spurious tilt from apex-clustered touch points), reaching ~2.2 mm RMS alignment error.
* Generated full-surface and 20-strip vertical touch-pose patterns (10 points per strip) with height-scaled orientation tilt (7°–14°) for tool clearance, then executed them via a custom Python UR5 IK solver (needed because the controller's single-seed IK fails to converge for poses spread around the cone), streaming a single URScript program over the robot's secondary client port while the real-time state stream kept broadcasting the TCP pose.
* Synchronized ATI Nano17 force readings with the UR5's real-time TCP pose stream via NI-DAQ, auto-detecting each press and logging its peak force and pose for offline analysis.

{{ youtube(id="ED0S0Vk0w-s") }}
