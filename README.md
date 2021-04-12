# Module 4 - School District Analysis

## Purpose 

There is a grade change for some 9th grade student in Thomas High school which administrators do not have the complete academic record for all students. The administrator wish to standadise the missing value and exclude them from the state academic report calculation. 

## Approach 

1. Replace the missing math and reading scores for 9th grader at Thomas High School with NaN. 

2. Exclude those missing data from the calculation for the state high school academic report. 

## Results 

### District Summary 

#### Before Cleaning up 

- Average Maths Score: 78.98

- Average Reading Score: 81.88

- Passing Math Rate: 74.9%

- Passing Reading Rate: 85.81%

- % Overall Passing Rate: 65.17%

#### After Cleaning up 

- Average Maths Score: 78.9

- Average Reading Score: 81.9

- Passing Math Rate: 74.8%

- Passing Reading Rate: 85.7%

- % Overall Passing Rate: 64.9%

### School Summary & Effect on THS's performance

Excluding the missing 9th grader's math and reading scores only resulted in a slight decrease in overall passing rate, math passing rate and reading passing rate. Overall, Thomas high school still ranks as the second place and still placed within the 90 percentile passing which indicates it does not affect its performance relative to other schools.  

#### Before Cleaning up 

- Thomas High School 

    - Overall Passing Rate: 90.95%

    - Math Passing Rate: 93.27%

    - Reading Passing Rate: 97.31%
    
    - Rank: 2nd

#### After Cleaning up 

- Thomas High School 

    - Overall Passing Rate: 90.63% 

     - Math Passing Rate: 93.19%

    - Reading Passing Rate: 97.02%

    - Rank: 2nd

### Effect on Replacing 9th grade score

Math and reading scores by grades only changed slightly by removing the partial 9th grade scores and Thomas high school still places as 2nd in the district. Score by school spending have increased from $638.00 to $888.53. Total students changed from 1635 to 1174 which its school size still falls in the medium criteria (1000-2000). Score 