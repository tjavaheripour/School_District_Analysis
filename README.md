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
  - District Summary after
    - ![District Summary after.png](https://github.com/tjavaheripour/School_District_Analysis/blob/main/Resources/District%20Summary%20after.PNG)

  - District Summary before
    - ![District Summary before.png](https://github.com/tjavaheripour/School_District_Analysis/blob/main/Resources/District%20Summary%20before.PNG)

- How is the school summary affected?
  - School Summary after
    - ![School Summary after.png](https://github.com/tjavaheripour/School_District_Analysis/blob/main/Resources/School%20Summary%20after.PNG)

  - School Summary before
    - ![School Summary before.png](https://github.com/tjavaheripour/School_District_Analysis/blob/main/Resources/School%20Summary%20before.PNG)

- How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
   - ![replacing.png](https://github.com/tjavaheripour/School_District_Analysis/blob/main/Resources/replacing.PNG)

- How does replacing the ninth-grade scores affect the following:
  - Math and reading scores by grade
    - After reading scores by grade
    - ![After reading scores by grade.png](https://github.com/tjavaheripour/School_District_Analysis/blob/main/Resources/After%20reading%20scores%20by%20grade.PNG)

    - Before reading scores by grade
    - ![Before reading scores by grade.png](https://github.com/tjavaheripour/School_District_Analysis/blob/main/Resources/Before%20reading%20scores%20by%20grade.PNG)

    - After Math scores by grade
    - ![After Math scores by grade.png](https://github.com/tjavaheripour/School_District_Analysis/blob/main/Resources/After%20Math%20scores%20by%20grade.PNG)

    - Before Math scores by grade
    - ![Before Math scores by grade.png](https://github.com/tjavaheripour/School_District_Analysis/blob/main/Resources/Before%20Math%20scores%20by%20grade.PNG)

  
  - Scores by school spending

    We can see the results of tables according to spending ranges have not changed before and after changing the 9th graders to NaN.
    - Scores after school spending
    - ![After school spending.png](https://github.com/tjavaheripour/School_District_Analysis/blob/main/Resources/After%20school%20spending.PNG)

    - Scores before school spending
    - ![Scores before school spending.png](https://github.com/tjavaheripour/School_District_Analysis/blob/main/Resources/Scores%20before%20school%20spending.PNG)


  - Scores by school size
    
    Thomas High School has 1635 students which refer to the Medium Category. The average math and reading score, the passing percentage and the % Overall students passing of each category remained unaltered.
    - Scores after school size
    - ![After school size.png](https://github.com/tjavaheripour/School_District_Analysis/blob/main/Resources/After%20school%20size.PNG)

    - Scores before school size
    - ![Before school size.png](https://github.com/tjavaheripour/School_District_Analysis/blob/main/Resources/Before%20school%20size.PNG)


  - Scores by school type
  
      Thomas High School is a charter school, so as we see the scores based on school type was not affected by the change in the 9th grade class data
    - Scores after school size
    - ![Before school type.png](https://github.com/tjavaheripour/School_District_Analysis/blob/main/Resources/After%20school%20type.PNG)

    - Scores before school size
    - ![After school type.png](https://github.com/tjavaheripour/School_District_Analysis/blob/main/Resources/Before%20school%20type.PNG)

## Summary
