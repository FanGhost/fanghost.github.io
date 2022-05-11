---
title: "Collaborative filtering via heterogeneous neural networks"
collection: publications
permalink: /publication/2021-asoc-Collaborative
excerpt: 'Over the last few years, the deep neural network is utilized to solve the collaborative filtering problem, a method of which has achieved immense success on computer vision, speech recognition as well as natural language processing. On one hand, the deep neural network can be used to capture the side information of users and items. On the other hand, it is also capable of modeling interactions between users and items. Most of existing approaches exploit the neural network with solo structure to model user-item interactions such that the learning representation may be insufficient over the extremely sparse rating data. Recently, a large number of neural networks with mixed structures are devised for learning better representations. A carefully designed hybrid network is able to achieve considerable accuracy but only requires a small amount of extra computation. In order to model user-item interactions, we elaborate a hybrid neural network consisting of the global neural network and several local neural blocks. The multi-layer perceptron is adopted to build the global neural network and the residual network is used to form the local neural block which is inserted into two adjacent global layers. The hybrid network is further combined with the generalized matrix factorization to capture both the linear and nonlinear relationships between users and items. It is verified by experimental results on benchmark datasets that our method is superior to certain state-of-the-art approaches in terms of top-n item recommendation.'
date: 2021-06-01
venue: 'Journal 1'
paperurl: 'http://fange.pro/files/2021Collaborative.pdf'
citation: 'Wei Zeng, Ge Fan, et al. Collaborative filtering via heterogeneous neuralnetworks." Applied Soft Computing: 1-15.'

---
In order to model user-item interactions, we design a hybrid neural network where the MLP is used to build the global network and the residual network is applied to form the local neural blocks. Two top-n accuracy metrics are selected to measure the performance of algorithms since the accuracy of top-n item recommendation are the main concern for users in the real world applications.
<!-- ![Model Mothed](../images/paper/2018LCR.png) -->

[Download paper here](http://fange.pro/files/2021Collaborative.pdf)
