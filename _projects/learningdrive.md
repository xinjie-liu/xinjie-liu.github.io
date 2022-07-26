---
layout: page
title: "Learn Driving Policy from Pixels"
description: Imitation learning driving policies from image observations
img: https://media.githubusercontent.com/media/xinjie-liu/xinjie-liu.github.io/main/assets/img/learningdrive.gif
importance: 5
category: past
---

## About

We formulate an autonomous racing game with discrete action space as a classification problem and use the imitation learning technique to solve it. The robot has raw images as observations. We design a feature extractor that can extract edge information from the pixels. After feature extraction, we perform principal component analysis (PCA) for dimensionality reduction. As a result, the extracted feature vector is in a much lower dimensional space, is robust against the background colour, and can generalize to unseen datasets.

The project was along with the course *RO47002 Machine Learning for Robotics* (instructor: Prof. Jens Kober) at the Delft University of Technology. The final grade for this course was 9.1/10 (top in the class, no concrete statistics).

## Supplementary Video

<iframe width="880" height="495" src="https://www.youtube.com/embed/6-MJtegZLAw" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>