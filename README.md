# school_districts-analysis
## Overview 
This analysis aggregated the standerdized reading and math test scores for various schools in a school district using Pandas in Jupyter Notebook (version 3.7.11). Multiple calculations were performed on the test scores to evalute school preformance and whether different conditions affected school performance such as grade level, school spending, school size, and school type. These calculations were used to determine budget allotments for the district. 

A separate analysis was also preformed, exactly like the one above except this one excluded the 9th graders' test scores from Thomas High School. 

## Results 
- How is the district summary affected? 
    The district summary was negatively impacted, although not significantly. The percent passing math decreased from 74.9 to 74.8. The percent passing reading decreased from 85.8 to 85.7. The percentage passing overall decreased from 65.1 to 64.9.

- How is the school summary affected?
    The only school impacted in the school summary was Thomas High School. It was negatively impacted, but not significantly. The percent passing math decreased from 93.27 to 93.19. The percent passing reading decreased from 97.31 to 97.02. The percentage passing overall decreased from 90.94 to 90.63.

- How does replacing the 9th graders' math and reading scores affect Thomas High School's performance relative to the other schools? 
    Replacing the 9th graders' scores did not affect Thomas High School's performance relative to other schools. They stayed the second top performing school despite replacing those scores. 

- How does replacing the ninth-grade scores affect the following? 
    - math and reading scores by grade 
        No data was affected in this dataframe except the 9th grade scores for Thomas High School were replaced with NaN.
    - scores by school spending  
        No data was affected.
    - scores by school size 
        No data was affected.
    - scores by school type
        No data was affected.

## Summary
There weren't many significant changes to the school district analysis after replacing the reading and math scores. The district summary was negatively impacted with the percentage passing math, the percentage passing reading, and the percentage passing overall seeing a decrease in value. Thomas High School's analysis also saw a slight change in the school summary. The percentage passing math, the percentage passing reading, and the percentage passing overall all decreased as a result of replacing the 9th graders' test scores. There were no other significant changes to the analysis. 