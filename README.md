# School_District_Analysis
## Overview of the School District Analysis
The school board has notified Maria and her supervisor that the School District has found evidence of academic dishonesty; specifically, reading and math grades for Thomas High School ninth graders appear to have been altered. Although the school board does not know the full extent of the academic dishonesty, they want to uphold state-testing standards and have turned to Maria for help. Maria has asked us to replace the math and reading scores for Thomas High School with NaNs while keeping the rest of the data intact. In so doing, we will be able to compare the analyzed test scores to other schools in the district while avoiding any effects of the tainted data.

## Results
By analyzing the results of the analysis, we will be answering the following questions:

### How is the district summary affected
The district summary was affected as THS 9th grade students averaged higher math reading and overall passing % than the district %. By removing the THS 9th grade results we were able to capture accurate results. 

Results prior THS 9th Grade Removal:
![Image](https://github.com/faridah-m/School_District_Analysis/blob/main/Pre_THS.PNG)
Results after THS 9th Grade Removal:
![Image](https://github.com/faridah-m/School_District_Analysis/blob/main/Post_THS.PNG)

### How is the school summary affected?
By removing the 9th graders from THS school, the overall school summary was not significantly affected. Thomas High School still remained in the top 5 schools.This is because of good performance of their other grades. 

![Image](https://github.com/faridah-m/School_District_Analysis/blob/main/Top_5_THS.PNG)

### How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
It affects THS performance slightly as the math passing scores of 83.5% was higher than district passing math score of 78.9%, however THS 10th-12th graders also performed above average in these two categories compared to the district which still left them #2 in the top 5 schools overall passing.

### How does replacing the ninth-grade scores affect the following:
- Math and reading scores by grade: All scores become Null / NaN
- Scores by school spending: THS remained in the same school spending bin
- Scores by school size: % Passing math went from 73% to 73.46%, % Passing Reading went from 84% to 84.3%. Other bin were unaffected as the seperation by school spending resulted in only the passing % of the specfic bin being affected
- Scores by school type: No significant change was observed when THS 9th grade schores were removed

## Summary
Below are the four major changes to the school district analysis after reading and math scores have been replaced:
- Bins that THS belonged to changed
- Average scores for THS in Math and Reading
- THS Student Count
- Medium school size passing & for Math and Reading
