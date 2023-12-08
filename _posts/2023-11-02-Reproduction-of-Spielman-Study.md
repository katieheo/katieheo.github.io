---
title: "Evaluating SoVI Validity in a Reanalysis of Spielman et al.'s 2020 Study"
excerpt_separator: "<!--more-->"
categories:
  - Study
tags:
  - GIS
  - Science
  - Open Source
---

In our study of ["Evaluating social vulnerability indicators: criteria and their application to the Social Vulnerability Index"](https://link.springer.com/article/10.1007/s11069-019-03820-z) by Seth E. Spielman et al., we aimed to replicate and evaluate the Social Vulnerability Index (SoVI) model. Spielman et al. originally sought to assess the internal and theoretical consistency of the SoVI, a widely used measure of social vulnerability to environmental hazards. They conducted their study by replicating the SoVI model for different geographic extents, and we attempted to reproduce their results. 

One significant aspect of [our reproduction study](https://katieheo.github.io/RPl-Spielman-2020/) is the importance of adjusting the SoVI construction to weight the components by the percentage of variance explained by each variable in the Principal Component Analysis (PCA). This weighting scheme aimed to emphasize the importance of each component in the SoVI model. By using the percent variance to weight the factors, we sought to **visualize** and **gain a better understanding** of how PCA and the SoVI method works. By doing this, we also address potential shortcomings in the original model and enhance the theoretical consistency of the SoVI. However, our weighting method did not improve the internal consistency of the model. It is important to note that while our model did show some improvement in consistency, SoVI issues with consistency may not be due to being falsely weighted. This emphasizes the challenges associated with improving the SoVI.

The findings from our study are consistent with Spielman's original work, but still highlight the ongoing issues of internal and theoretical consistency within the SoVI model. The challenges we encountered during the reproduction process also shed light on the importance of transparent and reproducible research practices, such as providing clear code, data, and metadata, using up-to-date packages, and eliminating extraneous information from the analysis. However, our results present questions on the SoVI model's ability to process geographic threats to validity. Since vulnerability differs according to geographic context, the generalized model may not be appropriate for studying specific areas. 

Here are the links to.. 

[My research compendium](https://github.com/katieheo/RPl-Spielman-2020)

[The original study by Spielman et al.](https://link.springer.com/article/10.1007/s11069-019-03820-z)

[Our reproduction study of Spielman et al.](https://katieheo.github.io/RPl-Spielman-2020/)

*Find more information about the class I am taking [**here**](https://opengisci.github.io)!*
