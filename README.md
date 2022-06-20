# School_District_Analysis

## Overview of the school district analysis
Due to academic dishonesty, Thomas High School ninth graders' math and reading scores were replaced by NaNs. School district files were reanalyzed to
compare the results, aiming to determine how these changes affected the overall analysis. The following analyses were covered:
1. Create data frames of district summary.
2. Create data frames of school summary.
3. Determine the top 5 and bottom 5 performing schools, based on the overall passing rate.
4. List the average math scores for each grade level from each school.
5. List the average reading scores for each grade level from each school.
6. Calculate the scores by school spending per student, by school size, and by school type

## Resources and Tools
- Data Source: [schools_complete.csv](https://github.com/CelineWW/School_District_Analysis/blob/main/Resources/schools_complete.csv),
               [students_complete.csv](https://github.com/CelineWW/School_District_Analysis/blob/main/Resources/students_complete.csv).
- Software Python 3.7.13, jupyter notebook

## Results
- **The district summary**
    - Original>>>>![The district summary original](https://user-images.githubusercontent.com/105877888/174541102-c0b81b64-e123-44ba-a4fc-22fac0652ee1.PNG) 
    - Replaced>>>>![The district summary replaced](https://user-images.githubusercontent.com/105877888/174541480-23ea6b66-55ec-4535-b412-cbf25cff5c49.PNG)
 
- **The school summary**
    - Original>>>>![The school summary title](https://user-images.githubusercontent.com/105877888/174542840-365578c8-5628-4500-91c1-481cf21bffe8.PNG)![The school summary original](https://user-images.githubusercontent.com/105877888/174542884-e51cf545-b6d7-45b0-be8f-c4af67b5f2cb.PNG)
    - Replaced>>>>![The school summary replaced](https://user-images.githubusercontent.com/105877888/174542895-29bc0eff-f143-4937-9d1c-e1a981823d16.PNG)
   
- **Thomas High School's performance based on overall passing percentage.**
  - Top 5 schools
     - Original>>>>![School performance top original](https://user-images.githubusercontent.com/105877888/174544691-78724b7e-0af9-40e2-8b9e-cf5cbbdff8b6.PNG)
     - Replaced>>>>![School performance top replaced](https://user-images.githubusercontent.com/105877888/174544708-87ef6833-c40a-4394-b400-31ef50ccba0f.PNG)
  - Bottom 5 schools remain the same.

- **Other changes affected:**
  - Math and reading scores by grade
    - Original>>>> Thomas High School 9th Graders' Average Scores:  Math-83.6, Reading-83.7. 
    - Replaced>>>> Thomas High School 9th Graders' Average Scores:  Math-NaN, Reading-NaN.
  
  - Scores by school spending
    - Original>>>>![Scores by school spending original](https://user-images.githubusercontent.com/105877888/174548783-586b8e60-ca81-424c-b62e-1f250e463112.PNG)
    - Replaced>>>>![Scores by school spending replaced](https://user-images.githubusercontent.com/105877888/174548800-9842492e-78c9-4fd0-afca-80702cd1077b.PNG)

  
  - Scores by school size
    - Original>>>>![Scores by school size original](https://user-images.githubusercontent.com/105877888/174548849-9ca2f005-123f-4d0f-9055-986f82b7732b.PNG) 
    - Replaced>>>>![Scores by school size replaced](https://user-images.githubusercontent.com/105877888/174548876-7c92a59b-0299-4b91-9eca-088940039a70.PNG)
    
  - Scores by school type
    - Original>>>>![Scores by school type original](https://user-images.githubusercontent.com/105877888/174548911-329dc441-6850-4ee9-9566-bc04df279de1.PNG) 
    - Replaced>>>>![Scores by school type replaced](https://user-images.githubusercontent.com/105877888/174548925-ceefbe30-ae6f-41c9-9c4d-1c4a33b985e5.PNG)

## Summary
After reading and math scores for the ninth grade from Thomas High School were replaced with NaNs, school district analyses results were updated. According to analyses, there were a few changes occured: 
  - The district summary: Updated average math score, passing math percentage, passing reading percentage, and overall passsing(both on math and reading) percentage are slightly lower than original ones.
  - The school summary: For Thomas High School, although average math score and reading score appear no big differences, passing math percentage, passing reading percentage, and overall passing percentage dramatically dropped. School summary for other schools were not affected.
  - School performance: Even if overall passing percentage of Thomas High School is changed from 90.948012% to 90.630324%, this doesn't affect its performance relative to other schools. Either ninth graders' math and reading scroes replaced or not, Thomas High School hold the second place of school performance based on overall passing percentage. 
  - Math and reading scores by grade: Obviously, Thomas High School 9th Graders' Average Scores were: Math-83.6, Reading-83.7. These average scores changed to NaNs. Because all the individual ninth grade student math and reading scores were replaced by NaN. 
  - For scores by school spending, school size, and school type, no changes were observed from formatted analyses data. 
  
 *Notice: Since all dataframe were formatted to certain decimals places. The changes of analyses results are based on current formatted data. If trace back to original data or formatted to more decimal places, there might be delicate changes been noticed.*
