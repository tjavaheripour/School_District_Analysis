# School_District_Analysis
python - pandas
## Overview
This analysis project is to prepare standardized test data for analysis in order to gain insights about school performance trends and patterns to help the school board make strategic decisions regarding school budgets and priorities. We have considerations for the FERPA regarding data confidentiality.  
The school board has notified analyst about evidence of academic dishonesty; specifically, reading and math grades for Thomas High School ninth graders appear to have been altered. We are asked to replace the math and reading scores of that school with NaNs while keeping the rest of the data intact.  We also require to measure the impact of these changes on the overall analysis.This report should include:

- The district summary
- The school summary
- The top 5 and bottom 5 performing schools, based on the overall passing rate
- The average math score for each grade level from each school
- The average reading score for each grade level from each school
- The scores by school spending per student, by school size, and by school type

## Results
- How is the district summary affected?

  Upon reviewing both results of district summaries before and after discarding math and reading scores of Thomas High School grade 9th, we observed no meaningful difference.     Average reading score seems to not be affected at all while average math score, rate of passing math and reading and overall passing rate slightly declined. 
  - District Summary after
    - ![District Summary after.png](https://github.com/tjavaheripour/School_District_Analysis/blob/main/Resources/District%20Summary%20after.PNG)

  - District Summary before
    - ![District Summary before.png](https://github.com/tjavaheripour/School_District_Analysis/blob/main/Resources/District%20Summary%20before.PNG)

- How is the school summary affected?

The figures remained unaffected for all schools except Thomas High School which shows a significant drop in passing rates.  Passing math rate and passing reading rate declined considerably reaching 66.91% from 93.27% and 69.66% from 97.30% respectively causing the overall passing rate to drop 26% whereas the average math and reading scores only illustrate a negligible drop

   - School Summary after
    - ![School Summary after.png](https://github.com/tjavaheripour/School_District_Analysis/blob/main/Resources/School%20Summary%20after.PNG)

   - School Summary before
    - ![School Summary before.png](https://github.com/tjavaheripour/School_District_Analysis/blob/main/Resources/School%20Summary%20before.PNG)

- How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?

   Thomas High School remains among the top performing schools (based on the overall passing percentage) if we base our dataset on 10th-12th graders score.
  - School summary 10th-12th
   - ![replacing.png](https://github.com/tjavaheripour/School_District_Analysis/blob/main/Resources/replacing.PNG)

   Top five schools 10th-12th -After
   - ![top five schools -after.png](https://github.com/tjavaheripour/School_District_Analysis/blob/main/Resources/top%20five%20schools%20-after.PNG)
   Top five schools 9th-12th - Before
   - ![Top five school - before.png](https://github.com/tjavaheripour/School_District_Analysis/blob/main/Resources/Top%20five%20school%20-%20before.PNG)

- How does replacing the ninth-grade scores affect the following:
  - Math and reading scores by grade
  
     In the following tables we can see the average math and reading scores of Thomas High School 9th graders have been replaced by nan where they were previously 83.6 and 83.7 respectively.
    - After reading scores by grade
    - ![After reading scores by grade.png](https://github.com/tjavaheripour/School_District_Analysis/blob/main/Resources/After%20reading%20scores%20by%20grade.PNG)

    - Before reading scores by grade
    - ![Before reading scores by grade.png](https://github.com/tjavaheripour/School_District_Analysis/blob/main/Resources/Before%20reading%20scores%20by%20grade.PNG)

    - After Math scores by grade
    - ![After Math scores by grade.png](https://github.com/tjavaheripour/School_District_Analysis/blob/main/Resources/After%20Math%20scores%20by%20grade.PNG)

    - Before Math scores by grade
    - ![Before Math scores by grade.png](https://github.com/tjavaheripour/School_District_Analysis/blob/main/Resources/Before%20Math%20scores%20by%20grade.PNG)

  
  - Scores by school spending

    As shown in the table, spending ranges per student have not been changed before and after changing 9th graders scores to nan as well as average and reading scores and the passing rates.
    - Scores after school spending
    - ![After school spending.png](https://github.com/tjavaheripour/School_District_Analysis/blob/main/Resources/After%20school%20spending.PNG)

    - Scores before school spending
    - ![Scores before school spending.png](https://github.com/tjavaheripour/School_District_Analysis/blob/main/Resources/Scores%20before%20school%20spending.PNG)


  - Scores by school size
    
    Having 1635  student, Thomas High School falls in the medium size category of schools. While nullifying the 9th graders scores did affect the Thomas High School average scores and passing rates but this change did not reflect in the results for the category itself. 
    - Scores after school size
    - ![After school size.png](https://github.com/tjavaheripour/School_District_Analysis/blob/main/Resources/After%20school%20size.PNG)

    - Scores before school size
    - ![Before school size.png](https://github.com/tjavaheripour/School_District_Analysis/blob/main/Resources/Before%20school%20size.PNG)


  - Scores by school type
  
      Thomas High School is a charter school and our analysis shows that this school type’s scores were not affected by the change in the 9th grade class data of Thomas High School.
    - Scores after school type
    - ![Before school type.png](https://github.com/tjavaheripour/School_District_Analysis/blob/main/Resources/After%20school%20type.PNG)

    - Scores before school type
    - ![After school type.png](https://github.com/tjavaheripour/School_District_Analysis/blob/main/Resources/Before%20school%20type.PNG)

## Summary

Dishonesty discovered which resulted in replacing 9th graders data score of Thomas High School(THS) with nan, largely affected the THS performance summary dropping overall passing percentage to 65% from 90%. This change did not have such a large influence in the results for school size category, type, spending and district summary though.
Discarding the 9th graders scores completely and basing our analysis on score data of 10th-12th graders put THS in the same rank among other schools as if we included the incorrect 9th graders score data.
