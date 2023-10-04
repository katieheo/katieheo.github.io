# Planned revisions to reproduction of the Chakraborty Study on COVID-19 (2021)

Author: Katie Heo

## Analysis

I will be working on ... 

1. The final chloropleth map has a mistaken parameter causing it to only use half of the available color ramp. This is important to fix as it is a data visualization problem that makes it difficult for readers to see the five different shades of orange that represent the race model weights.

2. Moving the "rationale for the updated report" to the very end
This is important as currently, the rationale is positioned before the discussion. It is more sensical for the rationale to be at the end of a study as its purpose is to convince the readers of the necessity and importance of the research.

3. Improving the formatting of the missing data table (Section: Missing Data)
The formatting of the missing data table is necessary to better reading and understanding of the study. The data table is currently extending to outside of the page so transposing the variables to create a vertical table might be a method to fix this problem. 

4. Integrating discussion with the original study

5. Separating a conclusions section from the discussion that concludes whether the reproduction attempt was successful, and what the implications are for how the original study contributes to scientific knowledge.

6. Coming up with four different versions of the final chloropleth map (ethnicity, poverty status, age, and biological sex) to see the pattern of similarities and differences in their GEE model maps versus the Race Model Weights. 


## Results

1. This is a data visualization problem that can be fixed by changing the argument **midpoint**. The midpoint in the original study was set to the default of 0. Hence, the original map only reflected the darker shades of orange of the diverging color scale, making it hard for readers to differentiate the five different shades of orange that the map was supposed to represent. As the Race Model Weights vary between 0.027 and 1, I will choose the mean of 0.51 (rounded to the nearest hundredth) to represent the midpoint. By doing this, I was able to better visualize the data for the Race Model Weights.

2. I will move the rationale's position to the bottom. 

3. I will improve the formatting of the missing data table with Kable and KableExtra functions. I will also transpose the table to vertical orientation.

4. I will integrate our conclusion with the original study's conclusion.  

5. I will separate a conclusions section from the discussion.

6. I will map each county's weight in GEE model for ethnicity, poverty status, age, and biological sex like the GEE model mapped for race in the original study. 


## Discussion

1. If my revised map shows a fairer divide of the orange color ramp, it means that I correctly interpreted the argument midpoint in R. It would also mean that there is a better visualization of data in the map.

2. The revised study would improve the flow of the study for an easier read. Moving the rationale's position to the bottom will help wrap back to the importance of the research.

3. If the table is transposed vertically and the missing data table is sorted, it will be easier for the reader to understand what we are trying to convey with the table.

4. Integrating our conclusion with the original study will help understand the importance of replicability. This will help synthesize the findings we found and think about their implications.

5. Having a clear separation between the conclusion and the discussion will help see whether the reproduction attempt was successful, and what the implications are for how the original study contributes to scientific knowledge.

6. After comparing the different chloropleth maps, I will be able to tell whether the Race Model Weights is a representative map of all five maps. If not, I should be able to note differences in the map and infer why they exist. 
