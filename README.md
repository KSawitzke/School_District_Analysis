# School_District_Analysis

## Overview

Maria was asked by the school board to put together an analysis of the school district to help make future funding decisions. This included an analysis of any trends by grade level, budget spent, school size, and school type across all of the schools in the district. Maria enlisted our help to perform this initial analysis for the district, but then a suspected case of academic dishonesty came up in one of the school's 9th grade classes. Because of this, we had to revisit our analysis and account for the student's whose scores were invalidated.

## Results

### District Summary

Overall, the district summary did not see much of an impact with the removal of the 9th grade class from Thomas High School's student's grades from the analysis. 

#### District Summary - Original Results
[Image](Resources/District_Summary1.PNG)

#### District Summary - Updated Results
[Image](Resources/District_Summary2.PNG)

Initially, the original results were rounded to a whole number, but I've brought it out to one decimal place for comparison's sake. We then see the following differences at the district level when the Thomas High School ninth grade scores are removed:
  - Average Math Score down .1 %
  - Average Reading Score no change
  - % Passing Math down .2 %
  - % Passing Reading down .1 %
  - % Overall Passing down.3 %

These aren't huge differences when looking at the whole district, but there is a negative trend when the THS 9th grade is removed.

### School Summary

In the first look at the by school level summary, the scores for THS are very low. This is because at this point in the code, the scores had been invalidated and replaced with NaN, but had not yet been removed from the calculations. This means they were essentially counted as zeroes, because they added no score to the summation, but added a student count to the total, bringing the average down.



