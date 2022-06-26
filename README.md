# School_District_Analysis

## Overview of the School District Analysis
The purpose of the School District Analysis was to analyze the data of an entire school district to provide clear results on school's performances. This analysis was performed twice due to potential academic dishonesty among 9th grade students at Thomas High School. The affect of omitting the dishonest data on the school district analysis is reviewed.

### Resources:
The data used for this analysis can be found inside the Resources folder provided.

Software: Python 3.7, Anacond, Jupyter Notebook

## Results

This analysis was run twice, once with the complete data set including all grades from all of the 15 highschools in the district, and again omitting the scores for the 9th grade class at Thomas High School due to academic dishonesty. The omission of the results of the 9th grade class did have affects on the overall analysis and outcome of the data for the school district as well as for Thomas High School. 

### How was district summary affected?

The district summary after omitting the Thomas High School 9th grade scores is shown below:

<img width="365" alt="District Analysis post THS edits" src="https://user-images.githubusercontent.com/105942622/175818391-901cbec8-2051-4f7b-b191-31c734f3138b.png">

This summary reflects a 0.2% decrease in Percent Passing Math, a 0.1% decrease in Percent Passing Reading , and a 0.3% decrease in Overall Passing Percentage across the entire school district due to the academic dishonesty of the 9th grade class at Thomas High School. 

### How was the school summary affected?
The percent passing math score dropped to 66.9%.
The percent passing reading score dropped to 69.7%.
The overall passing percentage for Thomas High School dropped to 65%
These drops in passing percentage for the whole school takes Thomas High School out of the top 5 schools and into the lower 5 schools when omitting the scores for the 9th grade class but still including them in the count of overall students. 

### How does replacing 9th grade math and reading affect Thomas High School's performance?
These drops in passing percentage for the whole school takes Thomas High School out of the top 5 schools and into the lower 5 schools when replacing the scores for the 9th grade class with "NaN" but still including them in the count of overall students. When omitting both the 9th grade grades and student count Thomas High School still remains in the top 5 schools. 

### How does replacing the 9th grade scores affect the following?

  **Math and reading scores by grade:**
  
  The math and reading score did not change and were not affected. The only different was that Thomas High School 9th grade was replaced with NaN
  
  *Updated Math Score*:

<img width="313" alt="2022-06-26 (4)" src="https://user-images.githubusercontent.com/105942622/175821199-97b78977-4484-433b-aa12-2e0b5e1c9133.png">

*Updated Reading Score*:

<img width="300" alt="2022-06-26 (5)" src="https://user-images.githubusercontent.com/105942622/175821230-784ed98c-0942-4f60-8cc2-7060c0556880.png">

  **Scores by school spending:**
  
*Original*:

<img width="565" alt="2022-06-26 (7)" src="https://user-images.githubusercontent.com/105942622/175821345-04282b4f-1dc3-453a-b389-6cbadeed70e8.png">

*Updated:

<img width="559" alt="2022-06-26 (6)" src="https://user-images.githubusercontent.com/105942622/175821313-bbbd9f9f-c9c5-4b62-b56b-d43bc6c3f829.png">

  Scores by school spending was not affected by the data change
  
  **Scores by school size**
  
*Original*:

<img width="511" alt="2022-06-26 (8)" src="https://user-images.githubusercontent.com/105942622/175821400-d51af195-6c79-4c8e-8277-e162fe08c793.png">

*Updated:*

<img width="511" alt="2022-06-26 (9)" src="https://user-images.githubusercontent.com/105942622/175821425-64dc02ea-1284-4315-ae95-5642f280b79f.png">

  Scores by school size was not significantly affected by the data change (< 1% change)
  
  **Scores by school type**

*Original*

<img width="481" alt="2022-06-26 (11)" src="https://user-images.githubusercontent.com/105942622/175821510-4bb353b4-9a28-47f6-99ec-b48264d823ca.png">


*Updated*

 <img width="496" alt="2022-06-26 (10)" src="https://user-images.githubusercontent.com/105942622/175821489-a24fcf6d-83ee-43ad-b5a2-ab1427bca42b.png">
 
There is a change in the charter school data because Thomas High School is a charter school. This change was not significant (<1%)

## Summary

There was no real change to the outcome of the data analysis in regards to district analysis, top school ranking, scores by school size, and score by school type when the data for the 9th grade class was completely omitted. The data was affected when the scores were replaced with the value NaN because the students were counted toward the total student body, thus decreasing the overall average of Thomas High School most drastically but also the school district. 



