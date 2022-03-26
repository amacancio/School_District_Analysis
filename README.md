# School_District_Analysis

## Overview of the School District Analysis

The purpose of this analysis was to repeat the previously done school district analysis while replacing the reading and math grades for Thomas High School ninth graders with NaNs in order to measure the effect of the alleged grade tampering taking place.

## Results

#### How was the district summary affected?
<ul>
  <li>Average Math Score: remained the same at 78.9</li>
  <li>Average Reading Score: remained the same at 81.9</li>
  <li>Percent Passing Math: 75% to 74.8%</li>
  <li>Percent Passing Reading: 85.8% to 85.7%</li>
  <li>Percent Overall Passing: 65.2% to 64.9%</li>
</ul>

![Original District Summary](https://user-images.githubusercontent.com/94088129/160019985-35a42c3c-4fb3-4169-b31c-578bc0a76b9c.png)
![District Summary W:O 9th graders](https://user-images.githubusercontent.com/94088129/160019999-fa50f5d0-055e-46d0-b256-e59b8f4f1ec0.png)

#### How is the school summary affected?
<ul>
  <li>Average Math Score: 83.42 to 83.35</li>
  <li>Average Reading Score: 83.85 to 83.90</li>
  <li>Percent Passing Math: 93.3% to 93.2%</li>
  <li>Percent Passing Reading: 97.3% to 97%</li>
  <li>Percent Overall Passing: 90.9% to 90.6%</li>
</ul>

![THS with 9th graders](https://user-images.githubusercontent.com/94088129/160022541-6c9733b9-c84a-417a-9eca-9b21f7e60660.png)
![THS without 9th graders](https://user-images.githubusercontent.com/94088129/160022564-117ad706-dabe-4369-bb54-39063fb426af.png)

#### How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?

Since performance relative to other schools is measured by the Percent Overall Passing and the replacement of the ninth grader's math and reading scores dropped Thomas High School's score by only .3%, Thomas High School remains second overall.

#### How does replacing the ninth-grade scores affect the following: 
<ol>
  <li>Math and reading scores by grade: math scores decreased by .07% and reading scores increased by .05%</li>
  <li>Scores by school spending: no change</li>
  <li>Scores by school size: no change</li>
  <li>Scores by school type: not affected</li>
</ol>

## Summary

After nullifying the scores of the 9th grade students, not much changed in the data.  There were slight changes in the average math and reading scores, as well as the percentages of passing math, passing reading, and overall passing.  Other variables, such as scores by school type, were not affected by the nullification of the ninth graders scores.  Furthermore, Thomas High School managed to maintain it's number two spot in the district, despite the nullification of the ninth grader's scores.
