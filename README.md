# School District Analysis
## Overview of Project
### Purpose
For this project, I revised a school district analysis previously completed at the request of the school board.
### Background
There was some concern that grades reading and math grades for Thomas High School ninth graders appear to have been altered were altered. The school board decided to remove the grades. I made adjustments to the school district analysis to account for the dropped grades and will present my results.
### Method
The ninth grade scores for Thomas High School were removed and replaced with null values. The analysis was redone without those grades. While the total student count still reflects those students for budgetary reasons, all percentages have been adjusted to account for the removed students.
## Results
### District Level
In the image below, the revised summary of the entire district is compared with the previous version containing the Thomas ninth graders. The difference is extremely minor, a slight difference in the average math score that is within the rounding margin of error and does not have any effect on the overall passing percentages.

![SchoolDistrictSummary_compared]( https://github.com/DeliaDavila/School_District_Analysis/blob/main/Images/SchoolDistrictSummary_compared.png)


### School Level
In the image below, I have compared the previous and revised percentages for Thomas High School. The numbers are not rounded to show that the average scores did change. However, again, when the numbers are rounded to whole numbers, the overall affect on the average scores and passing percentages disappears.

![ThomasHS_compared.png]( https://github.com/DeliaDavila/School_District_Analysis/blob/main/Images/ThomasHS_compared.png)

### School Ranking
The original and revised ranking of the Top Five schools has been reproduced below. In the comparison, it is easy to see that the very minor changes to the Thomas numbers did not affect the school’s overall ranking as the second highest results in the district.

![ThomasHS_compared.png](https://github.com/DeliaDavila/School_District_Analysis/blob/main/Images/ThomasHS_compared.png)

### Grade analysis
The overall average of math and reading scores were completed by grade. The other grades were unaffected by the removal of 9th grade scores. The average scores for all ninth graders had minor changes, shown below. The reading average is affected in the final number but the unrounded numbers show that the change in the number was due to rounding and not significant.
<<<<<<< HEAD
* Math and reading scores by grade
        * math average (previous): 80 (80.35333333, unrounded)
        * math average (revised): 80 (80.12030214, unrounded)
        * reading average (previous): 83 (82.5133174, unrounded)
        * reading average (revised): 82 (82.42649364, unrounded)

* Math scores by grade
    * Previous average: 80 (80.35333333, unrounded)
    * Revised average: 80 (80.12030214, unrounded)
* Reading scores by grade
    * Previous average: 83 (82.5133174, unrounded)
    * Revised average: 82 (82.42649364, unrounded)

### Other district analysis 
The additional comparisons were run again, comparing the school district in terms of school spending, school size, and school type (public or charter). The percentages below were unaffected by the minor adjustment to the Thomas High School results. 

* School spending (Range Per Student, Overall Passing Percentage)
    * <$584: 90
    * $585-629: 81
    * $630-644: 63
    * $645-675: 54
* School Size (Number of Students, Overall Passing Percentage)
    * Small (<1000): 90
    * Medium (1000-2000): 91
    * Large (2000-5000): 58
* School Type (Type, Overall Passing Percentage)
    * Charter: 90
    * District: 54

## Summary
### Findings
The changes to the Thomas High School averages and percentages were minimal so the overall district summary was not significantly affected. The 9th grade scores were replaced with null values and the numbers were adjusted so that averages reflect the remaining scores. Minor differences in numbers were shown to be not significant and the overall school ranking stayed the same. The overall analysis done at the district level was entirely unaffected, as the percentages stayed the same once the minor differences at Thomas were aggregated into different groups (size, spending level, and school type). 

### Opinion
This analysis cannot prove whether the grades in question were changed. However, it is my opinion that if grades were changed, the motive does not appear to have been to change the school’s overall ranking. I found that Thomas High School was in the top five schools in the district both before and after the questioned scores were removed.

