---
title: "Batch-normalization-based soft filter pruning for deep convolutional neural networks"
collection: publications
permalink: 
excerpt: 'As convolutional neural network contains many redundant parameters, a lot of methods have been developed to compress the network for accelerating inference. Among these, network pruning, which is a kind of widely used approaches, can effectively decrease the memory capacity and reduce the computation cost. Herein, we propose a competitive pruning approach based on Soft Filter Pruning (SFP) by taking account of the scaling factors y of Batch Normalization (BN) layers as the criterion of filter selection strategy. During the soft pruning procedure, in each epoch only y values of BN layers less than threshold are set to zero instead of setting the weights of selected filters in convolutional layers to zero. Compared to the existing approaches, the proposed method can obtain a highly increased accuracy on image recognition. Notably, on CIFAR-10, the proposed method reduces the same 40.8% FLOPs as SFP on ResNet-110 with even 0.87% top-1 accuracy improvement.'
date: 2020-12-13
venue: '2020 16th International Conference on Control, Automation, Robotics and Vision'
paperurl: 'https://ieeexplore.ieee.org/abstract/document/9305481'
citation: 'X Xu, <b>Q Chen</b>, L Xie, H Su. <i>International Conference on Control, Automation, Robotics and Vision</i>. (2020).'
---
