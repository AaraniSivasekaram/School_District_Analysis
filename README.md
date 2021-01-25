# School_District_Analysis

## Overview of project
This challenge allowed me to review school district student data and determine indicators such as: spending per student, average math and reading scores, and analysis based on spending, school size and district. As well, I was able to remove non-verified data from Thomas High School for grade 9 math and reading score and re-run my original school analysis to determine any changes.

## Results
- The district summary was slightly different after updating Thomas High School grade 9 values. Compared to the original district summary (https://github.com/AaraniSivasekaram/School_District_Analysis/blob/main/District_summary.png), values such as: avg math score, avg reading score, % passing math and % passing reading decreased by approximately 0.1%. And % overall passing decreased by approximately 0.3% (https://github.com/AaraniSivasekaram/School_District_Analysis/blob/main/Updated_district_summary.png). 
- Within the school summary, all schools except for Thomas High School were unchanged. Thomas High School had its reading and math score affected by the ninth-grade changes, values such as: avg math score, avg reading score, % passing math, % passing reading amnd % overall passing decreased slightly (by 0.05% to 0.3%). 
- Replacing the ninth graders' math and reading scores did not affect Thomas High School's ranking overall compared to other schools, Thomas High School remains second overall in % overall passing.
- Replacing the ninth-grade scores:
  - Changed math and reading scores by grade for Thomas High School, where NaN replaced all 9th grade math and reading scores. The other schools were not affected by this change.
  - Did not affect scores by school spending.
  - Did not affect scores by school size. 
  - Did not affect scores by school type.

## Analysis
Four major changes in the updated district analysis after the reading and math scores for ninth-grade Thomas High School students were replaced with NaNs. 
1. The grade values in the updated district analysis were slightly decreased. 
2. Thomas High School no longer has a value for ninth grade reading scores.
3. Thomas High School no longer has a value for ninth grade math scores. 
4. Overall passing percentage decreased the most by 0.3%.
All these factors relate to the fact that the voided ninth-grade scores were likely passing grades that were high percentages, affecting math, reading and overall scores not only for Thomas High School but for the district as a whole.
