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

### District Summary DataFrame

![__](https://github.com/Johnnytoobadman/School_District_Analysis/blob/main/PNG%20Files/PyCity%20District%20Summary.png)

### School Summary DataFrame

![__](https://github.com/Johnnytoobadman/School_District_Analysis/blob/main/PNG%20Files/School%20Summary%20DataFrame.png)

### The Top 5 Performing Schools DataFrame based on the Overall Passing Rate

![__](https://github.com/Johnnytoobadman/School_District_Analysis/blob/main/PNG%20Files/Top%205%20Perfoming%20Schools.png)

### The Bottom 5 Performing Schools DataFrame based on the Overall Passing Rate

![__](https://github.com/Johnnytoobadman/School_District_Analysis/blob/main/PNG%20Files/Bottom%205%20Perfoming%20Schools.png)

### The Average Math Score for Each Grade Level from Each School

![__](https://github.com/Johnnytoobadman/School_District_Analysis/blob/main/PNG%20Files/Average%20Math%20Score%20by%20Grade.png)

### The Average Reading Score for Each Grade Level from Each School

![__](https://github.com/Johnnytoobadman/School_District_Analysis/blob/main/PNG%20Files/Average%20Reading%20Score%20by%20Grade.png)

### The Scores on School Spending per Student

![__](https://github.com/Johnnytoobadman/School_District_Analysis/blob/main/PNG%20Files/Scores%20on%20School%20Spending%20per%20Student.png)

### The Scores by School Size

![__](https://github.com/Johnnytoobadman/School_District_Analysis/blob/main/PNG%20Files/Scores%20by%20School%20Size.png)

### The Scores by School Type

![__](https://github.com/Johnnytoobadman/School_District_Analysis/blob/main/PNG%20Files/Scores%20by%20School%20Type.png)

## Results

### The impact of nullifying the 9th grade Math and Reading Scores for Thomas High School are as follows:

### How the District Summary is Affected
There was only a very slight decrease in scores (less than 1%) in Average Math Scores, % Passing Math Scores, % Passing Reading Scores and the Overall % Passing Scores.

before:
![__](https://github.com/Johnnytoobadman/School_District_Analysis/blob/main/PNG%20Files/District%20Analysis1.png)

after:
![__](https://github.com/Johnnytoobadman/School_District_Analysis/blob/main/PNG%20Files/PyCity%20District%20Summary.png)

### How the School Summary is Affected
The per school Summary is the same except for Thomas High Schoool which had slightly lower scores as a result of nullifying the 9th gradres scores.

before:
![__](https://github.com/Johnnytoobadman/School_District_Analysis/blob/main/PNG%20Files/Per%20School%20Analysis1.png)

after:
![__](https://github.com/Johnnytoobadman/School_District_Analysis/blob/main/PNG%20Files/School%20Summary%20DataFrame.png)

### How Does replacing the ninth graders math and reading scores affest Thomas High School's performance relative to other schools.
As stated earlier by nullyfying the THS 9th graders scores the scores for THS changed slightly down.  Other schools scores remained unchanged.

before Math:

![__](https://github.com/Johnnytoobadman/School_District_Analysis/blob/main/PNG%20Files/Math%20scores%20by%20grade1.png)

after Math:
![__](https://github.com/Johnnytoobadman/School_District_Analysis/blob/main/PNG%20Files/Average%20Math%20Score%20by%20Grade.png)



before reading:

![__](https://github.com/Johnnytoobadman/School_District_Analysis/blob/main/PNG%20Files/reading%20scores%20by%20grade1.png)

after Reading:

![__](https://github.com/Johnnytoobadman/School_District_Analysis/blob/main/PNG%20Files/Average%20Reading%20Score%20by%20Grade.png)

## How does replacing the 9th grade scores affect the following:

### Math and Reading scores by grade
before and after:
	SEE ABOVE MATH AND READING SCORES
	 
### Scores by school spending
Unchanged for all except the 3rd Bin ($631 - $645/student) which are impacted by the slightly lower THS scores.
before and after:
![__](https://github.com/Johnnytoobadman/School_District_Analysis/blob/main/PNG%20Files/Student%20spending%20by%20school1.png)
	 
![__](https://github.com/Johnnytoobadman/School_District_Analysis/blob/main/PNG%20Files/Spending%20by%20school%20summary.png)	 

### Scores by School Size
Unchanged except for the Medium sized schools which includes THS.  Because the decimals are set to zero the change can't be observed on these analysis but it would be there ever so slightly.

before and after:
![__](https://github.com/Johnnytoobadman/School_District_Analysis/blob/main/PNG%20Files/School%20size1.png)

![__](https://github.com/Johnnytoobadman/School_District_Analysis/blob/main/PNG%20Files/Scores%20by%20School%20Size.png)

### Scores by School Type
Likewise we would need to see results into the hundreds decimal place to see the impact in the Charter Type (THS is a Charter School).

before and after:
![__](https://github.com/Johnnytoobadman/School_District_Analysis/blob/main/PNG%20Files/School%20type1.png)

![__](https://github.com/Johnnytoobadman/School_District_Analysis/blob/main/PNG%20Files/Scores%20by%20School%20Type.png)


## Summary
### The Analysis of the PyCity School District for Grades 9 through 12 showed the following:

•	The Thomas High School 9th Graders represent approximately 28% of the students at Thomas High School.  Although we can’t tell what grade modifications were made to the 9th graders grades a rough scan of their grades shows a somewhat normal distribution.  Therefore once these 9th grader grades are nullified (NaN) the impact to the overall results for Thomas High School will be minimal. Since these students represent approximately 1% of the students in the school district the impact to the overall district analysis will be insignificant.
 
•	The four changes to the updated school District analysis after Thomas High School 9th grade reading and math scores were nullified was less than 1% decrease in the following:

	o	Average math scores
	o	% Passing math
	o	% Passing reading 
	o	% Overall Passing
