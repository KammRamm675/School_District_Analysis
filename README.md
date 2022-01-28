# Battle For The NaN

## Overview of the School District Analysis
  - The purpose of this analysis is to provide the reader with information regarding statistical standings of the high schools located within the school district.  This is provided through a look into mathematical and reading test scores.  Also provided is an at-a-glance view of spending on a per-student basis of each high school.  

## Results
  - Below are the test results of reading and mathematical scores.  This will also include an experiment on how’s school scores are affected without including Thomas High School 9th grade scores.  Also, the results of an in-depth view of expenditures of each school.  
  
  ### How is the District Summary Affected?
  - Simply put, not including ALL the data into an analysis can create a false positive or a false negative.  False positive being an overall district performance being good and a false negative being that the district is under performing.  
  - Not including a bad (or good) part of a school’s performance shows that the district is willing to cut corners.  Worst yet it also shows that the district is misrepresenting numbers for the sake of keeping money in the district.
  
  ### How is the School Summary Affected?
 
  - Please reference "School Summary." (https://github.com/KammRamm675/School_District_Analysis/blob/main/School%20Summary.PNG) In this picture we see the fifteen (15) school of the selected school district.  One of the biggest pieces of information that stands out is the relation between "Total School Budget," "Per Student Budget," and both “% Overall Passing" values. We see that the school with the most money budget as an entire school and per student have the lowest passing students.  In all fairness this may be due to there being a larger student test pool.  But at the same time, we can see that the school with a lesser school and per student budget have better passing scores.  There is also a trend that overall passing stays above 90% until the school population reaches 1600 students.  In terms of spending, THS is spending ($630-644/student) as much as a school almost two times in size (Figueroa HS) and doing better.  Including the 9th grade scores will still show spending being the same but the passing rates greatly reduced.  To me still justifying the spending per student. 
  
  - Ultimately this information begs two questions.  First, is there a bad ratio of staff to students? I would venture to say that school over 1600 students need to have more teachers. Secondly, should new school be built? If a school reaches 1600 students, there should maybe talks of building another school to satisfy a 90%F passing rate. 
  
  ### How Does Replacing the Ninth Grade Math/Reading Scores Affect Thomas High School's Performance in Relation to the Other Schools?
  
  - Please reference "Scores with THS 9Th Grade." (PLACE ADDRESS HERE) Replacing the 9th grade scores affected the percentages GREATLY.  Looking at the picture provided we can see that including the 9th grade scores for math would drop the % Passing Math column by about 10.25%! Reading would also drop about 14%! 
  
  ### What is Affected by Replacing Ninth-Grade Scores with NaN?
  
  - Math and Reading Scores by Grade
      Overall, replacing the 9th grade scores would effect school-to-school and grade-to-grade standings greatly.  I would consider this almost a false positive in terms of school quality. THS 9th graders alone actually stand on par in comparison to the other schools 9th grades.
  
  - Scores by School Spending
      THS is spending $630-644 per student.  Which is justifiable.  As I had mentioned earlier, THS is getting a lot of money for where it is in comparison to other schools in the same spending bracket.  Even if adding the 9th grade scores THS is still doing better.  
       
  - Scores by School Size
      THS has 1635 students.  Considering that they are as what I consider to be the cut off, they are doing very well.  Including the 9th grade scores would put them behind in comparison to other schools with the same population. 

  - Scores by School Type
      The type of school is about the same as the school size.  THS is a charter school so comparing THS to similar schools we can see that THS is on the same wavelength as the other charter schools.  BUT if you included the 9th grade scores THS will fall back to last place amongst the other charter schools. 
## Summary
  - The Four Changes After NaN Were Placed
    In summary four changes had occurred.  1. THS' % Passing Math from 66.91% (9th grade included(total number of students passing math/total population)) to 93.86% (9th grade not included).  2. THS' % Passing Reading from 69.66% (9th grade included(total number of students passing math/total population)) to 97.01% (9th grade not included).  3. THS' % Overall Passing is up, but if 9th grade was included it would fall from 97.01% reading and from 93.18% for math. 4. Obviously the overall performance standings of THS went up because the lower end of the scale was not included.  Including the 9th grade would bring down the overall performance rating at THS.
