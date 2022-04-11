# School_District_Analysis
analysis on standardized testing in schools using python/anaconda environment

## Overview
This analysis was originally conducted to provide the district school board with a series of metrics that display the results of standardized testing in the district, based on criteria such as: school type, spending, size, grade level, etc.

The redone analysis takes into account that there may have been some academic dishonesty perpetrated at some point in time; ninth graders' scores for Thomas High School appear to have been altered. The current analysis has replaced all scores for Thomas High School 9th graders with null values, and has been rerun to account for the change. The effects will be explained below.
## Results
When applicable, the categories in which Thomas High School data is present are highlighted in blue.
### District Summary
Below are the changes in the district summary due to the excluded data.
![Original_District_Summary (2)](https://user-images.githubusercontent.com/100614266/162655439-40dbc300-e03c-4c44-a024-616959dd1ea7.png)
![NaN District Summary](https://user-images.githubusercontent.com/100614266/162655446-f1041ca6-a63e-413a-a1b7-aa21ac758f24.png)
The Averages and Passing Percentages are barely changed. If fully rounded to an integer, rather than a decimal point, the values would be identical. The change in data is almost negligible.

### Thomas High School
The following images are the changes for Thomas High School Metrics.
![OG_THS (2)](https://user-images.githubusercontent.com/100614266/162655499-18d01218-9bca-41a1-acfa-4e4a7a7ca34f.png)
![new_THS (2)](https://user-images.githubusercontent.com/100614266/162655509-3cd5389f-059a-4766-80da-6a0c230f5c2d.png)
With the exclusion of their entire 9th grade, Thomas High Schools overall performance is much the same, with some change in the thousandths or hundredths decimal places.

### High School Rankings
These images are of the top five performing schools before and after the excluded data.
![OG_THS_rank (2)](https://user-images.githubusercontent.com/100614266/162655522-22896db8-9050-42b0-8eca-c00cde7a5622.png)
![new_ths_rank (2)](https://user-images.githubusercontent.com/100614266/162655535-2abced22-94b2-4b66-a13a-de64b95cd525.png)
Thomas High School took a small hit in overall passing percentage, however, still managed to keep their place in 2nd best performing school in the district.

### Math Scores by Grade Level
The following images show math score averages for each school by each grade level.
![og_math_scores_by_year (2)](https://user-images.githubusercontent.com/100614266/162655569-9f71dfb4-a4b2-4f09-9202-0381d5b5b8bd.png)
![new_math_avg_by_year (2)](https://user-images.githubusercontent.com/100614266/162655580-6f918c2b-e7dc-4a4a-ab53-9df70d03315c.png)
The only thing that has changed is that the 9th graders for Thomas High School have no values inputted. 

### Reading Scores by Grade Level
The following images show reading score averages for each school by each grade level.
![og_reading_scores_by_year (2)](https://user-images.githubusercontent.com/100614266/162655594-a220f7e9-5227-4bca-9238-75fc09db86e5.png)
![new_reading_avg_per_year (2)](https://user-images.githubusercontent.com/100614266/162655612-aad6fc22-52ba-40cc-9d35-02c78bf12264.png)
Similar to the math scores by grade level, the 9th graders have no values. 

### Scores by School Spending
The following shows the change in scores by spending ranges before and after the excluded data.
![2022-04-10 (46)](https://user-images.githubusercontent.com/100614266/162657011-aebf0b3c-656c-4716-918e-e06d0383bc6b.png)
![new_spending_metric (2)](https://user-images.githubusercontent.com/100614266/162655644-47d81394-7519-4a9e-a6a0-f6f7b8016914.png)
When formatted, the new spending metric shows no significant change and is identical to the original. However, if there were several decimal places, the change would be visible.

### Scores by School Size
The following shows scores based on school size
![og_size_metric (2)](https://user-images.githubusercontent.com/100614266/162655652-13652ea9-6bde-4dbe-9023-b26e0fb57dae.png)
![new_size_metric (2)](https://user-images.githubusercontent.com/100614266/162655657-574311d4-cb51-4cce-86ae-46e4a374e042.png)
The metrics are identical when rounded.

### Scores by School Type
The following shows scores based on whether the school is a Charter or District school
![og_type_metric (2)](https://user-images.githubusercontent.com/100614266/162655674-fc9a8cb3-f96e-4654-8ca4-708adc2258bc.png)
![new_type_metric (2)](https://user-images.githubusercontent.com/100614266/162655694-aaec3907-51a6-456f-bc97-1a9bb9bcdcc6.png)
The metrics, like all the metrics thus far, have experienced negligble change.


## Summary
Essentially, none of the metrics have changed in a significant way. There are miniscule changes when the data is displayed before formatting, however, to any degree that the school board, or other agencies who have permissions, would use this data to make visuals and reports, the changes would not be visible. The only visible changes would be in the grade-level data for math and reading score averages. Since data is null for 9th graders in Thomas High School, no comparisons can be accurately made among data focusing on 9th graders. Thomas High School retains its original ranking among the schools in the district, and the average scores and passing percentages for this school are nearly the same as they were before the 9th graders were removed. 

Although the following is beyond the scope of the purpose of this analysis, I feel like it is necessary to mention that given the extremely small change that the omitted 9th grade THS data created, it is likely that any academic dishonesty among 9th graders at THS is either 1 set of scores, or a small group of students' scores. It is also completely likely that the "alteration" may have simply been a typo that had been corrected, or a series of typos that had been corrected. However, I do not suspect that there was a large scale 9th grade conspiracy. 
