---
layout: page
title: "ScrubBot: Autonomous Field Cleaning"
description: a robotic solution for cleaning a field where obstacles present
img: https://media.githubusercontent.com/media/xinjie-liu/xinjie-liu.github.io/main/assets/img/Husky_obstacle.gif
importance: 2
category: past
---


## About 

This is a project in collaboration with the industry. The objective is to cover a field as fast as possible, where static and dynamic obstacles may present. 
We built a robotic solution with modules including perception, global path planning, local motion planning and control and state machine. The software is wrapped in ROS framework and tested in simulation and on a real Husky robot. 
We used only a top-view camera as the sensor for localization and mapping. The global shortest path planning is done by solving travelling salesman problems (TSP) combined with A* algorithm. For local motion planning and control, a non-linear MPC is deployed. 

The project was along with the course *RO47007 Multi-disciplinary Project* at Delft University of Technology. The final grade for this project was 9.7/10 (top 1 in the class).


<!-- {:refdef: style="text-align: center;"} -->
![husky_obstacle](https://media.githubusercontent.com/media/xinjie-liu/xinjie-liu.github.io/main/assets/img/Husky_obstacle.gif){: width="600"}
<!-- {: refdef} -->

![husky_simulation](https://media.githubusercontent.com/media/xinjie-liu/xinjie-liu.github.io/main/assets/img/husky_simulation.gif){: width="600"}

## Report & Code

Due to the non-disclosure agreement (NDA), the full-text report cannot be published online. But the package for the motion control module will be available soon.

## Supplementary Video

<iframe width="880" height="495" src="https://www.youtube.com/embed/hZuqNEBZi00" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
