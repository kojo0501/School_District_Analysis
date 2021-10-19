# School District Analysis

## Purpose

### Analyzing School District Data
Maria was seeking to analyze performance trends and patterns using standardized test score data. The data is used to evaluate school performance and inform decisions about school funding. The data for individual students needed to be aggregated in a way that masks the identity of individual students. Analysis of the data was completed using Python in Jupyter Notebook.

### Removal of Thomas High School from Data Set
A signficant change from the original data set is that test scores for ninth graders at Thomas High School were removed the analysis. The data was removed at the request of the schoolboard due to evidence of academic dishonesty. The focus of this report is to compare analysis of the full data set to an analysis of a version that does not include Thomas High School's ninth grade reading and math scores.

This code displays where the grade percentages for Thomas High School with data that excluded their ninth grade test scores:
![code_change_to_summary](https://user-images.githubusercontent.com/24308495/137845389-a7f9855e-43ed-488d-9ec5-c8e69311a710.PNG)


## Results

### •	Top Five Performing Schools
These were the top five performing schools in the full set:
![MODULE_top_5_performing](https://user-images.githubusercontent.com/24308495/137844447-3ef57a91-23e0-47c1-be79-db6246ea3f28.PNG)

These were the top five performing after Thomas High School ninth grade was removed:
![CHALLENGE_top_5_performing](https://user-images.githubusercontent.com/24308495/137844682-f1686e6b-f926-4a9f-a07d-d69ef0612e34.PNG)

### •	Bottom Five Performing Schools
The outcomes for the bottom five performing schools were identical in both the full set and the altered set.
![CHALLENGE_bottom_5_performing](https://user-images.githubusercontent.com/24308495/137844865-d8848005-e329-48d2-8bcf-ef712b4f64da.PNG)

### •	Math Scores by Grade Level
These were math scores by grade in the full set:
![MODULE_math_by_grade](https://user-images.githubusercontent.com/24308495/137846184-2f1136b9-7bc2-428b-bbd4-dde68b5f3aab.PNG)

These were math scores by grade after Thomas High School ninth grade was removed:
![CHALLENGE_math_by_grade](https://user-images.githubusercontent.com/24308495/137846250-b6fe45d4-c99b-4172-b0c5-ce669833b487.PNG)

### •	Reading Scores by Grade Level
These were reading scores by grade in the full set:
![MODULE_reading_by_grade](https://user-images.githubusercontent.com/24308495/137846227-d2d09733-354a-435c-b3d2-598fef78f2ce.PNG)

These were reading scores by grade after Thomas High School ninth grade was removed:
![CHALLENGE_reading_by_grade](https://user-images.githubusercontent.com/24308495/137846273-3c8184bc-9ac6-40b3-b155-08ee27280a75.PNG)

### •	Scores by School Spending per Student
After scores were formatted, there was functionally no change in the data.
![PER_student_spending](https://user-images.githubusercontent.com/24308495/137847096-eee847d7-dad7-4245-872c-2f895aaa29c7.PNG)

### •	Scores by School Size
After scores were formatted, there was functionally no change in the data.
![PER_school_size](https://user-images.githubusercontent.com/24308495/137847064-736e6790-9919-4b2a-b781-1b796566343c.PNG)

### •	Scores by School Type
After scores were formatted, there was functionally no change in the data.
![PER_type](https://user-images.githubusercontent.com/24308495/137847055-958e1e3b-2df9-4ebe-a998-12d5bf4192ed.PNG)

## Summary

### Changes After Removing Thomas High School Ninth Grade Scores
Removing Thomas High School ninth grade class caused these changes in the data:
&emsp;1. Reviewing the top 5 performing schools, Thomas High School had minor changes in the average scores and percentage passing. No change to percentage passing was greater than 0.35%, and the average was greater than 0.07. Dropping the ninth grade improved outcomes for "% Overall Passing" and "% Passing Reading" but it was detrimental for all other outcomes.
&emsp;2. For the data set that removed Thomas High School ninth grade scores, no value was provided on the chart that shows math scores by grade. On the chart using the full data set, there is a numerical value; on the chart with the updated data set, NaN was inserted.
&emsp;3. For the data set that removed Thomas High School ninth grade scores, no value was provided on the chart that shows reading scores by grade. On the chart using the full data set, there is a numerical value; on the chart with the updated data set, NaN was inserted.
&emsp;4. For the remainder of the metrics, there were changes that were masked by formatting. Due to rounding, the changes aren't apparent in the final version of the chart. However, if the chart was formatted to include more decimal places, a very slight marginal change would become apparent.
