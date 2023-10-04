# Planned revisions to reproduction of the Chakraborty Study on COVID-19 (2021)

Author: Katie Heo

## Analysis

Enumerate and justify changes to analytical plan here

I will be working on ... 

1. The final chloropleth map has a mistaken parameter causing it to only use half of the available color ramp. This is important to fix as it is a data visualization problem that makes it difficult for readers to see the five different shades of orange that represent the race model weights.

2. Moving the "rationale for the updated report" to the very end
This is important as currently, the rationale is positioned before the discussion. It is more sensical for the rationale to be at the end of a study as its purpose is to convince the readers of the necessity and importance of the research.

3. Improving the formatting of the missing data table (Section: Missing Data)
The formatting of the missing data table is necessary to better reading and understanding of the study. The data table is currently extending to outside of the page so transposing the variables to create a vertical table might be a method to fix this problem. 

5. Integrating discussion with the original study

6. Separate a conclusions section from the discussion that concludes whether the reproduction attempt was successful, and what the implications are for how the original study contributes to scientific knowledge.

7. The four different versions of the final chloropleth map (ethnicity, poverty status, age, and biological sex) to see the pattern of similarities and differences in their GEE model maps versus the Race Model Weights. This will help the readers see if the Race Model Weights is a representative map of all five maps. 


## Results

Describe how changes will be visualized / compared here

1. This is a data visualization problem that can be fixed by changing the argument **midpoint**. The midpoint in the original study was set to the default of 0. Hence, the original map only reflected the darker shades of orange of the diverging color scale, making it hard for readers to differentiate the five different shades of orange that the map was supposed to represent. As the Race Model Weights vary between 0.027 and 1, I will choose the mean of 0.51 (rounded to the nearest hundredth) to represent the midpoint. By doing this, I was able to better visualize the data for the Race Model Weights.

2. Moving the rationale's position to the bottom will help wrap back to the importance and need of the research.

3. 


## Discussion

Describe how you will interpret the results of your changes here.
For example, in hypothetical terms, if my new/revised map shows ---, it will mean that ---.

1. If my revised map shows a fairer divide of the orange color ramp, it means that I correctly interpreted the argument midpoint in R. It would also mean that there is a better visualization of data in the map.

2. The revised study would improve the flow of the study for an easier read.

