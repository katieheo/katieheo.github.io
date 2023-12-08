---
title: "Reanalyzing Vulnerability in Malcomb et al.'s 2014 Study"
excerpt_separator: "<!--more-->"
categories:
  - Study
tags:
  - GIS
  - Science
  - Open Source
---

The choice of aggregation method depends on the specific context and objectives of a research, and one should carefully consider whether it aligns with the conceptual framework and goals of their vulnerability assessment. In this reanalysis of the original study on ["vulnerability modeling for sub-Saharan Africa: An operationalized approach in Malawi"](https://www.sciencedirect.com/science/article/abs/pii/S0143622814000058?via%3Dihub) by Malcomb et al., our primary objective was to reproduce the findings, and this process led us to consider alternative aggregation methods for assessing vulnerability. We carefully examined the implications of moving from an **additive vulnerability score**, as used in the original study, to a **geometric vulnerability score**. This transition represents a shift in how we understand and prioritize vulnerability.

[Our reproduction and reanalysis study](https://katieheo.github.io/RPr-Malcomb-2014/) implemented the geometric aggregation method to explore alternative aggregation methods to enhance the accuracy, validity, and utility of climate vulnerability assessments in Malawi. The original study used the **additive** method, which resulted in high vulnerability scores for most areas, making it challenging to identify regions with a vulnerability score of 0. Additionally, this approach assumes no interaction between the indicators and has issues with compensability. This means that a high value in one indicator can overshadow the significance of a low value, potentially leading to an incomplete understanding of vulnerability. Implementing a **geometric** aggregation method, on the other hand, allowed for a broader range of vulnerability scores including 0, a difference made particularly evident when examining the maps in Figures 5 and 6. This method acknowledges the interactions between the indicators and provides a more nuanced perspective on vulnerability. The additive method identified more regions in Malawi as highly vulnerable, whereas the geometric method predominantly highlighted the most vulnerable areas. In short, the geometric method emphasized the importance of addressing regions with more extreme vulnerabilities, which were overlooked when using an additive approach. The choice of aggregation method for vulnerability assessment is critical, as it can significantly impact the identification of vulnerable areas and influence resource allocation in Malawi and surrounding countries. 

The subjectiveness of the Malcomb et al. study is not only reflected in the approaches the researchers decided on but on various data collection methods and interpretation of the data. The original study's household data merely provides an estimated household location, the drought exposure data estimates the population that is exposed to drought not the region's drought risk, and the livelihood sensitivity indicators focus specifically on low-income households and does not represent all households in Malawi. Hence, researchers should carefully consider how their approaches may lead to incorrect estimations and then uncertainty. The study overall illustrates how decisions regarding the scale of analysis and data collection can introduce distortions into the understanding of real-world phenomena.

Here are the links to.. 

[My research compendium](https://github.com/katieheo/RPr-Malcomb-2014)

[The original study by Malcomb et al.](https://www.sciencedirect.com/science/article/abs/pii/S0143622814000058?via%3Dihub)

[Our reproduction study of Malcomb et al.](https://katieheo.github.io/RPr-Malcomb-2014/)

*Find more information about the class I am taking [**here**](https://opengisci.github.io)!*
