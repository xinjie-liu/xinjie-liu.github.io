---
layout: page
title: "Adaptive Game-Theoretic Planning"
img: assets/img/highway_cover.png
importance: 1
category: Research projects
---


## About 

This is the first project of my master's thesis (June 2022 - October 2022). The work is with [Lasse Peters](https://lasse-peters.net/) and [Prof. Javier Alonso-Mora](https://www.autonomousrobots.nl/index.html). I developed an adaptive game solver that jointly estimates agents' objectives using gradient and solves for generalized Nash equilibrium strategies in non-cooperative dynamic games for safe interaction.

<!-- ![husky_simulation](https://media.githubusercontent.com/media/xinjie-liu/xinjie-liu.github.io/main/assets/img/highway_inference.gif){: width="650"}

![husky_simulation](/assets/img/highway_traj.png){: width="650"}

![husky_simulation](https://media.githubusercontent.com/media/xinjie-liu/xinjie-liu.github.io/main/assets/img/jackal.gif){: width="650"} -->

## Abstract

<!-- Many autonomous agents, such as intelligent vehicles, are inherently required to interact with one another. Game theory provides a natural mathematical tool for robot motion planning in such interactive settings. However, tractable algorithms for such problems usually rely on a strong assumption, namely that the objectives of all players in the scene are known. To make such tools applicable for ego-centric planning with only local information, we propose an adaptive model-predictive game solver, which jointly infers other players' objectives online and computes a corresponding generalized Nash equilibrium (GNE) strategy. The adaptivity of our approach is enabled by a differentiable trajectory game solver whose gradient signal is used for maximum likelihood estimation (MLE) of opponents' objectives. This differentiability of our pipeline facilitates direct integration with other differentiable elements, such as neural networks (NNs). Furthermore, in contrast to existing solvers for cost inference in games, our method handles not only partial state observations but also general inequality constraints. In two simulated traffic scenarios, we find superior performance of our approach over both existing game-theoretic methods and non-game-theoretic model-predictive control (MPC) approaches. We also demonstrate our approach's real-time planning capabilities and robustness in two hardware experiments.  -->

Many autonomous agents, such as intelligent vehicles, are inherently required to interact with one another. Game theory provides a natural mathematical tool for robot motion planning in such interactive settings. However, tractable algorithms for such problems usually rely on a strong assumption, namely that the objectives of all players in the scene are known. To make such tools applicable for ego-centric planning with only local information, we propose an adaptive model-predictive game solver, which jointly infers other players' objectives online and computes a corresponding generalized Nash equilibrium (GNE) strategy. The adaptivity of our approach is enabled by a differentiable trajectory game solver whose gradient signal is used for maximum likelihood estimation (MLE) of opponents' objectives. This differentiability of our pipeline facilitates direct integration with other differentiable elements, such as neural networks (NNs). Furthermore, in contrast to existing solvers for cost inference in games, our method handles not only partial state observations but also general inequality constraints. In two simulated traffic scenarios, we find superior performance of our approach over both existing game-theoretic methods and non-game-theoretic model-predictive control (MPC) approaches. We also demonstrate our approach's real-time planning capabilities and robustness in two hardware experiments.

## Paper


<a href ="https://arxiv.org/abs/2211.13779"><img src="/assets/img/liu2023ral_teaser.png"></a>

## Supplementary Video

<iframe width="560" height="315" src="https://www.youtube.com/embed/YCjbeF9gd8k" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

<!-- Human-robot interaction experiment:

The robot actively infers the human's intention and tracks the human w.r.t. collision avoidance

<iframe width="560" height="315" src="https://www.youtube.com/embed/VhqwuZe9V0s" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe> -->

<!-- <iframe width="880" height="495" src="https://www.youtube.com/watch?v=kVon1kuIvjg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe> -->