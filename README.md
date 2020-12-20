# School_District_Analysis

## Purpose
The purpose of this project was to analyze data on school funding and student's standardized test scores. The objective was to aggregate the data and demonstrate trends school performance. Results would assist the school board in making decisions regarding school budgets and funding priorities.
<br>
<br>
For the challenge, reading and math grades for Thomas High School ninth graders were removed due to suspicion of academic dishonesty. The data was then reanalyzed to determine trends and performance.

## Resources
- Data Sources: [schools_complete.csv](Resources/schools_complete.csv); [students_complete.csv](Resources/students_complete.csv)
- Software: Jupyter Notebook

## Results
- School Analysis: [PyCity Schools_Challenge](PyCitySchools_Challenge.ipynb); [PyCity_Schools](PyCitySchools.ipynb)

### How is the district summary affected?
District Summary Before Removing 9th Grade Scores
<br>
<br>
![District_Summary_Before](Resources/district_before.png)
District Summary After Removing 9th Grade Scores
<br>
<br>
![District_Summary_After](Resources/district_after.png)
- By removing the 9th grade reading and math scores, the total number of students in the district was decreased from 39,170 to 38,709 students.
- The average math and reading scores, and the percentage of passing math and reading values were not affected by removing 9th grade test scores.
- The overall passing percentage for the district was not affected, remaining at 65% after removing 9th grader scores at Thomas High School.

### How is the school summary affected?
Thomas High School After Removing 9th Grade Scores
<br>
<br>
![Column Headers](Resources/column_headers.png)
![Thomas High After](Resources/thomas_high_after.png)
- With removal of 9th grades scores, the passing math percentage for the Thomas High School decreased from 93.2% to 66.9%.
- Average reading scores were not affected, remaining at 83.8% after removing 9th grade test scores.
- For Thomas High School, the overall passing percentage decreased from 90.9% to 65%.
- The total school budget was not affected, at $1,043,130.

### How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
Replacing the ninth grade scores caused Thomas High School's performance to decrease relative to other schools. Its rank changed from the top 5 schools to being ranked in the middle.

### How does replacing the ninth-grade scores affect the following:
- Math and reading scores by grade

- Scores by school spending

- Scores by school size

- Scores by school type

## Summary
