# Student Performance Analysis

An exploratory data analysis (EDA) project examining how gender, test preparation, and parental education level relate to student academic performance.

## Objective

To analyze student performance data and identify key factors influencing academic success, using NumPy, Pandas, Matplotlib, and Seaborn.

## Dataset

- **Source:** [Students Performance Dataset (Kaggle)](https://www.kaggle.com/datasets/spscientist/students-performance-in-exams)
- Contains math, reading, and writing scores along with demographic and background details (gender, parental education, test preparation course status)

## Project Workflow

1. **Data Loading & Exploration** — Checked dataset structure, data types, and missing values
2. **Feature Engineering** — Calculated an average score across math, reading, and writing, and assigned letter grades (A/B/C/D) based on performance bands
3. **Data Visualization**
   - Histogram: distribution of average scores by gender
   - Bar plot: average score by gender and grade
   - Boxplot: effect of test preparation course on scores, by gender
   - Heatmap: correlation between subject scores
   - Countplot: grade distribution by gender
   - Pairplot: pairwise relationships between subject scores
   - Bar plot: effect of parental education level on performance
4. **Statistical Insights** — Computed highest, lowest, mean, and median average scores
5. **Top Performers** — Identified top 5 students by average score
6. **Correlation Analysis** — Subject-wise correlation table

## Key Insights

- Female students tend to perform better in reading and writing
- Male students perform slightly better in math
- Students who completed the test preparation course achieved higher average scores
- Higher parental education levels are associated with better student performance
- Reading and writing scores are strongly correlated with each other

## Tech Stack

Python, Pandas, NumPy, Matplotlib, Seaborn

## Setup Instructions

1. Download the dataset from [Kaggle](https://www.kaggle.com/datasets/spscientist/students-performance-in-exams)
2. Upload `StudentsPerformance.csv` to your Google Colab environment (or place it in the same folder as the notebook)
3. Open `Student_Performance_Analysis.ipynb` and run cells in order

## Output

The notebook exports a processed summary (`student_performance_summary.csv`) containing the original data along with calculated average scores and grades.
