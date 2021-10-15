# School District Analysis

## Overview of the school district analysis

The objective of the analysis is to assist Maria with the information of a school district to get a high-level snapshot of the district's key metrics and a overview of the key metrics for each school. However, The school board has notified Maria and her supervisor that the students_complete.csv file shows evidence of academic dishonesty; specifically, reading and math grades for Thomas High School ninth graders. We have been asked to replace the math and reading scores for Thomas High School with NaNs while keeping the rest of the data intact in order to run the school district analysis again.

For this task, we merge two datasets schools complete.csv and students_complete.csv. The schools_complete.csv consists of 15 rows of information, including the name of the schools, type, size, and budget. On the other hand, the students_complete.csv contains the information of each student, their name, their gender, their grade, the school, the reading score and the math score.

## Results

After replacing the math and reading scores for Thomas High School with NaN we have the following differences

- **How is the district summary affected?**

Before replace

![](https://github.com/Jponce25/School_District_Analysis/blob/f5a9a1f7b70957c22de7e121d0a1fd5025c6663e/Resources/DSBe.png)

After replace

![](https://github.com/Jponce25/School_District_Analysis/blob/f5a9a1f7b70957c22de7e121d0a1fd5025c6663e/Resources/DSAf.png)

In the district summary we can observe a small decrease in the % Overall Passing, with an even smaller decrease in the Average Math Score, in the % Passing Mathen and in the % Passing Reading, However, However, the Average Reading Score remained the same.

- **How is the school summary affected?**

Imagen 

In the school summary we can observe a decrease of three tenths in the % Overall Passing. A small decrease is also observed in the Average Math Score, in the % Passing Math and in the % Passing Reading. However, the Average Reading Score does not decrease in fact increases 0.05

- **How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?**

Imagen

Sorting the base by the top 5 schools, we can observe that "Thomas High School" remains in the second position. The % Overall Passing only decreased 0.3 and remains above "Griffin High School".

- **How does replacing the ninth-grade scores affect the following:**

1) Math and reading scores by grade

Imagen

After substituting the 9th grade scores for NaN, it can be confirmed that only the 9th grade math and reading scores were affected.

2) Scores by school spending

Imagen

After substituting the ninth grade values ​​at Thomas High School, it can be seen that the spending range per student remains the same ($630-644). Only we can see a small decrease (0.1) in the % Passing Reading.

3) Scores by school size

Imagen

Thomas High School remains a medium-sized school, grouping by size there is only a decrease of 0.1 in the % Passing Reading the other values ​​remain the same.

4) Scores by school type

Imagen

Finally, the grouping by type of school shows us that there is no difference in the data.


## Summary

After replacing the ninth grade values ​​with NaN, no major changes are identified. But we can try to summarize the most relevant changes:

- The district summary reveals that replacing the 9th grade data affects the Average Math Score compared to the Average Reading Score. In other words, the original 9th grade data in Math was slightly enough to push the Average Math Score higher.
- The % Overral Passing decreases .3 tenths after replacing the data, this indicates that the % Overral Passing of Thomas High School is above the average. This can be confirmed with the value of the % Overral Passing for the Thomas High School that goes from 90.94 to 90.63.
- Sorting the data by type, size or spending range, do not change the result in the % Overall Passing, this means that comparing Thomas High School with other schools within the same range does not change the final values.
- Finally, we can deduce that there is a greater impact of the ninth grade scores on maths rather than reading. but that impact is only reflected in the totalized data because Thomas High School is ranked second in the top schools, if we categorize the data into ranges and compare Thomas High School with schools with similar characteristics, we observe that there are no changes on the overall passing percentage.
