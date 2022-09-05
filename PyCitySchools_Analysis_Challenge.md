# PyCitySchools School District Analysis Challenge

## Overview of Project

We have been engaged by Maria, The Chief Data Scientist for the PyCity School District.  She is responsible for preparing all standardized test data for analysis, reporting and presentation to the School District Administration to provide feedback about performance trends.  We have been doing some analysis already using Jupiter Notebook and Pandas to create the following:

	•	The School District Summary.
	•	The Summary by School.
	•	The Top 5 and Bottom 5 performing schools.
	•	The average math score for each grade level from each school.
	•	The average reading score for each grade level from each school.
	•	The scores by school spending per student, by school size , and by school type 		(District or Charter).
	•	This analysis was limited to the grades 9 through 12.
	•	Due to a report of grade tampering for 9th graders at Thomas High School the data must 		be cleaned to maintain accuracy.

## Resources
The resources were provided by the Elections employee and included:
•	Data Source: schools_complete.csv and students_complete.csv files.
•	Software: Python 3.7.6, Jupyter Notebook version 6.4.8, Pandas version 1.4.5 and Numby version 

## Overview of The School District Analysis

The results from the PyCity School District Analysis of the 9th through 12th graders is as follows:

District Summary DataFrame


School Summary DataFrame


The Top 5 Performing Schools DataFrame based on the Overall Passing Rate


The Bottom 5 Performing Schools DataFrame based on the Overall Passing Rate


The Average Math Score for Each Grade Level from Each School


The Average Reading Score for Each Grade Level from Each School


The Scores on School Spending per Student


The Scores by School Size


The Scores by School Type

## Results
The impact of nullifying the 9th grade Math and Reading Scores for Thomas High School is as follows:

How the District Summary is Affected

How the School Summary is Affected

How Does replacing the ninth graders math and reading scores affest Thomas High School's performance relative to other schools.

How does replacing the 9th grade scores affect the following:

	 - Math and Reading scores by grade

	 - Scores by school spending

	 - Scores by School Size

	 - Scores by School Type


## Summary
### The Analysis of the PyCity School District for Grades 9 through 12 showed the following:

•	The Thomas High School 9th Graders represent approximately 28% of the students at Thomas High School.  Although we can’t tell what grade modifications were made to the 9th graders grades a rough scan of their grades shows a somewhat normal distribution.  Therefore once these 9th grader grades are nullified (NaN) the impact to the overall results for Thomas High School will be minimal. Since these students represent approximately 1% of the students in the school district the impact to the overall district analysis will be insignificant.
 
•	The four changes to the updated school District analysis after Thomas High School 9th grade reading and math scores were nullified was less than 1% decrease in the following:

	o	Average math scores
	o	% Passing math
	o	% Passing reading 
	o	% Overall Passing
