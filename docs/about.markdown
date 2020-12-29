---
layout: page
title: Camera Motion Classification Based on 3D ResNet with Attention Module
permalink: /about/
---

<div align='center' ><font size='15'><b>Camera Motion Classification Based on 3D ResNet with Attention Module</b></font></div>

## Abstract

Camera motion classification is a classic task in computer vision. Recent existing methods always take two consecutive frames as input to classify the camera motion and then a post-processing is applied to classify the camera motion of the video segment. However, most of them only utilize motion vectors to analyze the camera motion, which makes them usually fail when there are large motion objects. In this paper, a deep learning based method is proposed to classify the camera motion directly from the input video segment in an end to end manner. To reduce the ambiguity caused by motion objects, an efficient attention module with consistent constraints is designed and combined with the base network. The attention module is used to explicitly generate a soft attention mask that makes the network pay more attention to stationary objects than motion objects. Specifically, 3D convolutional neural networks (3D CNN) is adopted as the base network to extract spatio-temporal features directly from video segments. Besides, the proposed method treats the camera motion classification task as a multi-label classification problem. As such, it can recognize the combination of basic camera operations. For performance evaluation, a challenging dataset consisting of 1,954 video segments is built, which includes various real-world scenes. All the video segments are manually annotated with seven basic categories of camera motions in the form of multiple labels. Finally, extensive experimental results show that the proposed deep learning based method achieves a better performance than recent state-of-the-art methods in terms of efficiency and effectiveness.

## Dataset

<center class="half">
<img src="https://github.com/FunnyDragonK/cm.github.io/blob/gh-pages/pics/data_distribution_all.png" width="200"/>
<img src="https://github.com/FunnyDragonK/cm.github.io/blob/gh-pages/pics/cctv_news.png" width="200"/>
<img src="https://github.com/FunnyDragonK/cm.github.io/blob/gh-pages/pics/cctv_sports_channel.png" width="200"/>
</center>

<center>Fig. 1. Distribution and the various scenes of the dataset.</center>

link: comming soon

