---
layout: page
title: Experience
permalink: /experience/
---

## Summer Internship 2016 
*SURGE, IIT Kanpur*

I worked on Visual Question Answering under the guidance of [Dr. Gaurav Sharma](http://www.grvsharma.com/research.html).
Current state of the art methods use CNNs trained on the ImageNet task (VGGNet, GoogleNet,
 etc). These are independent of the text representation used. An image representation that is aligned with the text representation may improve the VQA performance of existing systems. 
The VQA baseline we used was the [*deeper LSTM + Normalized CNN*](https://github.com/VT-vision-lab/VQA_LSTM_CNN)  model from the original VQA dataset paper.
We used [*SkipThought vectors*](https://github.com/ryankiros/skip-thoughts) based sentence representation, and aligned the image 
representation with it. Two methods of alignment were explored:

* Supervised: Learnt a linear projection using triplet hinge loss and backpropagation
* Unsupervised: Learnt a linear projection using Canonical Correlation Analysis

We found that the aligned features were complementary to the original features, and a 
late fusion model obtained **1.5%** improvement over the baseline model. 

## Winter Internship 2014 
*HyperVerge Inc.*

I worked on developing modules for generating object proposals in images. I explored the prototypes (implemented a few) of state of the art models such as Selective Search, Multi-scale Combinatorial Grouping, Objectness, etc.
By evaluating their effectiveness on our specific scenarios, I selected the best model and
implemented it in C++ for testing on real time applications.

## Summer Internship 2014 
*HyperVerge Inc.*

Our team developed video surveillance modules for performing tasks such as background
subtraction and object tracking. In background subtraction, we implemented several models 
and evaluated them on the existing datasets. We further ported the best performing model on
CUDA, achieving the necessary speed for real-time applications. In object tracking, we
implemented a few existing models and evaluated them on datasets such as VOT2013, PETS2009, etc. 
