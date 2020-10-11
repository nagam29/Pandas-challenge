# Analysis on School Types and Academic Performance

### Goal
Examine whether the academic performance of students with charter schools is better than that those with district / public schools

### Summary

The majority of the district school students presented the similar academic achievement with the students with the charter schools. For example, the math scores of most of the students with the district schools were higher than 70, that was the same as the scores with the charter school students. However, the variability of the scores were larger with the district school students. This seemed to be one of the reasons that the average test scores of district school students appear to be lower than the charter school students.  We need to look into the reasons for the large variability in the scores before concluding that the academic performance of district schools is lower than the charter schools.

### Method
I used the data about types of school, their budget and students, and academic performance. The names of schools and their students were modified to protect their privacy. Analysis was conducted using a few descriptive statistics through python/pandas. Tableau was used for data visualization to summarize and present the findings.

### Findings

**Tableau Dashboard: Summary 1: School Type, Budget, and Performance**
We often hear that public schools are in general more expensive and their students' academic performance is worse than charter schools. The charts presented in the Summary 1 Tab seem to support that notion. For example, “Budget, Type of School, Academic Performance” appears to show per student budget for the charter schools were in general a little more than $40 (about 7%) lower than the district schools. Average math and reading scores for the charter schools were about 8% higher than the district schools. 

**Tableau Dashboard: Summary 2: School Type and Academic Performance**
Box charts in the Summary 2 present that math scores and reading scores for the different school types. They present the scores varied more widely for the district schools compared to those for the charter schools. Because of the large variability, the average academic scores of the district school students appeared to be lower. In other words, the low average math/reading scores at the district school can be a mathematical artifact.

**Tableau Dashboard: Summary 3: School Type, Academic Performance **
The chart presents more detailed information about schools, school types, the numbers of students, and the math score of each student in the schools. The majority of the district school students have the scores above 70, which is the same/similar level of achievement of the students with the charter schools. This indicates that 1) we cannot simply conclude that the academic achievement of the district schools is lower than the charter schools, and 2) the lower mean scores might be a mathematical artifact of the scores with the large variability. 

### Next Step
The academic performance of district schools might appear to be lower than the charter schools. However, the outcomes of analysis seem to indicate that it was related to the large variability in the scores among the students of district schools. We need to look into the reasons for the large variability as the first step to address lower math and/or reading scores.

### Note
Please go to  the folder: PyCitySchools.  You can find items below.
Program --  PyCitySchools.ipynb. 
Data -- CSV files are schools_complete.csv and students_complete.csv
Tableau Dashboard:  School_Budget_Students

