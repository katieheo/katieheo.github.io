---
title: "Reanalysis of Malcomb Study 2014"
excerpt_separator: "<!--more-->"
categories:
  - Study
tags:
  - GIS
  - Science
  - Open Source
---

The choice of aggregation method depends on the specific context and objectives of a research, and one should carefully consider whether it aligns with the conceptual framework and goals of their vulnerability assessment. In this reanalysis of the original study on ["vulnerability modeling for sub-Saharan Africa: An operationalized approach in Malawi"](https://www.sciencedirect.com/science/article/abs/pii/S0143622814000058?via%3Dihub) by Malcomb et al., our primary objective was to reproduce the findings, and this process led us to consider alternative aggregation methods for assessing vulnerability. We carefully examined the implications of moving from an **additive vulnerability score**, as used in the original study, to a **geometric vulnerability score**. This transition represents a shift in how we understand and prioritize vulnerability.

[Our reproduction and reanalysis study](LINK) implemented the geometric aggregation method to explore alternative aggregation methods to enhance the accuracy, validity, and utility of climate vulnerability assessments in Malawi. The original study used the additive method, which resulted in high vulnerability scores for most areas, making it challenging to identify regions with a vulnerability score of 0. Implementing a geometric aggregation method, on the other hand, allowed for a **broader range** of vulnerability scores including 0, a diffference made particularly evident when examining the maps in Figures 5 and 6. The additive method identified more regions in Malawi as highly vulnerable, whereas the geometric method predominantly highlighted the most vulnerable areas. The choice of aggregation method for vulnerability assessment is critical, as it can significantly impact the identification of vulnerable areas and influence resource allocation in Malawi and surrounding countries.

*Find more information about the class I am taking [**here**](https://opengisci.github.io)!*
