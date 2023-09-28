# Planned revisions to reproduction of ....

Author: Katie Heo

## Analysis

Enumerate and justify changes to analytical plan here

I will be working on the ... 

1. The final choropleth map as it has a mistaken parameter causing it to only use half of the available color ramp. This is important to fix as it is a data visualization problem that makes it difficult for readers to see the five different shades of orange that represent the race model weights. 

2. 

## Results

Describe how changes will be visualized / compared here

1. This is a data visualization problem that can be fixed by changing the argument **midpoint**. The midpoint in the original study was set to the default of 0. Hence, the original map only reflected the darker shades of orange of the diverging color scale, making it hard for readers to differentiate the five different shades of orange that the map was supposed to represent. As the Race Model Weights vary between 0.027 and 1, I will choose the mean of 0.51 (rounded to the nearest hundredth) to represent the midpoint. By doing this, I was able to better visualize the data for the Race Model Weights.

## Discussion

Describe how you will interpret the results of your changes here.
For example, in hypothetical terms, if my new/revised map shows ---, it will mean that ---.

1. If my revised map shows a fairer divide of the orange color ramp, it means that I correctly interpreted the argument midpoint in R. It would also mean that there is a better visualization of data in the map. 
