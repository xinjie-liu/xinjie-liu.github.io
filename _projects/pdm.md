---
layout: page
title: "Autonomous Delivery"
description: motion planning and control for an autonomous quadrotor drone
img: https://media.githubusercontent.com/media/xinjie-liu/xinjie-liu.github.io/main/assets/img/rrt.gif
importance: 4
category: "Other projects: control, planning, optimization"
---

## About

This is a motion planning and control project for mobile robots. The objective is to use quadrotor drone robots for autonomous delivery. We realize autonomous navigation by implementing the global path search method RRT*. The path is smoothed by conducting minimum-snap optimization. 

We design a non-linear MPC controller as the local planner, which can avoid local obstacles while tracking the reference. The robot needs to deviate from the reference path when avoiding the local obstacles. The collision avoidance guarantee to the global static obstacles (the walls) is provided by real-time box constraints. We tested our method in several scenarios.

The project was along with the course *RO47005 Planning and Decision Making* (instructor: Prof. Javier Alonso-Mora) at the Delft University of Technology. The final grade for this project was 9.5/10 (top 1 in the class).

![husky_simulation](https://media.githubusercontent.com/media/xinjie-liu/xinjie-liu.github.io/main/assets/img/rrt.gif){: width="600"}

![husky_simulation](https://media.githubusercontent.com/media/xinjie-liu/xinjie-liu.github.io/main/assets/img/pdm.gif){: width="600"}

## Paper & Code

<!-- TODO: cool responsive image -->

The code repository can be found [here](https://github.com/xinjie-liu/PlanningDecisionMaking)

The paper can be found [here](https://www.researchgate.net/publication/358573208_Planning_Algorithm_for_a_Quadrotor_Drone)

## Supplementary Video

<iframe width="880" height="495" src="https://www.youtube.com/embed/opqHCWvAOwY" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
