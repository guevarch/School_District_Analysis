# PandaPython

##Overview of the school district analysis: Explain the purpose of this analysis.

-The overview of the school district analysis is to examine the data for academic dishonesty by removing one of the shools 9th grade reading and math results. The first method is to replace the 9th grade reading and math would NaN's and perform the following analysis on district school summary, school summary, top 5 and bottom 5 performing schools, based on the overall passing rate, average math score for each grade level from each school, average reading score for each grade level from each school, scores by school spending per student, by school size, and by school type.

Results: Using bulleted lists and images of DataFrames as support, address the following questions.
How is the district summary affected?
![image](https://user-images.githubusercontent.com/107594143/179422297-574a7d76-ec7c-45cb-b6a3-63e725704702.png)
 - This is the school summary report before removing the THS 9th grades.
![image](https://user-images.githubusercontent.com/107594143/179422436-eb987a91-34c4-4a5f-a468-4b60a383b6e8.png)
 - This is the school summary report after removing the THS 9th grades. We can see a 39% increase in passing math, reading and overall percentage. 
![image](https://user-images.githubusercontent.com/107594143/179422759-05cbaee0-2ae4-4441-ab99-83712592b6a9.png)
 - This image shows the top performing schools, on the left we can see THS grades with 9th grades; on the right we can see without the 9th grade scores. The removal alone elevated the scores by 39%.
![image](https://user-images.githubusercontent.com/107594143/179430126-24de912b-bfcf-4251-bf19-7c375c2961d1.png)
 - Comparing the top performing schools, the image on the left represents THS with the 9th graders, the right without. THS overall passing percentage is top 2 without the 9th grader scores; while if left in the analysis the ranking would be much lower.
![image](https://user-images.githubusercontent.com/107594143/179430211-2bfc8e12-8825-4944-b2c5-eb968b1afeb4.png)
 -This images at the math and reading grades. The image on the left includes the 9th graders and the right excludes them. The data shows that the math and reading grades from grade 9 were dragging the overall passing percentage of the school down. Another conclusion that could be drawn, ableit a weak case, but if students from grade 10-12 were all cheating on the exams. I doubt the later conclusion is more believable than the former.
 ![image](https://user-images.githubusercontent.com/107594143/179430702-85eb1376-5c81-4f35-b0d3-1e44a658401c.png)
 - This image shows the amount of grade 9 students in the THS school. Grade 9 make about roughly 28% of the population. Quite interesting that of the population would skew the data lower



How is the school summary affected?
How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
How does replacing the ninth-grade scores affect the following:
Math and reading scores by grade
Scores by school spending
Scores by school size
Scores by school type
Summary: Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.
