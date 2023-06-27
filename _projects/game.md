---
layout: page
title: "Adaptive Game-Theoretic Planning"
img: assets/img/highway_cover.png
description: adaptive game-theoretic planning enabled by a differentiable game solver
importance: 1
category: Research projects
---

## News

* **2023-04-17** This work has been accepted at RA-L and will be presented at IROS 2023. See you in Detroit!

* **2023-01-24** I gave an invited talk at [Princeton](https://saferobotics.princeton.edu/), \[[slides](https://xinjie-liu.github.io/static/talks/liu2023learning.pdf)\]. Thanks for the invitation!

* **2022-12-01** We submitted this work and published the [preprint](https://arxiv.org/abs/2211.13779) version!

---

## About 

This is the first project of my master's thesis. The work is with [Lasse Peters](https://lasse-peters.net/) and [Prof. Javier Alonso-Mora](https://www.autonomousrobots.nl/index.html). I developed an adaptive game solver that jointly estimates agents' objectives using gradient and solves for generalized Nash equilibrium strategies in non-cooperative dynamic games for safe interaction.

## Abstract

Many autonomous agents, such as intelligent vehicles, are inherently required to interact with one another. Game theory provides a natural mathematical tool for motion planning in such interactive settings. However, tractable algorithms for such problems usually rely on a strong assumption, namely that the objectives of all players in the scene are known. To make such tools applicable for ego-centric planning with only local information, we propose an adaptive model-predictive game solver, which jointly infers other players' objectives online and computes a corresponding generalized Nash equilibrium (GNE) strategy. The adaptivity of our approach is enabled by a differentiable trajectory game solver whose gradient signal is used for maximum likelihood estimation (MLE) of opponents' objectives. This differentiability of our pipeline facilitates direct integration with other differentiable elements, such as neural networks (NNs). Furthermore, in contrast to existing solvers for cost inference in games, our method handles not only partial state observations but also general inequality constraints. In two simulated traffic scenarios, we find superior performance of our approach over both existing game-theoretic methods and non-game-theoretic model-predictive control (MPC) approaches. We also demonstrate our approach's real-time planning capabilities and robustness in two hardware experiments.

## Paper


<a href ="https://arxiv.org/abs/2211.13779"><img src="/assets/img/liu2023ral_teaser.png"></a>

## Slides

<a href ="https://xinjie-liu.github.io/static/talks/liu2023learning.pdf"><img src="/assets/img/liu2023learning_cover.png" width = "560" height = "315"></a>

## Supplementary Video

<iframe width="560" height="315" src="https://www.youtube.com/embed/f0KJuCC1Xyo" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

