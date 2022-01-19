# School District Analysis

## Overview of School District Analysis

The purpose of this analysis is to find out if there's any correlation between the budget per student and the overall passing percentages across a pool of high schools.  Based on the analysis, it was discovered that 9th graders at Thomas High School had incorrect test scores, which led to the request for updated data analysis.  It was determined that the best decision was to update/replace specific 9th grade math and reading scores at Thomas High School, while keeping the integrity of all other data consistent.  Incorrect math and reading scores were replaced with the value "NaN", or "Not-a-number".  

## Results

- How is the district summary affected?
  - Compared against the original dataset and across all 15 schools, the average math score dropped 0.1%, the average reading score remained unchanged, the percentage passing math dropped 0.2%, the percentage passing reading dropped 0.3%, and the overall passing percent dropped 0.1%.

- How is the school summary affected?
  - Once the scores were replaced, the percentage passing math fell from 93.3% to 66.9%.  The percentage passing reading fell from 97.3% to 69.7%.  And for overall passing percentage, Thomas High School fell from 90.9% to 65.1%.

- How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
  - Once the scores were replaced, Thomas High School actually fell out of the top 5 for overall passing percentage, as their total fell from 90.9% all the way down to 65.1%.  Previously they were ranked 2nd in overall passing percentage but not have fallen down to 8th highest.  They, however, did not fall in to the bottom 5 performing schools.

- How does replacing the ninth-grade scores affect the following:
  - Math and reading scores by grade
    - For 9th Graders at Thomas High School, the score nows shows as NaN for both average math and reading scores by grade.  However average grades for grade levels 10-12 remained unchanged as there was no manipulated data in these groupings.
  - Scores by school spending
    - The passing percentages did change for the $630-644 spending range, with a 6% decline in passing math, a 7% decline in passing reading and a 7% decline in overall passing.
  - Scores by school size
    - For the medium-sized schools of 1000-2000 students, the passing percentages did change.  The percentages for passing math, reading and overall passing all declined by 6% each.
  - Scores by school type
    - The percentages for passing math, reading and overall passing did decline for charter schools.  Charter schools passing math fell from 94% to 90%, passing reading fell from 97% to 93% and overall passing fell from 90% to 87%.  That being said, charter schools are still ranked much more competitively compared to district schools.

## Summary
Although 9th grade reading and math scores at Thomas High School were altered, there was only minor impact to the overall school district metrics, with overall passing percentage only dropping by less than 1%.  Thomas High School was individually impacted in their overall passing rankings, where previously they were a top-5 school ranked at #2 for highest passing percentage, instead moved them out of the top 5 and down to #8 overall across the school district.  Tied to this fall, Thomas High School saw a significant impact to their overall passing percentage, which fell by more than 25%!  Because of the data change, there was also negative impact to the budget tiers of $630-644 and medium-sized schools of 1000-2000 students, which saw their overall passing percentages fall 7% and 6%, respectively.
