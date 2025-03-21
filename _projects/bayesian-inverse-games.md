---
layout: page
title: "Auto-Encoding Bayesian Inverse Games"
img: assets/img/bayesian-inverse-games-partial.png
description: Multi-modal distribution inference, uncertainty, generative modelling, differentiable programming
importance: 2
category: Research projects
---

## News

* **2024-09-10** We published the [code](https://github.com/xinjie-liu/AutoEncodingBayesianInverseGames.jl) for this work.

* **2024-08-17** This work was accepted to WAFR 2024. See you in Chicago!



---

## About 

TL;DR: We propose a method for tractable inference of unknown parameters in noncooperative games by embedding a differentiable game solver into a variational autoencoder, and we assess this method in the context of interactive robot motion planning.

<iframe width="560" height="315" src="https://www.youtube.com/embed/hjb2GqbNIIE?si=5wr9hPFjPWe9RSZA" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>


## Abstract

When multiple agents interact in a common environment, each agent’s actions impact others’ future decisions, and noncooperative dynamic games naturally capture this coupling. In interactive motion planning, however, agents typically do not have access to a complete model of the game, e.g., due to unknown objectives of other players. Therefore, we consider the inverse game problem, in which some properties of the game are unknown a priori and must be inferred from observations. Existing maximum likelihood estimation (MLE) approaches to solve inverse games provide only point estimates of unknown parameters without quantifying uncertainty, and perform poorly when many parameter values explain the observed behavior. To address these limitations, we take a Bayesian perspective and construct posterior distributions of game parameters. To render inference tractable, we employ a variational autoencoder (VAE) with an embedded differentiable game solver. This structured VAE can be trained from an unlabeled dataset of observed interactions, naturally handles continuous, multi-modal distributions, and supports efficient sampling from the inferred posteriors without computing game solutions at runtime. Extensive evaluations in simulated driving scenarios demonstrate that the proposed approach successfully learns the prior and posterior objective distributions, provides more accurate objective estimates than MLE baselines, and facilitates safer and more efficient game-theoretic motion planning.


<img src="https://xinjie-liu.github.io/assets/img/liu2024wafr_demo.gif" alt="wafr demo" width="350" height="350">


## Paper

<a href ="https://arxiv.org/abs/2402.08902"><img src="/assets/img/liu2024wafr_teaser.png"></a>

<!-- <a href ="https://ieeexplore.ieee.org/document/10137879"><img src="/assets/img/liu2023ral_teaser.png"></a> -->

<!-- ```
@article{liu2022learning,
  title={Learning to Play Trajectory Games Against Opponents with Unknown Objectives},
  author={Liu, Xinjie and Peters, Lasse and Alonso-Mora, Javier},
  journal={IEEE Robotics and Automation Letters (RA-L)},
  year={2023}
}
``` -->

## Poster

<a href ="https://xinjie-liu.github.io/assets/pdf/liu2024auto.pdf"><img src="https://xinjie-liu.github.io/assets/img/liu2024auto.png" width = "560" height = "396"></a>



## Code

[Repository Link](https://github.com/xinjie-liu/AutoEncodingBayesianInverseGames.jl)


<!-- ## Poster -->

<!-- <a href ="https://xinjie-liu.github.io/assets/pdf/Liu2023learningPoster(full).pdf"><img src="https://xinjie-liu.github.io/assets/img/liu2023ral_poster.png" width = "560" height = "396"></a> -->

<!-- ## Short Talk -->

<!-- <iframe width="560" height="315" src="https://www.youtube.com/embed/X_xMdyxNads?si=mTP2jUT5JiP1-dtg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe> -->

<!-- ## Slides -->

<!-- <a href ="https://xinjie-liu.github.io/static/talks/Xinjie2023TUD.pdf"><img src="/assets/img/Xinjie2023TUD-1.png" width = "560" height = "315"></a> -->




