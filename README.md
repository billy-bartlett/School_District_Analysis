# School District Analysis

## Overview of the School District Analysis

For this project, I was tasked with analyzing data for student funding and student standardized test scores. I was tasked with aggregating the data to showcase trends in school performance that can be leveraged in setting school budgets and priorities. Upon reviewing my initial analysis, it was identified that there was potential evidence of academic dishonesty for the ninth grade reading and math scores for Thomas High School. Upon this discovery, I removed these scores from the data set to allow an additional side-by-side comparison of the two analyses. 

## Results

### District Summary
The District Summary includes the following data: Total Schools, Total Students, Total Budget, Average Math Score, Average Reading Score, % Passing Math, % Passing Reading, and % Overall Passing. The number of Total Schools remained unchanged during both analyses as there are 15 schools included in the original analysis and the revised analysis. Likewise, the Total Budget remained unchaged at $24,649,428.00 along with the Total Student Count at 39,170. 

Categories that were affected are listed below. A description of what changed has also been provided.
	
**Average Math Score** - Average Math Score decreased from 79.0% in the original analysis to 78.9% in the revised analysis.
	
**Average Reading Score** - Average Reading Score decreased from 81.87% in the original analysis to 81.85% in the revised analysis. After formatting, the number appears to be the same due to the very small difference in the original and revised data point.
	
**% Passing Math** - Passing Math Percentage decreased from 75.0% in the original analysis to 74.8% in the revised analysis.
	
**% Passing Reading** - Passing Reading Percentage decreased from 86.0% in the original analysis to 85.7% in the revised analysis.
	
**% Overall Passing** - Overall Passing Percentage decreased from 65.0% in the originl analysis to 64.9% in the revised analysis.

For a visual of these changes, please review the images below. 

![Revised_District_Summary](https://user-images.githubusercontent.com/101153516/180674243-b2e29214-afdb-4ce1-bb03-b53181bcfc71.jpg)

![OG_District_Summary](https://user-images.githubusercontent.com/101153516/180674265-fbd94b4f-f82c-4e9c-b0db-97fa16a63340.jpg)

### School Summary
The School Summary includes the following data: School Type, Total Students, Total School Budget, Per Student Budget, Average Math Score, Average Reading Score, % Passing Math, % Passing Reading, and % Overall Passing. Categories that remain unchaged in both the original and revised analyses include: School Type (District and Charter), Total Students (count of student per school), Total School Budget (budget per school), and Per Student Budget (budget per student).

Below, you can see how the removal of the ninth grade math and reading scores for Thomas High School impacted the School Summary. 

**Average Math Score** - Average Math Score for Thomas High School decreased from 83.41% in the original analysis to 83.35% in the revised analysis.
	
**Average Reading Score** - Average Reading Score for Thomas High School increased from 83.84% in the original analysis to 83.89% in the revised analysis.
	
**% Passing Math** - Passing Math Percentage for Thomas High School decreased from 93.27% in the original analysis to 93.18% in the revised analysis.
	
**% Passing Reading** - Passing Reading Percentage for Thomas High School decreased from 97.31% in the original analysis to 97.02% in the revised analysis.
	
**% Overall Passing** - Overall Passing Percentage for Thomas High School decreased from 90.95% in the originl analysis to 90.63% in the revised analysis.

For a visual of these changes, please review the images below. 

![OG_School_Summary](https://user-images.githubusercontent.com/101153516/180674321-9c49ad50-316c-40e2-9bce-28656663a8c9.jpg)

![Revised_School_Summary](https://user-images.githubusercontent.com/101153516/180674344-c5749db0-794b-4ecb-8ea1-6fe587dc9ff7.jpg)

### Impact of Removing Thomas High School Ninth Grade Scores

As you can see, Thomas High School remained in the top five schools at rank two in both analyses. 

By replacing the ninth grade scores for Thomas High School, the math and reading scores by grade DataFrames now display "nan" rather than a score as indicated in the image below. 

![Revised_Math_Score_By_Grade](https://user-images.githubusercontent.com/101153516/180674371-336ea5d4-3a14-44db-9b60-6591c534b185.jpg)

Scores by school spending were unaffected by this change as budgets were not impacted. However, student performance can be leveraged when answsering budget related questions when establishing future budgets.

Likewise, scores by school size and scores by school type were also unaffected by this change. 

## Summary
By replacing Thomas High School ninth grade scores with "nan," we see a decrease in the follwoing categories: Average Math Score, Average Reading Score, % Passing Math, % Passing Reading, and % Overall Passing.
