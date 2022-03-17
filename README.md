# School_District_Analysis


Overview of the School District Analysis
	
	The purpose of this analysis was to summarize and examine data on student funding and standardized test scores across multiple schools in differing districts. Using our findings, we were able to distinctively categorize math and reading scores for each grade level by school type, school size, and the funding allocated for each student. For Thomas High School, Maria was able to identify trends in overall school performance once the math and reading scores were replaced for the ninth graders.

Results
 
o How is the district summary affected?
- The overall passing percentage in the district summary is < 70%. 
- Whereas the individual percentages for passing math and reading are higher, falling between 74% - 86%. 
 
o How is the school summary affected?
- By replacing the math, reading, and overall percentages for Thomas High School using the calculations for 10th – 12th graders, the percentages drastically increased.
- The passing percentages taken of the 10th – 12th graders were all over 90%. As shown in the figure below.

o How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?

- Replacing the ninth graders’ math and reading scores drastically increased performance in both subjects for Thomas High School.
- Below is the “per_school_summary” dataframe depicting the statistics from a few of the other schools.

- In comparison, when the scores are replaced, the dataset for Thomas High School becomes limited. Therefore, the average of the scores in each subject become higher. As shown in the figure below.

o How does replacing the ninth-grade scores affect the following:

* Math and reading scores by grade

- The math and reading scores of students in grades 10 – 12 remained the same when examined individually. However, when the scores for each of these grades were grouped and taken into consideration, the overall passing rate for each subject increased substantially. 

* Scores by school spending

- As the spending range increases per student, the overall math and reading scores decrease. 

* Scores by school size

- The difference between schools categorized in small and medium school is little to none. The average math and reading scores, as well as overall passing percentages remain relatively the same.
- However, moving from medium to large school sizes, the average and passing scores both decrease significantly. 

* Scores by school type

- The district school type’s overall passing percentage is much lower than that of the charter school type.
-  Once the scores for ninth graders at Thomas High School were replaced, the combined average of the other grades increased. 

Summary:

1. The percentage of students passing math increased significantly after the ninth graders scores were replaced with NaNs. The value went from 75% to 93.2%.

2. Additionally, the percentage of students passing reading also increased from 86% to 97%.

3. The overall passing percentage managed to decrease from 65.17% to 64.85%. This was due to the overall total student count decreasing in the updated school district analysis.

4. The average math and reading scores remained relatively the same after the ninth graders scores were replaced, as the “NaNs” will not impact other values as they are placeholders.


	
