---
layout: archive
title: ""
permalink: /publications/
author_profile: true
---
{% include base_path %}

# Peer-Reviewed Journal Papers

## * Automated segmentation and chord length distribution of melt pools in complex 3D printed metal artifacts
### Authors: Sheila E. Whitman, Guangyu Hu, Hunter C. Taylor, Ryan B. Wicker & Marat I. Latypov
We present a new computational approach for large-scale segmentation and spatially-resolved analysis of melt pools in complex 3D printed parts and qualification artifacts. Our hybrid segmentation includes human-in-the-loop image processing of a few representative optical images of melt pools that are then used for training machine learning models for automated segmentation of melt pool boundaries in large parts. Our approach specifically targets minimizing the need for manual annotation. Considering imperfect segmentation and errors unavoidable with most algorithms, we further propose chord length distribution as a statistical description of melt pool sizes relatively tolerant to segmentation errors. We first show and validate our new approach on optical images of melt pools in a simple 3D printed plate sample (IN718 alloy) as well as selected regions of a complex qualification artifact (AlSi10Mg alloy). We then demonstrate the application of our approach on an entire cross section of the artifact.
 
S.E. Whitman, G. Hu, H. C. Taylor, R. B. Wicker, M.I. Latypov, [Automated segmentation and chord length distribution of melt pools in complex 3D printed metal artifacts](https://link.springer.com/article/10.1007/s40192-023-00329-z) *Integrating Materials and Manufacturing Innovation* (2023).


## * SR-CLD: spatially-resolved chord length distributions for statistical description, visualization, and alignment of non-uniform microstructures
### Authors: Sheila E. Whitman, Marat I. Latypov
This study introduces the calculation of spatially-resolved chord length distribution (SR-CLD) as an efficient approach for quantifying and visualizing non-uniform microstructures in heterogeneous materials. SR-CLD enables detailed analysis of spatial variation of microstructure constituent sizes in different directions that can be overlooked with traditional descriptions. We present the calculation of SR-CLD using efficient scan-line algorithm that counts pixels in constituents along pixel rows or columns of microstructure images for detailed, high-resolution SR-CLD maps. We demonstrate the application of SR-CLD in two case studies: one on synthetic polycrystalline microstructures with known and intentionally created uniform and gradient spatial distributions of grain size; and one on experimental images of two-phase microstructures of additively manufactured Ti alloys with significant spatially non-uniform distributions of laths of one of the phases. Additionally, we present how SR-CLDs can enable automated, computationally efficient, and robust alignment of large sets of images for merging into accurate composite images of large microstructure areas.

S.E. Whitman, M.I. Latypov, [SR-CLD: spatially-resolved chord length distributions for statistical description, visualization, and alignment of non-uniform microstructures](https://arxiv.org/abs/2409.03729) *Submitted to Materials Characterization* (2024).

# Peer-Reviewed Conference Papers

## * Learning microstructure–property relationships in materials with robust features from vision transformers
### Authors: Sheila E. Whitman, Guangyu Hu & Marat I. Latypov
Machine learning of microstructure–property relation- ships from data is an emerging approach in computational materials science. Most existing machine learning efforts focus on the development of task-specific models for each microstructure–property relationship. We propose utilizing a pre-trained foundational vision model for the extraction of task-agnostic microstructure features and subsequent light- weight machine learning. We demonstrate our approach with a pre-trained DinoV2 model on unsupervised repre- sentation of an ensemble of two-phase microstructures and modeling of their overall elastic stiffness. Our results show the potential of foundational vision models for robust mi- crostructure representation and efficient machine learning of microstructure–property relationships without the need for expensive task-specific training or fine-tuning.

S.E. Whitman, G. Hu, M.I. Latypov, [Learning microstructure–property relationships in materials with robust features from vision transformers](https://openaccess.thecvf.com/content/CVPR2024W/CV4MS/papers/Whitman_Learning_Microstructure--Property_Relationships_in_Materials_with_Robust_Features_from_Vision_CVPRW_2024_paper.pdf) *Computer Vision for Materials Science - CVPR Workshop* (2024).














