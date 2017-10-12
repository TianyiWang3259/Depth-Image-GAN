# Depth Image Super Resolution using Cycle-GAN
----------------------------------------
## Team Member
Tianyi Wang (TianyiWang3259)
## Goals
The depth images acquired by commerical RGBD camera (Intel F200, SR300) have very low accuracy and quality compared with the depth images from professional depth camera [[1](https://www.spiedigitallibrary.org/conference-proceedings-of-spie/10220/1022005/High-speed-high-accuracy-large-range-3D-measurement/10.1117/12.2262680.short)]. So the goal of this project is to train a generative adversial network that can transfer the low quality depth image into high qualith depth image by using the method of cycle-gan [[2](https://arxiv.org/pdf/1703.10593.pdf)].
## Challenges
1. Image aquisition and dataset establish.
2. Implementation of cycle GAN network.
3. Adjustment of training parameters.
