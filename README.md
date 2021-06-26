# School District Analysis

## Overview
In this challenge we will analyze the student grades from different high schools, we will look into some discrepancies due to incorrect math and reading scores for Thomas High School 9th graders.  

* As part of this analysis, we removed certain data that appeared to be academic dishonesty which created variance from the data pre-removal.  

## Results  
### Thomas High School overall passing rate  
![THS](https://user-images.githubusercontent.com/16723095/123518269-c5e61600-d66a-11eb-9912-fe8cd1597bc8.PNG)  

### Thomas High School overall passing rate after replacing data  
![THS_nan](https://user-images.githubusercontent.com/16723095/123518328-05acfd80-d66b-11eb-95cb-37e39f48a893.PNG)  

* The pictures above shows the average from Math scores move from 83.418349 to 83.350937 and reading scores move from 83.848930 to 83.896082 after we replace the grades for Thomas High School, this removal decreases the district level scores.  
* When the 9th-grade scores were removed from Thomas High School the percent passing rate is slightly lower, without this data been removed Thomas High School students passed math at a rate of 93.272171% and reading at 97.308869%, after this filter the passing rates are 93.185690% for math and 97.018739% for reading. 
* The effect of these score changes is minimal across the data set.
* By grade, Thomas High School has no results for 9th grade, but the rest of its scores are unaffected.
* Spending by the school is unaffected when averaging out across schools. Any effect in by school size is similarly lost in averages and rounding, and similar with overall results by school type.

## Summary
Once the changes were made we lost any data for the 9th grade at Thomas High School, the average scores for the district were not strongly shifted but it decreases district-level scores slightly. 

This analysis shifts entirely future models and expectations for the 9th-grade class since these scores are not accurate. The potential academic dishonesty reduces confidence in the administration and future scoring of Thomas High School. 
