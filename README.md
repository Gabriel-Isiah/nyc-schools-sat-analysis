# NYC Schools SAT Analysis (Pandas Project)

## Overview
This project explores NYC public school SAT performance using Python and pandas. The goal was to analyze patterns in academic performance across schools and boroughs, identify top-performing schools, and understand how performance varies across New York City.

Although this began as a guided DataCamp exercise, it was extended with additional exploratory analysis to strengthen my understanding of data manipulation and real-world data interpretation.

---

## What I Learned
Through this project, I strengthened my ability to work with real datasets using pandas and developed a more structured approach to exploratory data analysis. Key learnings include:

- How to clean and transform raw data into meaningful metrics (e.g., total SAT score)
- How to use `groupby` and aggregation to summarize data at different levels (school and borough)
- How to apply filtering and conditional logic to extract meaningful subsets of data
- How to create new features from existing columns to answer analytical questions
- How to rank and compare entities using sorting and top-N selection
- How to classify data into categories using conditional logic (`np.select`)
- How to think in terms of questions instead of steps, which is essential for data analysis

---

## Dataset
The dataset contains NYC school-level SAT performance data, including:

- Average Math scores
- Average Reading scores
- Average Writing scores
- Borough classification
- School names

A **total SAT score** was created by summing Math, Reading, and Writing scores.

---

## Key Analyses

### 1. Top Performing Schools (Math)
Identified schools with strong math performance by selecting those scoring at least 80% of the maximum possible math score.

### 2. Overall Top Schools
Computed total SAT scores and ranked the **top 10 schools** based on combined performance across all subjects.

### 3. Borough-Level Performance
Aggregated data by borough to understand:
- Average SAT performance
- Variation in performance (standard deviation)
- Number of schools per borough

This helped identify differences in both performance level and consistency across NYC.

### 4. Subject Performance Imbalance
Created a measure of imbalance within schools by comparing the highest and lowest subject scores. This highlighted schools where performance is uneven across Math, Reading, and Writing.

### 5. Borough Variability Classification
Boroughs were grouped into **low, medium, and high variability** categories based on the standard deviation of total SAT scores, providing a clearer interpretation of performance consistency across regions.

### 6. College Readiness Benchmark
Analyzed the percentage of schools in each borough scoring **1500 or above** in total SAT, used as a benchmark for college readiness. This allowed comparison of high-performing school distribution across boroughs.

---

## Key Insights

- NYC school performance is unevenly distributed across boroughs
- Some boroughs show high variability, meaning large gaps between high and low performing schools
- High-performing schools are clustered rather than evenly spread
- Subject-level differences reveal that some schools are strong in one area but weak in others
- Borough-level analysis provides better insight than looking at individual schools alone

---

## Skills Used

- `pandas` (groupby, agg, filtering, sorting)
- Feature engineering
- Conditional logic (`np.select`)
- Aggregation and summary statistics
- Data exploration and interpretation
- Analytical thinking and problem framing

---

## Tools

- Python
- pandas
- NumPy
