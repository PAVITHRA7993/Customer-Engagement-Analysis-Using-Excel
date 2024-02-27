**Data Description:**
1.student_id – the unique identifier for each student in the dataset. The field contains IDs for students who used the 365 Data Science platform with free or paid accounts in Q4 2021 (October 1, 2021 – December 31, 2021, both included) and Q4 2022 (October 1, 2022 – December 31, 2022, both included).

2.student_country – identifies the country of each student. The field provides information about students’ geographic location and can help analyze regional differences or conduct country-specific analyses.

3.Paid – indicates whether a student had a paid account during the specified period. It is a binary variable, where '1' represents a paid account and '0' represents a free or unpaid account. It helps differentiate between students who have access to additional features or content through a paid subscription.

4.minutes_watched_21 – represents the student’s engagement level, as expressed by the number of minutes a student has watched in Q4 2021.

5.minutes_watched_22 – denotes the student’s engagement level, as expressed by the number of minutes a student has watched in Q4 2022.
**Part 1: Descriptive Analytics**
Task 1: Finding the Mean, Median, Standard Deviation 
Task 2: Finding the skewness and kurtosis
**Part 2: Confindence Intervals**
Task 3: 
* Students who haven’t had a paid-plan subscription
-Engaged in Q4 2021
-Engaged in Q4 2022
* Students who have been paid-plan subscribers
-Engaged in Q4 2021
-Engaged in Q4 2022
By using Z-Statistics
**Part 3: Hypothesis Testing**
Task 4: To reach a data-driven customer engagement decision on whether the platform’s new features contribute to the increase of minutes watched on the platform for both free-plan and paying students.
Null Hypotheses:The engagement (minutes watched) in Q4 2021 is higher than or equal to the one in Q4 2022 (μ1 ≥ μ2). We test free-plan and paying students separately.
Assumptions: 
* For free-plan students, perform a two-sample t-test assuming unequal variances.
* For paying students, conduct a two-sample t-test assuming unequal variances.
* To perform a two-sample F-test for variance to support the assumptions.
Task 5: Determing whether the average number of minutes watched in the US is similer to that in India.
Null Hypotheses: 
* The engagement (minutes watched) in the US is higher than or equal to that in India (μ1 ≥ μ2). We test only free-plan students.
* The engagement (minutes watched) in the US is lower than that in India (μ1 < μ2). We test only free-plan students.
Assumptions:
* Performing a two-sample t-test assuming unequal variances.
* Performing a two-sample f-test for variances to support the assumptions.

