# School_District_Analysis

## School_District_Analysis_Challenge

Module 4 Challenge

Following the PyCitySchools.ipynb analysis done as part of Module 4, it was discovered that some score averages were incorrect. Therefore, in this challenge analysis, the ninth-grade math and reading scores from Thomas High School were replaced with the correct scores.

The goals of this challenge analysis were to:
    - Filter DataFrames using logical operators
    - Replace incorrect values with NaN
    - Explain how the PyCitySchools analysis changes after handling the incorrect data 

Additionally, student's names were corrected to remove professional prefixes or suffixes.

The new analysis is contained in the PyCitySchools_Challenge.ipynb and for easy of understanding, a new analysis was started from scratch for this challenge.

After replacing the reading and math scores for 9th graders at Thomas High School, the district and school summary DataFrames were recreated with the following results:

- The district summary average scores and percentage passing were affected, specifically:
    - Average math score decreased by 0.1% to 78.9%
    - Average reading score stayed the same at 81.9%
    - Percentage passing math decreased 1.1% to 73.0%
    - Percentage passing reading decreased by 1.3% to 84.7%
    - Percentage overall passing decreased 0.1% to 64.9%

- The school summary average scores and percentage passing for Thomas High School were affected, specifically:
    - Average math score was unchanged at 83.4%
    - Average reading score increased by 0.1% to 83.9%
    - Percentage passing math decreased by 26.4% to 66.9%
    - Percentage passing reading decreased by 27.6% to 69.7%
    - Percentage overall passing decreased 25.8% to 65.1%

After recalculate the high-performing and low-performing schools, replacing the ninth graders’ math and reading scores for Thomas High School resulted in Thomas High School moving from 2nd place with an overall passing percentage of 90.9% to 8th place with an overall passing percentage of 65.1%.

Recalculate the scores by grade, scores by school spending, scores by school size, and scores by school type.
Replacing the ninth-grade scores affected the following:
    - Math and Reading Scores by Grade - only affect Thomas High School 9th grade, reading scores went from 83.7% to NaN, and math scores went from 83.6 to NaN
    
    - Scores by School Spending - only affected the $630 to $644 per student range. Average math and reading scores were unchanged, however:
        - Percentage passing math decreased 6.6% to 66.9%
        - Percentage passing reading decreased by 6.9% to 77.5%
        - Percentage overall passing decreased 6.5% to 56.4%

    - Scores by School Size - only affected the medium size schools. Average math and reading scores were unchanged, however:
        - Percentage passing math decreased 5.3% to 88.3%
        - Percentage passing reading decreased by 5.5% to 91.3%
        - Percentage overall passing decreased 5.2% to 85.4%

    - Scores by School Type - only affected Charter schools:
        - Percentage passing math decreased 3.3% to 90.3%
        - Percentage passing reading decreased by 3.5% to 93.1%
        - Percentage overall passing decreased 3.2% to 87.2%


