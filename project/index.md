---
layout: page

title: Projects
---

## Seq-CALC: lightweight and robust deep loop detection for SLAM

* 03/2020 - 05/2020
* Institute of Artificial Intelligence and Robotics, Xi’an Jiaotong University
* Advisor: Prof. Pengju Ren

We propose a lightweight SLAM loop detection method based on deep learning. An unsupervised denoising auto-encoder network is trained to extract an image’s deep descriptor, which uses the projective-transformed images as input data, and HOG descriptor as the reconstruction object. Besides, we apply PCA to reduce the descriptor’s dimension, and combine linear query with fast approximate nearest neighbor search to further improve the efficiency. With the help of sequence match, we significantly improve its accurary. The results of experiments on NVIDIA TX2 demonstrate that, our Seq-CALC outperforms DBoW3 in terms of both accurary and efficiency on various challenging datasets. Its accuary is even close to NetVLAD under certain conditions. We open-source the C++ library of Seq-CALC, which can be conveniently embedded in any SLAM system.

[[Details](https://mingrui-yu.github.io/Seq-CALC/)] [[Code](https://github.com/Mingrui-Yu/Seq-CALC)] [[Thesis(in Chinese)](https://www.jianguoyun.com/p/DVqHhNIQ-9KLBxi40dkD)]


## Adaptive traffic signal control with deep reinforcement learning 

* 07/2018 - 06/2019
* Institute of Automation, Chinese Academy of Sciences
* Advisor: Prof. Yisheng Lv

Contents:
* Proposed a DRL algorithm that automatically learns an optimal policy to adaptively determine
phase duration.
* Proposed a phase sensitive neural network structure based on DDPG model.
* Developed some interesting training techniques.

## Image processing in color+depth based 3D vision systems

* 02/2018 - 11/2018
* Institute of Artificial Intelligence and Robotics, Xi’an Jiaotong University
* Advisor: Prof. Meng Yang

Contents:
* Depth-based stereoscopic image zooming.
* Extension and application of Depth No-Synthesis-Error model for view synthesis in 3D video.
* Color guided depth map restoration for synthesized view quality enhancement.

&emsp;

***

&emsp;

Some small pilot projects are listed here:

## A simple stereo SLAM system

This is a simple stereo SLAM system with a deep-learning based loop closure module ([Seq-CALC](https://github.com/Mingrui-Yu/Seq-CALC)). As a beginner of SLAM, I made this system mainly in order to practice my coding and engineering skills to build a full SLAM system by myself. The structure of the system is simple and clear, in which I didn't apply much detailed optimization. Thus, the performance of this system is not outstanding. Such a simple structure may be friendly for a SLAM beginner to study the body frame of a full SLAM system.

[[Details](https://mingrui-yu.github.io/A-Simple-Stereo-SLAM-System/)] [[Code](https://github.com/Mingrui-Yu/A-Simple-Stereo-SLAM-System)]


## An Intelligent Car based on Raspberry Pi

In this curriculum project, we utilize Raspberry Pi 3 and some other accessories to design a simple intelligent car. The functions we have implemented include obstacle avoidance, video transmittion from Pi to PC, lane tracking, object detection, and tennis tracking.

[[Details](https://mingrui-yu.github.io/RaspberryCar/)] [[Code](https://github.com/Mingrui-Yu/RaspberryCar)]

