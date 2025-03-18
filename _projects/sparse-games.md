---
layout: page
title: "Sparse Policies in Noncooperative Games"
img: assets/img/sparse-games.png
description: Information sparsity, regularized dynamic programming, feedback Nash equilibrium
importance: 1
category: Research projects
---

## News

* **2024-10-22** We submitted this work and published a preprint version!




---

## About 

TL;DR: We propose a dynamic programming approach for computing sparse feedback policies that selectively depend on a subset of agents in noncooperative games. We prove the convergence of the approach and show the advantages of employing sparse policies.

<iframe width="560" height="315" src="https://www.youtube.com/embed/AouomX7v9WE?si=EJ8KiuBWxCamfYRG" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>


## Abstract

Common feedback strategies in multi-agent dynamic games require all players’ state information to compute control strategies. However, in real-world scenarios, sensing and communication limitations between agents make full state feedback expensive or impractical, and such strategies can become fragile when state information from other agents is inaccurate. To this end, we propose a regularized dynamic programming approach for finding sparse feedback policies that selectively depend on the states of a subset of agents in dynamic games. The proposed approach solves convex adaptive group Lasso problems to compute sparse policies approximating Nash equilibrium solutions. We prove the regularized solutions’ asymptotic convergence to a neighborhood of Nash equilibrium policies in linear-quadratic (LQ) games. We extend the proposed approach to general non-LQ games via an iterative algorithm. Empirical results in multi-robot interaction scenarios show that the proposed approach effectively computes feedback policies with varying sparsity levels. When agents have noisy observations of other agents’ states, simulation results indicate that the proposed regularized policies consistently achieve lower costs than standard Nash equilibrium policies by up to 77% for all interacting agents whose costs are coupled with other agents’ states.





## Paper

<a href ="https://arxiv.org/pdf/2410.16441"><img src="/assets/img/sparse_games_teaser.png"></a>

<!-- <a href ="https://arxiv.org/abs/2402.08902"><img src="/assets/img/liu2024wafr_teaser.png"></a> -->

<!-- <a href ="https://ieeexplore.ieee.org/document/10137879"><img src="/assets/img/liu2023ral_teaser.png"></a> -->

<!-- ```
@article{liu2022learning,
  title={Learning to Play Trajectory Games Against Opponents with Unknown Objectives},
  author={Liu, Xinjie and Peters, Lasse and Alonso-Mora, Javier},
  journal={IEEE Robotics and Automation Letters (RA-L)},
  year={2023}
}
``` -->

<!-- ## Poster -->

<!-- <a href ="https://xinjie-liu.github.io/assets/pdf/liu2024auto.pdf"><img src="https://xinjie-liu.github.io/assets/img/liu2024auto.png" width = "560" height = "396"></a> -->



## Code

Coming soon

<!-- [Repository Link](https://github.com/xinjie-liu/AutoEncodingBayesianInverseGames.jl) -->


<!-- ## Poster -->

<!-- <a href ="https://xinjie-liu.github.io/assets/pdf/Liu2023learningPoster(full).pdf"><img src="https://xinjie-liu.github.io/assets/img/liu2023ral_poster.png" width = "560" height = "396"></a> -->

<!-- ## Short Talk -->

<!-- <iframe width="560" height="315" src="https://www.youtube.com/embed/X_xMdyxNads?si=mTP2jUT5JiP1-dtg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe> -->

<!-- ## Slides -->

<!-- <a href ="https://xinjie-liu.github.io/static/talks/Xinjie2023TUD.pdf"><img src="/assets/img/Xinjie2023TUD-1.png" width = "560" height = "315"></a> -->






