# School_District_Analysis

## Overview
Maria, a chief data scientist for a city school district, requires assistance in analyzing data on student funding and student standardized test scores. Our task is to organize the data and illustrate trends in school performance.

## Results
Using the student funding, and math and reading scores, we were able to output the following results:

-	Top 5 Performing Schools

  ![Top_Performing](/top_perf.PNG)
  
-	Bottom 5 Performing Schools

  ![Bottom_Performing](/bttm_perf.PNG)
  
-	Math Scores by Grade

![Math_Scores_Grade](/math_scores_grade.PNG)

-	Reading Scores by Grade

![Reading_Scores_Grade](/reading_scores_grade.PNG)

-	Scores by School Spending

![Spending_Summary](/spending_summary.PNG)

-	Scores by School Size

![School_Size_Summary](/score_school_size.PNG)

-	Scores by School Type

![School_Type_Summary](/score_school_type.PNG)

During our analysis, it was brought to our attention that the ninth grade reading and math scores were not accurate for Thomas High School. Therefore, we replaced all the ninth grade scores for this school with NaN values. By doing this, the results we produced were slightly reduced due to Thomas High School only reflecting results for grades 10 to 12.

## Summary
While the school standings remain the same, the data we output fails to reflect the full picture as we needed to clean the data received from Thomas High School. As a result, reading, math and overall scores are slightly inacurate. We also do not have the the full picture if we choose to analyze performance trends for 9th graders.
