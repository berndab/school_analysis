# School District Analysis

## Project Overview
This repository contains Jupyter Notebook applications that are programed in Python 3 which analyze school and student academic performance data for a school district and generate student performance statistics based on the following student groupings:

* by district
* by school
* by grade
* by school spending per student
* by school size
* by school type

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


The data from the spending per student summary table show that there is a significant negative correlation of student performance to per capita student spending particularly for math. Reading passing percentage decreased by 16% between going from the lowest to the highest per capita spending range but math passing percentage decrease by 27%. Again, almost double the reading passing percentage decrease. The data show that additional funding will not fix the problem with the way the district is currently being managed. 
data from the student performance by school size and student performance by school type tables do show the math performance significantly increased based on school size and type. There is a 24 percent increase in the math passing rate between schools with student populations between 2000 and 5000 and those with populations less 1000. There is a 27% greater math passing rate for charter schools over district schools. This data shows that creating additional charter schools with population less than 1000 would be very effective in greatly increasing the overall distinct math passing rate and significantly increasing the overall student passing rate of the district which should intern significantly reduce the magnitude this current crisis. 

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

There are two approaches to calculating student performance data with the reading and math scores from the 9th grade Thomas High School set to NaN
* Approach 1 - INCLUDE the students from the 9th grade Thomas High School set to NaNn in all student counts
*	Approach 2 - DO NOT INCLUDE the students from the 9th grade Thomas High School set to NaNn in all student counts

Since the NEITHER Module 4 Challenge instructions NOR the challenge rubric specifies that we must NOT INCLUDE the students from the 9th grade Thomas High School set in student count calculations, 

The implementation follows Approach 1


Removing the suspect reading and math scored of the Thomas High School’s 9th grade student did have a noticeable effect on the district’s math, reading, and overall passing percentage by reducing all three by 1%. There are two reasons for this. One is that the Thomas 9th grade class had a high average math score of 86 and a high average reading score of 83, but now with classes reading and math scores set to NaN, the classes average scores are not zero. Second, the instructions did not explicitly state that the students count for this class should be excluded from the district summary performance calculations. We can infer from this that if the actual scores for the class are significantly lower than the current suspect values, it will have a significant effect on reducing the districts overall performance not as much as 1% but in the range of 0.5% which still is significant.

However, with or without this classe's scores, the district will still have a serious student performance problem with the percentage of students not passing both math and reading remaining in the 35% range.

Replacing the 9th grade Thomas High School student score with NaN significantly reduced the performance ranking of the school which previously was ranked second overall in performance and now with the NaN values, the school’s performance ranking drops to 8th place. From the point of view of the Thomas High School administration, if the actual performance scores averages are determined to be significantly lower, the school ranking reduction could put the school in the problem school catigory. 

Replacing 9th grade Thomas High School student scores with NaN did have a significant effect on the performance statistics for the spending category $630-644, reducing the student percentage passing for math, reading and overall significantly. This strengthens the negative correlation between student performance with per capita student spending. Again, this is because the excluded classe had high average scores which are now zero do to the student score values being set to NaN. Again, no matter what the actual valid scores turn out to be for the class, the district administration will still have to rectify the negative correlation of spending and student performance.

The 9th grade student score set to NaN negatively affected the school performance by size category of Medium (1000-2000) but does not significantly affect the correlation of increased student performance with smaller school size. It also negatively affected the school performance by type category of charter but the passing percentages for all measures still remains in the high 80’s and 90’s. Again, the 9th grade student scores set to NaN had a negligible influence between the correlation of higher student performance for charter school type.

Overall setting the classes scores to NaN does not change the position stated in the original analysis, that the district has a serious student performance problem. The data shows that more spending most likely will not reduce the student performance problem. It also shows that opening more charter school and reducing school size would be the most effective solution to reducing the peformance problem. 
