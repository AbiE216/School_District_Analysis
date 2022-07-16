# School_District_Analysis
Overview of the school district analysis: Explain the purpose of this analysis.

## Overview
### Purpose 
PyCity School District enlisted us with a list of tasks to provide a complete anyalysis of the different schools reading and math scores. Thomas High School Ninth Graders were omitted from the data based on possible academic dishonesty; as such the anaylsis needs to be performed again to ensure accurate results. 
#### Tasks to complete
 1. Replace all reading and math scores for Thomas High School 9th graders with Nan within the data set.
 2. Repeat the School District Analysis with the following metrics:
   1. The District Summary.
   2. The School Summary.
   3. The Top 5 and Bottom 5 performing schools: based on overall passing rate.
   4. The average math score for each grade level from each school.
   5. The average reading schore for each grade level from each school.
   6. The scorea by school spending per student, by school size, and by school type.
### Resources
- Data source: schools_complete.csv and students_complete.csv
- Software: Python 3.6.1
    - Jupyter notebook
    - Pandas
## School District Results
###  The affect on District Summary and School Summary
The school district summary remained largely the same with the exception of the score averages from Thomas High School rising dramatically by about 30% a piece. 
 - Math initial average: 66.91 increased to 93.19
 - Reading initial average: 69.66 increased to 97.02
 - Overall initial average: 65.08 increased to 90.63
### The Impact on the Top 5 and Bottom 5 Schools
 - The top 5 schools: 
   1. Cabrera High School
   2. Thomas High School
   3. Griffin High School
   4. Wilson High School
   5. Pena High School
 - The bottom 5 schools: 
   1. Rodriguez High School
   2. Figueroa High School
   3. Huang High School
   4. Hernandez High School
   5. Johnson High School
 Thomas High School went from have the lowest math and reading percentages to being the second best performing school. 
### Other Impacts
#### The Impact on Math and Reading
The average reading and math score both drastically increased, as seen in the initial impact section. By removing the 9th grade scores, each average rose about 30%. 
#### Scores and School Spending
The change in scores, showed on clear trend the better a school performed the less funding it recieved, the was initially skewed by Thomas High but now there is a clear data trend. 
#### Scores by School Size
Small and Medium schools performed far better than large schools, which again, removing the scores from Thomas High, allowed the data to follow the progression of data rather than becoming an anomally.
##### Scores between District and Charter
When sorter by type, District and Charter, overall it appears that all charters performed about two times better than district schools. Because Thomas High is a charter, one would expect that if follow that trend, initially it did not, however, with corrected data it does. 

## Summary 
There were clear data trends for the majority of schools, be it size, funding, or type of school. Prior to the results being removed from Thomas High School's 9th graders, the data had an outlier, however, with the correction made, all data falls into a neat line. Large District schools perform worse and recieve more funding than small charter schools perform better and recieve less funding. 
Food for thought: if school funding is based on outcomes, perhaps there should be a secondary incentive to performing well. It makes sense that a poorly performing school with more students would need more funding, but perhaps schools that do well in testing should be given a separate reward to encourage teachers to be honest in there grading. 

  
   
