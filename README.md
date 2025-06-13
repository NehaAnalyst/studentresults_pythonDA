# Student Academic Performance Analysis

## Project Overview

This project involves a detailed exploratory data analysis (EDA) of student academic performance. The primary objective is to uncover insights and relationships within a dataset containing various student attributes and their scores in Math, Reading, and Writing. The analysis identifies key factors that might influence student performance, providing valuable insights for educational strategies.

## Objective

The main goals of this project are:
* To perform comprehensive data cleaning and preprocessing on the student dataset.
* To analyze the distribution of various demographic and behavioral factors among students.
* To investigate the correlation between different student and parental attributes (e.g., gender, parental education, marital status) and student academic scores.
* To visualize key findings using appropriate statistical plots to communicate insights effectively.

## Data Source

The analysis is based on the `student_Score.csv` dataset.
* **Dataset Description:** This dataset contains information on student demographics, parental background, weekly study hours, and scores in three subjects: Math, Reading, and Writing.
* **Key Columns:**
    * `Gender`: Gender of the student.
    * `EthnicGroup`: Ethnic group of the student.
    * `ParentEduc`: Education level of parents.
    * `LunchType`: Type of lunch provided (standard/free-reduced).
    * `TestPrep`: Test preparation course completion status.
    * `ParentMaritalStatus`: Marital status of parents.
    * `PracticeSport`: Whether the student practices sport.
    * `IsFirstChild`: Indicates if the student is the first child.
    * `NrSiblings`: Number of siblings.
    * `TransportMeans`: Means of transport to school.
    * `WklyStudyHours`: Weekly study hours.
    * `MathScore`: Score in Math.
    * `ReadingScore`: Score in Reading.
    * `WritingScore`: Score in Writing.

## Tools and Technologies

* **Python:** The primary programming language used for data analysis.
* [cite_start]**Pandas:** For data manipulation and analysis. 
* [cite_start]**NumPy:** For numerical operations. 
* [cite_start]**Matplotlib:** For static, interactive, and animated visualizations. 
* [cite_start]**Seaborn:** Built on Matplotlib, used for drawing attractive and informative statistical graphics. 

## Analysis Steps & Methodology

The analysis followed these key steps:

1.  **Data Loading and Initial Inspection:**
    * [cite_start]Loaded the `student_Score.csv` dataset into a Pandas DataFrame. 
    * [cite_start]Performed initial checks using `df.head()`, `df.describe()`, and `df.info()` to understand data structure, summary statistics, and data types. 
2.  **Data Cleaning and Preprocessing:**
    * [cite_start]Identified and calculated the sum of null values across all columns. 
    * [cite_start]Dropped the redundant 'Unnamed: 0' column. 
    * [cite_start]Transformed the 'WklyStudyHours' column, replacing '05-Oct' with '5-10' for consistency in categorical representation. 
3.  **Exploratory Data Analysis (EDA) and Visualization:**
    * [cite_start]**Gender Distribution:** Analyzed the gender distribution of students, revealing that the number of females is slightly higher than males. 
    * **Parental Education vs. Student Scores:** Investigated the relationship between parents' education levels and students' Math, Reading, and Writing scores using a heatmap. [cite_start]Concluded that parental education has a significant positive impact on children's scores. 
    * **Parental Marital Status vs. Student Scores:** Explored the impact of parents' marital status on student scores through a heatmap. [cite_start]The analysis indicated that parental marital status does not have a major or significant impact on student performance. 
    * [cite_start]**Outlier Detection:** Used box plots to visualize the distribution and identify outliers in Math, Reading, and Writing scores. 
    * [cite_start]**Ethnic Group Distribution:** Examined the distribution of different ethnic groups within the dataset using both pie and bar charts. 

## Key Insights and Conclusions

* [cite_start]The dataset shows a balanced gender distribution among students, with a slight predominance of females. 
* [cite_start]A strong positive correlation exists between parents' education level and their children's academic performance, suggesting that higher parental education generally corresponds to better student scores. 
* [cite_start]The marital status of parents appears to have minimal to no significant impact on student scores. 
* Outliers are present in the score distributions, which might warrant further investigation depending on the project's scope.
* The distribution across different ethnic groups provides demographic context for the student population.



## Contact

For any questions or collaborations, feel free to reach out:

* **Neha Sharma**
* **Email:** kr.nehasharma2016@gmail.com


---
