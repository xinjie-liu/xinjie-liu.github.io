---
layout: page
title: "Multi-Sensor Perception of Intelligent Vehicles"
description: pedestrian and obstacle detection using multi-sensor information
img: https://media.githubusercontent.com/media/xinjie-liu/xinjie-liu.github.io/main/assets/img/perception.gif
importance: 4
category: past
---

## About

In this project, I implemented algorithms for the perception of intelligent vehicles using multi-sensors such as LiDAR, Radar, and camera. For performance, I did point cloud processing and clustering. The processed point cloud was used as a prior for efficient region proposal for the visual detector. For frame transformation, the iterative closest point (ICP) was used for the ego-motion compensation of the vehicle. Besides, I implemented a ROS package for intelligent vehicles. 

The project was along with the course *RO47005 Machine Perception* (instructor: Prof. Dariu Gavrila) at the Delft University of Technology. The final grade for this project was 9.5/10 (top 2 in the class).

![husky_simulation](https://media.githubusercontent.com/media/xinjie-liu/xinjie-liu.github.io/main/assets/img/perception.gif){: width="600"}

![husky_simulation](https://media.githubusercontent.com/media/xinjie-liu/xinjie-liu.github.io/main/assets/img/intelligentvehicle.gif){: width="600"}



## Supplementary Video

<iframe width="880" height="495" src="https://www.youtube.com/embed/N3yv7vWhbWE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

<iframe width="880" height="495" src="https://www.youtube.com/embed/xyQBc3VUO2U" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>