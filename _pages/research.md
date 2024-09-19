---
layout: archive
title: ""
permalink: /research/
author_profile: true
---

{% include base_path %}

# Research Focus Areas

Generally, my research focuses at the intersection of applied mathematics and materals science. Specifically, I utilize machine learning, computer vision, and natural language proceessing techniques to acceelerate the materials design process.

## Microstructure - Processing - Property Relationships
One of the key challenges in materials science is understanding and modeling the relationships between processing, microstructure, and properties to design materials with desired characteristics. My current research focuses on modeling the microstructure-property relationships using machine learning. Traditional methods, such as statistical techniques and convolutional neural networks, face limitations—statistical methods often require precise segmentation, while CNNs demand extensive microstructure data. To address these challenges, I am exploring the use of vision transformers, leveraging pre-trained models like DinoV2 to efficiently extract task-agnostic features from microstructure images. This approach aims to enhance the prediction of material properties, such as elastic stiffness, without the need for expensive, task-specific training or fine-tuning, ultimately advancing the efficiency and effectiveness of the materials design process. In the future, we aim to extend this work by including compositions and processing conditions to improve the prediction accuracy.

I presented this work at the Computer Vision for Materials Science Workshop at CVPR 2024. Check out my [slides](https://whishei.github.io/files/CVPR_presentation.pdf) here!

## Spatially-Resolved Chord Length Distributions 
In my preprint,[SR-CLD: spatially-resolved chord length distributions for statistical description, visualization, and alignment of non-uniform microstructures](https://arxiv.org/abs/2409.03729), we introduce the calculation of spatially-resolved chord length distribution (SR-CLD) as an efficient approach for quantifying and visualizing non-uniform microstructures in heterogeneous materials. SR-CLD enables detailed analysis of spatial variation of microstructure constituent sizes in different directions that can be overlooked with traditional descriptions. We present the calculation of SR-CLD using efficient scan-line algorithm that counts pixels in constituents along pixel rows or columns of microstructure images for detailed, high-resolution SR-CLD maps. We demonstrate the application of SR-CLD in two case studies: one on synthetic polycrystalline microstructures with known and intentionally created uniform and gradient spatial distributions of grain size; and one on experimental images of two-phase microstructures of additively manufactured Ti alloys with significant spatially non-uniform distributions of laths of one of the phases. Additionally, we present how SR-CLDs can enable automated, computationally efficient, and robust alignment of large sets of images for merging into accurate composite images of large microstructure areas.

## Automated Segmentation
In my publication,[Automated segmentation and chord length distribution of melt pools in complex 3D printed metal artifacts](https://link.springer.com/article/10.1007/s40192-023-00329-z), we present a new hybrid approach for large-scale segmentation and spatially- resolved analysis of melt pools in complex 3D printed parts and qualification artifacts. Our hybrid segmentation approach includes human-in-the-loop image processing of a few representative optical images of melt pools that are then used for training machine learning models for automated segmentation of melt pool boundaries in large parts. Our approach specifically targets minimizing the need for manual annotation. Considering imperfect segmentation and errors unavoidable with most algorithms, we further propose chord length distribution (CLD) as a statistical metric of melt pool size relatively insensitive to boundary segmentation errors. We first show and validate our new protocol on optical images of melt pools in a simple 3D printed plate sample (IN718 alloy) as well as selected regions of a qualification artifact (AlSi10Mg alloy). We then demonstrate the application of our approach on a large-area cross section of the entire artifact.





