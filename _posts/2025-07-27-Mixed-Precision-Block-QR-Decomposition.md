---
layout: post
title: Mixed-precision Block QR Decomposition with CUDA
subtitle: University of Washington ECE Master's Project with Amazon Lab126
cover-img: /assets/img/path.jpg
thumbnail-img: /assets/img/thumb.png
share-img: /assets/img/path.jpg
---

This was my final project for my Master's in Electrical Engineering at the University of Washington, completed in 2024. I worked with a group of 6 graduate students to implement a parallel QR decomposition algorithm using CUDA. The project was a collaboration with Amazon Lab126 for development of Simultaneous Localization and Mapping (SLAM) for robotics. The QR decomposition can be used for least-squares optimization to solve for robot pose, a key part of SLAM algorithms.

We developed our algorithm targetting a PC with a GeForce RTX 2070 and Ubuntu installed. The algorithm was developed "from scratch" without the use of BLAS libraries (e.g. Cutlass). Here's a clip from one of our presentations, where I explain the mathematics.

<iframe width="560" height="315" src="https://www.youtube.com/embed/xfnWfB8IjI4?si=5o4oonn5AJcG-vv7" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
