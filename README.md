# School District Analysis

***

## Project Overview
This repository contains Jupyter Notebook applications that are programed in Python 3 which analyzes school and student academic performance data for a school district and generates student performance statistics based on the following student groupings:

* by district
* by school
* by grade
* by school spending per student
* by school size
* by school type

***

## Technical Specifications

|      Type         |             Name                |             Description            |
--------------------|---------------------------------|------------------------------------|
| Program Language  | Python 3.7.8                    |                                    |
| APIs and Modules  | Anaconda 4.8.3                  |                                    |
|                   | Pandas 1.0.3                    |                                    |
| Data Sources      | resources/schools_complete.csv  |                                    |
|                   | resources/students_complete.csv |                                    |
| Programming Tools | Jupyter Notebook                |                                    |
| Application Files | PyCitySchools.ipynb             | School district analysis all data  |
|                   | PyCitySchools_challenge.ipynb   | School district analysis EXCLUDING Thomas High School 9th Grade |



***

## PyCitySchools.ipynb Jupyter Notebook Application
### Student Performance Summary Tables By Student Grouping

### By District
![Summary By District](https://github.com/berndab/school_district_analysis/blob/master/summary_tables/summary_table_1_by_district.jpg)

### By School
![Summary By School](https://github.com/berndab/school_district_analysis/blob/master/summary_tables/summary_table_2_by_school.jpg)

### By School Ranked 
![Summary By School Ranked](https://github.com/berndab/school_district_analysis/blob/master/summary_tables/summary_table_2A_by_school_ranked.jpg)

### By Grade Math
<img src="https://github.com/berndab/school_district_analysis/blob/master/summary_tables/summary_table_3M_by_grade_math.jpg" width="330" height="450" />

### By Grade Reading
<img src="https://github.com/berndab/school_district_analysis/blob/master/summary_tables/summary_table_3R_by_grade_reading.jpg" width="330" height="450" />

### By Spending Per Student
![Summary By Per_Student Spending](https://github.com/berndab/school_district_analysis/blob/master/summary_tables/summary_table_4_by_spending_per_student.jpg)

### By School Size
![Summary By School_Size](https://github.com/berndab/school_district_analysis/blob/master/summary_tables/summary_table_5_by_school_size.jpg)

### By School Type
![Summary By School_Type](https://github.com/berndab/school_district_analysis/blob/master/summary_tables/summary_table_6_by_school_type.jpg)

****

### Analysis

The overall student passing percentage is the most important factor for the school district administration to consider. It is an indicator of how many students may not advance to the next grade or graduate from high school. The district student performance data shows that the 35% of the district students are not passing both math and science. This is a crisis for the district because of the addition pressure put on the limited education resource in order to provide the remedial educational assistance to remedy this crisis. 


The district student performance data further indicates poor student math performance is the biggest contributor to the low student overall passing percentage.  The overall math passing percentage is 11% percent lower than the overall reading passing percentage. Data from the school performance data rank table further illustrates how much poor math performance contributes to the low overall passing percentage.  The table data shows that that the average reading passing percentage of bottom 7 schools is 16% lower than the average reading passing percentage of the top 8 schools. However, the average math passing percentage of bottom 7 schools is 27% lower than the average reading passing percentage of the top 8 schools which is almost double of the average reading percentage difference.


The data from the spending per student summary table show that there is a significant negative correlation of student performance to per capita student spending particularly for math. Reading passing percentage decreased by 16% between going from the lowest to the highest per capita spending rage but math passing percentage decrease by 27%. Again, almost double the reading passing percentage decrease. The data show that additional funding will not fix the problem with the way the district is currently being managed. 
Data from the student performance by school size and student performance by school type tables do show the math performance significantly increased based on school size and type. The is a 24 percent increase in the math passing rate between schools with student populations between 2000  and 5000 and those with populations less 1000. while there is a 27% greater math passing rate for charter schools over district schools. The data show that creating additional charter schools with population less than 1000 would be very effective in greatly increasing the overall distinct math passing rate and significantly increasing the overall student passing rate of the district and significantly reducing the crisis. 

***

##  PyCitySchools_Challenge.ipynb Jupyter Notebook Application

### Student Performance Summary Table By Student Grouping 
### !! Minus Thomas High School 9th Grade Math and Reading Scores 

### By District
![Summary By District](https://github.com/berndab/school_district_analysis/blob/master/summary_tables/summary_table_1_by_district_-_thomas.jpg)

### By School
![Summary By School](https://github.com/berndab/school_district_analysis/blob/master/summary_tables/summary_table_2_by_school_-_thomas.jpg)

### By School Ranked 
![Summary By School Ranked](https://github.com/berndab/school_district_analysis/blob/master/summary_tables/summary_table_2A_by_school_ranked_-_thomas.jpg)

### By Grade Math
<img src="https://github.com/berndab/school_district_analysis/blob/master/summary_tables/summary_table_3M_by_grade_math_-_thomas.jpg" width="330" height="450" />

### By Grade Reading
<img src="https://github.com/berndab/school_district_analysis/blob/master/summary_tables/summary_table_3R_by_grade_reading_-_thomas.jpg" width="330" height="450" />

### By Spending Per Student
![Summary By Per_Student Spending](https://github.com/berndab/school_district_analysis/blob/master/summary_tables/summary_table_4_by_spending_per_student_-_thomas.jpg)

### By School Size
![Summary By School_Size](https://github.com/berndab/school_district_analysis/blob/master/summary_tables/summary_table_5_by_school_size_-_thomas.jpg)

### By School Type
![Summary By School_Type](https://github.com/berndab/school_district_analysis/blob/master/summary_tables/summary_table_6_by_school_type_-_thomas.jpg)

***

### Analysis



