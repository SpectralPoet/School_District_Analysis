# School_District_Analysis
Use Python and the Pandas library to analyze school district data and showcase trends in school performance.

For this part of the Challenge, write a report that summarizes your updated analysis and compares it with the results from the module.

The analysis should contain the following:

  Overview of the school district analysis: Explain the purpose of this analysis.
    Essentially it's just a reporting of district data. No concrete purpose was given. Some manipulation of data has been done to compare overall passing percentage      based on variables such as per student spending, school size, and school type.

  Results: Using bulleted lists and images of DataFrames as support, address the following questions.
      How is the district summary affected?
  The passing percentages are marginally lower. There's very little difference on a district level
  
  How is the school summary affected?
Only Thomas Highschool is affected, naturally. Thomas Highschool, however, has a significantly different outcome.
Image 1: Pre-Changes![Thomas Highschool Before](https://user-images.githubusercontent.com/21095468/124978327-3e4bc000-dff7-11eb-8274-04fb4b1820e3.png)
Image 2: Post-Changes![Thomas Highschool After](https://user-images.githubusercontent.com/21095468/124978359-499eeb80-dff7-11eb-95db-5d35b5252fb9.png)


  How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
Its overall passing percentage goes from 2nd of 15 to 15th of 15

  How does replacing the ninth-grade scores affect the following:
      Math and reading scores by grade
      All changed to NaN for Thomas High School 9th grade. Others unaffected.
      
   Scores by school spending
   These are essentially unaffected due to the large sample size   
   
   Scores by school size
   These are essentially unaffected due to the large sample size
   
   Scores by school type
    These are essentially unaffected due to the large sample size

  Summary: Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.
  1. All 9th grade math and reading scores at Thomas High school are NaN
  2. Thomas High School overall passing percentage changed from ~90% to ~65%
  3. Thomas High School ranking by passing percentage changed from 2nd to 15th of 15
  4. Number of total students being evaluated at Thomas High School reduced by 461
