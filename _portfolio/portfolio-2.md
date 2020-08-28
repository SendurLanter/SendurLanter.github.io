---
title: "FPGA High Level Synthesis: A Survey and Implementation on Operation Scheduling Algorithms"
excerpt: ' '
collection: portfolio
---
## Research background and motivation

High-level synthesis (HLS) mainly consists of three parts, inclusive of allocation, scheduling, and binding. Among them, scheduling is the most critical part of HLS. As a consequence, I decided to survey the recent development of scheduling algorithms. Nonetheless, since there are many design scenarios in the HLS, which will lead to different specialized algorithms, I will focus on the scheduling algorithm for general design in order to narrow down the topic. Then, I will also perform the implementation and experiments on the algorithms to compare the effectiveness of the recent general scheduling algorithm. 

## Comparison of existing scheduling algorithms

<img src="http://SendurLanter.github.io/files/Comparison.png" width="800" height="375">

## Simulation benchmark

<img src="http://SendurLanter.github.io/files/cosine2.png" width="500" height="375">

<img src="http://SendurLanter.github.io/files/invert.png" width="500" height="375">

## Performance

<img src="http://SendurLanter.github.io/files/Resource_mul.jpg" width="300" height="225">
<img src="http://SendurLanter.github.io/files/milti_mat.jpg" width="300" height="225">
<img src="http://SendurLanter.github.io/files/Runtime_inv.jpg" width="300" height="225">