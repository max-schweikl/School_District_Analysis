# School District Analysis

## Overview of School District Analysis

The purpose of this analysis is to find out if there's any correlation between the budget per student and the overall passing percentages across a pool of high schools.  Based on the analysis, it was discovered that some 9th Graders at Thomas High School had missing test scores.  With there being missing test scores at Thomas High School, we want to ensure all test scores are included in the analysis so that the overall outcomes aren't impacted.

## Results

- How is the district summary affected?
  - After taking a look at both district summaries from pycityschools and pycityschools_challenge there is not a change.

- How is the school summary affected?
  - The over all passing for Thomas High School was 90.94% in pycityschools, with the 9th graders taken out the overall passing shrinks by 0.3 %.

- How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
  - Overall it does not affect either the reading scores or math scores. We are doing an investigation because we believe they are not including most of the 9th graders scores because they might bring the school even further down in test scores.

- How does replacing the ninth-grade scores affect the following:
  - Math and reading scores by grade
    - The only difference now between the scores is that under 9th graders who attended Thomas High School it shows an NaN.
  - Scores by school spending
    - The numbers stay nearly identical since the 9th graders are nullified from the statistics.
  - Scores by school size
    - Overall passing percentage does not change.
  - Scores by school type
    - Scores by school type are not altered at all.

## Summary
