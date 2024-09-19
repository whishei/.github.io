---
layout: archive
title: ""
permalink: /talks/
author_profile: true
---
# Talks 

## Learning microstructure–property relationships in materials with robust features from vision transformers
### Talk at CVPR 2024
#### Authors: Sheila E. Whitman, Guangyu Hu & Marat I. Latypov
Machine learning of microstructure–property relationships from data is an emerging approach in computational materials science. Most existing machine learning efforts focus on the development of task-specific models for each microstructure–property relationship. We propose utilizing a pre-trained foundational vision model for the extraction of task-agnostic microstructure features and subsequent lightweight machine learning. We demonstrate our approach with a pre-trained DinoV2 model on unsupervised representation of an ensemble of two-phase microstructures and modeling of their overall elastic stiffness. Our results show the potential of foundational vision models for robust microstructure representation and efficient machine learning of microstructure–property relationships without the need for expensive task-specific training or fine-tuning.

Check out the recording of my presentation here: [Youtube](https://youtu.be/T9H2UkTeOxE?si=Zyx4AYppiD5KhPGz&t=7047). 

## Computer Vision for Process–Structure-Property Relationships in Materials
### Talk at Los Alamos - Arizona Days Spring 2024
#### Authors: Sheila E. Whitman, Guangyu Hu, Hunter C. Taylor, Ryan B. Wicker & Marat I. Latypov
We present a new computational approach for large-scale segmentation and spatially-resolved analysis of melt pools in complex 3D printed parts and qualification artifacts. Our hybrid segmentation includes human-in-the-loop image processing of a few representative optical images of melt pools that are then used for training machine learning models for automated segmentation of melt pool boundaries in large parts. Our approach specifically targets minimizing the need for manual annotation. Considering imperfect segmentation and errors unavoidable with most algorithms, we further propose chord length distribution as a statistical description of melt pool sizes relatively tolerant to segmentation errors. We first show and validate our new approach on optical images of melt pools in a simple 3D printed plate sample (IN718 alloy) as well as selected regions of a complex qualification artifact (AlSi10Mg alloy). We then demonstrate the application of our approach on an entire cross section of the artifact.

## Accuracy and Computational Cost of Semi-Extrapolated Finite Difference Schemes 
### Poster Presentation at APS Division of Fluid Dynamics Meeting 2019
#### Authors: Sheila Whitman, Mikayla Feldbauer, Narshini Gunputh, Andrew Brandon
When numerically solving partial differential equations, finite difference methods are a popular choice. Several factors come into play when choosing a finite difference method, such as stability, accuracy, and computational cost. In response to the small stability regions of explicit methods and the computational cost of implicit methods, we've developed a novel discretization technique called semi-extrapolation. Semi-extrapolation generates explicit schemes from implicit schemes by applying extrapolation in an unconventional fashion. Semi-extrapolation can improve stability, however, we've also found that semi-extrapolation can have unexpected and interesting effects on accuracy. In our presentation, we'll introduce our semi-extrapolation technique and discretize the Advection Equation and the Advection-Diffusion Equation according to semi-extrapolated and mainstream finite difference methods. Then, we'll examine the computational costs and accuracies of semi-extrapolated methods. Included in this examination will be a comparison against the costs and accuracies of mainstream methods and a discussion regarding how stability influences the accuracy of semi-extrapolated schemes.

## Semi-Extrapolated Finite Difference Schemes: Accuracy and Consistency 
### Poster Presentation at APS Division of Fluid Dynamics Meeting 2018
#### Authors: Sheila Whitman, Mikayla Feldbauer, Andrew Brandon
When solving partial differential equations, finite difference methods are a popular choice. Several factors come into play when choosing a finite difference method, such as stability, computational cost, accuracy, and consistency. In response to the small stability regions of explicit methods and the computational cost of implicit methods, we’ve developed a novel discretization technique (semi-extrapolation) that generates explicit schemes from implicit schemes by applying extrapolation to the implicit schemes in an unconventional fashion. Semi-extrapolating can lead to improved stabilities as compared to the stabilities of analogous explicit schemes, however, consistency and accuracy can be affected by semi-extrapolation. In our presentation, we’ll discuss our semi-extrapolation technique and introduce several semi-extrapolated discretizations of the Advection Equation and the Advection-Diffusion Equation. We’ll then analyze the consistency of these semi-extrapolated discretizations, compare their accuracies against the accuracies of several common discretizations, and discuss how stability constraints and choice of extrapolation stencil both influence the consistency and accuracy of semi-extrapolated schemes.

