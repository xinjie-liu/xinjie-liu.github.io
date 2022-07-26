---
layout: page
title: "MPC Designing and Analysis"
description: a model predictive control approach design and analysis
# img: assets/img/mpc.gif
img: https://media.githubusercontent.com/media/xinjie-liu/xinjie-liu.github.io/main/assets/img/mpc.gif
importance: 1
category: "Other projects: control, planning, optimization"
---

## About 

This is a model-predictive controller designing project. We designed an MPC controller that enables non-holonomic mobile robots to avoid static and dynamic obstacles. We linearized system dynamics along the reference trajectory. For obstacle avoidance, we proposed a constraint in velocity-space and showed its effectiveness. Furthermore, we proved that the time-varying system is stable in a Lyapunov sense.

The project was along with the course *SC42125 Model Predictive Control* (instructor: Prof. Sergio Grammatico) at the Delft University of Technology. The final grade for this project was 10/10 (top 1 in the class).

![husky_simulation](https://media.githubusercontent.com/media/xinjie-liu/xinjie-liu.github.io/main/assets/img/mpc.gif){: width="600"}

## Paper & Code

<!-- TODO: cool responsive image -->

The code repository can be found [here](https://github.com/xinjie-liu/SafeMPC_ObstacleAvoidance)

The paper can be found [here](https://arxiv.org/abs/2207.12878)

## Supplementary Video

<iframe width="880" height="495" src="https://www.youtube.com/embed/nYDxWkKvzZ8" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>