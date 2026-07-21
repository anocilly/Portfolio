---
layout: project
title: Relative Pose Estimation
description: Point Cloud based relative pose estimation using LiDAR and camera data.
image: /assets/images/VLP16.jpg
---

In summer 2025 after my freshman year of college, I joined Professor Sanyal's Autonomous Unmanned Systems Laboratory at Syracuse University.
I worked primarily with the VLP-16 LIDAR sensor, gathering point cloud data of my surroundings in various locations. These point clouds were outputted in xyz Cartesian coordinates, allowing me to analyze the data and develop a relative pose estimation algorithm.
Essentially, these algorithms (written in MATLAB) would allow me to estimate the relative change in position and orientation of the sensor between two different point clouds. This is a crucial step in autonomous navigation, as it allows a robot to understand how it has moved through its environment based on sensor data.
For example, I would focus on a chair in a room and continuously record point clouds after roll, pitch, and yaw rotations of the sensor, resulting in multiple "frames" of xyz point clouds.
I wrote five different algorithms, each implementing different methods of estimating relative orientation between frames.

Below are several examples of my work and two of the weekly presentations I made to the lab. The first presentation is a general overview of my work, while the second presentation focuses on a specific algorithm I developed and its performance.

Example sensor output:
![Chair PC]({{ '/assets/images/origin.png' | relative_url }}){: style="width:100%; display:block;" }

Presentation 1
<iframe
    src="{{ '/assets/FirstResults.pdf' | relative_url }}"
    width="100%"
    height="600px">
</iframe>

Presentation 2
<iframe
    src="{{ '/assets/ICP.pdf' | relative_url }}"
    width="100%"
    height="600px">
</iframe>

Animation of the ICP algorithm in action (Presentation 2)
<video width="100%" height="auto" controls>
    <source src="{{ '/assets/icp testing bunny.mp4' | relative_url }}" type="video/mp4">
    Your browser does not support the video tag.
</video>