---
layout: archive
title: ""
permalink: /research/
author_profile: true
---

{% include base_path %}

# Research Focus Areas

## Computer Vision
Generally, my research focuses at the intersection of applied mathematics and materals science. Specifically, I utilize computer vision techniques to acceelerate the materials design process. Here are some specific project examples to get a feel of my research:

### Automated Segmentation
In my first ever publication,[Automated segmentation and chord length distribution of melt pools in complex 3D printed metal artifacts,](https://link.springer.com/article/10.1007/s40192-023-00329-z), we present a new hybrid approach for large-scale segmentation and spatially- resolved analysis of melt pools in complex 3D printed parts and qualification artifacts. Our hybrid segmentation approach includes human-in-the-loop image processing of a few representative optical images of melt pools that are then used for training machine learning models for automated segmentation of melt pool boundaries in large parts. Our approach specifically targets minimizing the need for manual annotation. Considering imperfect segmentation and errors unavoidable with most algorithms, we further propose chord length distribution (CLD) as a statistical metric of melt pool size relatively insensitive to boundary segmentation errors. We first show and validate our new protocol on optical images of melt pools in a simple 3D printed plate sample (IN718 alloy) as well as selected regions of a qualification artifact (AlSi10Mg alloy). We then demonstrate the application of our approach on a large-area cross section of the entire artifact.

### Feature Extraction for Properties Prediction 
Machine learning of microstructure–property relationships from data is an emerging approach in computational materials science. Most existing machine learning efforts focus on the development of task-specific models for each microstructure–property relationship. We propose utilizing a pre-trained foundational vision model for the extraction of task-agnostic microstructure features and subsequent light-weight machine learning. We demonstrate our approach with a pre-trained DinoV2 model on unsupervised representation of an ensemble of two-phase microstructures and modeling of their overall elastic stiffness. Our results show the potential of foundational vision models for robust microstructure representation and efficient machine learning of microstructure–property relationships without the need for expensive task-specific training or fine-tuning.

I presented this work at the Computer Vision for Materials Science Workshop at CVPR 2024. Check out my [slides](https://whishei.github.io/files/CVPR_presentation.pdf) here!




