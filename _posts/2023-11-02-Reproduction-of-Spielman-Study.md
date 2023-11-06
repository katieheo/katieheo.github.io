---
title: "Reproduction of Spielman et al. Study 2020"
excerpt_separator: "<!--more-->"
categories:
  - Study
tags:
  - GIS
  - Science
  - Open Source
---

In our study of ["Evaluating social vulnerability indicators: criteria and their application to the Social Vulnerability Index"](https://link.springer.com/article/10.1007/s11069-019-03820-z) by Seth E. Spielman et al., we aimed to replicate and evaluate the Social Vulnerability Index (SoVI) model. Spielman et al. originally sought to assess the internal and theoretical consistency of the SoVI, a widely used measure of social vulnerability to environmental hazards. They conducted their study by replicating the SoVI model for different geographic extents, and we attempted to reproduce their results. 

One significant aspect of [our reproduction study](https://katieheo.github.io/RPl-Spielman-2020/) is the importance of adjusting the SoVI construction to weight the components by the percentage of variance explained by each variable in the Principal Component Analysis (PCA). This weighting scheme aimed to emphasize the importance of each component in the SoVI model. By using the percentage of variance, we sought to address **potential shortcomings** in the original model and enhance the internal and theoretical consistency of the SoVI. However, it's important to note that while the weighted SoVI model did show some improvement in consistency, it didn't fundamentally change the original SoVI model. This emphasizes the challenges associated with improving the SoVI, which inherently depends on the weights assigned by PCA.

The findings from our study are **consistent** with Spielman's original work, highlighting the ongoing issues of **internal and theoretical consistency** within the SoVI model. The challenges we encountered during the reproduction process also shed light on the importance of transparent and reproducible research practices, such as providing clear code, data, and metadata, using up-to-date packages, and eliminating extraneous information from the analysis. While we succeeded in reproducing the results, these efforts to enhance reproducibility can further improve the **transparency** and **accessibility** of research in the field of geography.

*Find more information about the class I am taking [**here**](https://opengisci.github.io)!*
