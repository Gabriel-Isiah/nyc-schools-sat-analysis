NYC Schools SAT Analysis (Pandas Project)

Overview This project explores NYC public school SAT performance using
Python and pandas. The goal was to analyze school-level and
borough-level performance patterns, identify top-performing schools, and
understand variation in academic outcomes across New York City.

This project started as a guided DataCamp exercise but was extended with
additional exploratory analysis to deepen understanding of data
manipulation and real-world interpretation.

Dataset The dataset contains NYC school-level SAT performance data,
including: - Average Math scores - Average Reading scores - Average
Writing scores - Borough classification - School names

A total SAT score was created by summing Math, Reading, and Writing
scores.

Key Analyses

1.  Top Performing Schools (Math) Identified schools with strong math
    performance, defined as scoring at least 80% of the maximum possible
    math score.

2.  Overall Top Schools Computed total SAT scores and ranked the top 10
    schools based on combined performance across all subjects.

3.  Borough-Level Performance Aggregated data by borough to compute:

-   Average SAT score
-   Standard deviation of SAT scores (variability)
-   Number of schools per borough

4.  Subject Performance Imbalance Measured differences within schools by
    comparing highest and lowest subject scores to identify uneven
    performance.

5.  Borough Variability Classification Boroughs were grouped into low,
    medium, and high variability based on SAT score standard deviation.

6.  College Readiness Benchmark Analyzed the percentage of schools in
    each borough scoring 1500 or above in total SAT.

Key Insights - Performance varies significantly across NYC boroughs. -
Some boroughs show high inequality in school outcomes. - High-performing
schools are not evenly distributed. - Subject-level gaps exist within
many schools.

Skills Used - pandas data manipulation - groupby and aggregation -
filtering and conditional selection - feature engineering - ranking and
sorting - np.select classification

Tools - Python - pandas - NumPy
