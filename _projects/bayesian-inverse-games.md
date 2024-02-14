---
layout: page
title: "Bayesian Inverse Games"
img: assets/img/bayesian-inverse-games-partial.png
description: Multi-modal distribution inference, uncertainty, variational methods, differentiable programming
importance: 1
category: Research projects
---

## News


<!-- * **2022-12-01** We submitted this work and published the [preprint](https://arxiv.org/abs/2211.13779) version! --> 

---

## About 

TL;DR: We propose a method for tractable inference of unknown parameters in noncooperative games by embedding a differentiable game solver into a variational autoencoder, and we assess this method in the context of interactive robot motion planning.

## Abstract

When multiple agents interact in a common environment, each agent’s actions impact others’ future decisions, and noncooperative dynamic games naturally capture this coupling. In interactive motion planning, however, agents typically do not have access to a complete model of the game, e.g., due to unknown objectives of other players. Therefore, we consider the inverse game problem, in which some properties of the game are unknown a priori and must be inferred from observations. Existing maximum likelihood estimation (MLE) approaches to solve inverse games provide only point estimates of unknown parameters without quantifying uncertainty, and perform poorly when many parameter values explain the observed behavior. To address these limitations, we take a Bayesian perspective and construct posterior distributions of game parameters. To render inference tractable, we employ a variational autoencoder (VAE) with an embedded differentiable game solver. This structured VAE can be trained from an unlabeled dataset of observed interactions, naturally handles continuous, multi-modal distributions, and supports efficient sampling from the inferred posteriors without computing game solutions at runtime. Extensive evaluations in simulated driving scenarios demonstrate that the proposed approach successfully learns the prior and posterior objective distributions, provides more accurate objective estimates than MLE baselines, and facilitates safer and more efficient game-theoretic motion planning.

## Paper


<!-- <a href ="https://ieeexplore.ieee.org/document/10137879"><img src="/assets/img/liu2023ral_teaser.png"></a> -->

<!-- ```
@article{liu2022learning,
  title={Learning to Play Trajectory Games Against Opponents with Unknown Objectives},
  author={Liu, Xinjie and Peters, Lasse and Alonso-Mora, Javier},
  journal={IEEE Robotics and Automation Letters (RA-L)},
  year={2023}
}
``` -->

## Code

<!-- * [The original solver implementation used in this work and experiment code](https://github.com/xinjie-liu/DifferentiableAdaptiveGames.jl)

* [A more optimized implementation of the solver.](https://github.com/JuliaGameTheoreticPlanning/MCPTrajectoryGameSolver.jl) -->

<!-- ## Poster -->

<!-- <a href ="https://xinjie-liu.github.io/assets/pdf/Liu2023learningPoster(full).pdf"><img src="https://xinjie-liu.github.io/assets/img/liu2023ral_poster.png" width = "560" height = "396"></a> -->

<!-- ## Short Talk -->

<!-- <iframe width="560" height="315" src="https://www.youtube.com/embed/X_xMdyxNads?si=mTP2jUT5JiP1-dtg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe> -->

<!-- ## Slides -->

<!-- <a href ="https://xinjie-liu.github.io/static/talks/Xinjie2023TUD.pdf"><img src="/assets/img/Xinjie2023TUD-1.png" width = "560" height = "315"></a> -->


## Supplementary Video


<iframe width="560" height="315" src="https://www.youtube.com/embed/-PPLPH_yfmY?si=bdf5FWgP7nKqYMmp" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>



