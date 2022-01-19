# School District Analysis

## Overview of School District Analysis

The purpose of this analysis is to find out if there's any correlation between the budget per student and the overall passing percentages across a pool of high schools.  Based on the analysis, it was discovered that some 9th Graders at Thomas High School had missing test scores.  With there being missing test scores at Thomas High School, we want to ensure all test scores are included in the analysis so that the overall outcomes aren't impacted.

## Results

- How is the district summary affected?
  - The district does not appear to be impacted by the change in data between pycityschools and pycityschools_challenge.

- How is the school summary affected?
  - For Thomas High School, the overall passing percentage is at 90.94%, but by taken out the 9th Grade scores the overall passing shrinks by 0.3%.

- How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
  - The math or reading scores are not impacted.  But upon further investigation it appears that not all 9th Graders' scores are being included, which may potentially lower the school test scores.

- How does replacing the ninth-grade scores affect the following:
  - Math and reading scores by grade
    - For 9th Graders at Thomas High School, the score nows shows as NaN,
  - Scores by school spending
    - Since the 9th Grader scores are now not included, the scores stay nearly identical.
  - Scores by school size
    - The overall passing percentage does not change.
  - Scores by school type
    - The scores by school type barely changes at all.

## Summary

By replacing the scores of 9th Graders at Thomas High School, the result is that not much has changed for overall statistics.  Values were nullified that may have had a potential impact on size, district, spending and overall passing percengate of students.
