                              Student Performance Analysis System (Synthetic Data)
Project Overview

The Student Performance Analysis System is a data analytics project that generates a synthetic student dataset and performs Exploratory Data Analysis (EDA) to understand academic performance patterns. The project helps identify top-performing students, students needing improvement, and relationships between factors such as attendance, internal marks, and academic scores.

Since the data is synthetically generated, the project can be used for educational purposes without privacy concerns.

Problem Statement

Educational institutions generate large amounts of student performance data. Analyzing this data manually is time-consuming, inefficient, and prone to errors. This project provides an automated approach to generate, process, analyze, and visualize student performance data to support academic decision-making.

Objectives
Generate a synthetic dataset containing student academic records.
Perform data cleaning and preprocessing.
Calculate descriptive statistics for student performance.
Analyze total marks, average marks, and grades.
Identify top-performing and low-performing students.
Perform department-wise, gender-wise, and year-wise analysis.
Study relationships between attendance, internal marks, and academic performance.
Visualize insights using charts and graphs.
Derive meaningful conclusions from the data.
Dataset Description

The dataset contains 250 student records with the following attributes:

Column Name	Description
Student_ID	Unique student identifier
Name	Student name
Gender	Male/Female
Department	CSE, IT, ECE
Year	1st, 2nd, 3rd
Maths	Marks obtained in Mathematics
Science	Marks obtained in Science
English	Marks obtained in English
Attendance	Attendance percentage (50–100%)
Internal	Internal assessment marks (0–25)
Derived Columns
Column Name	Description
Total	Sum of Maths, Science, and English marks
Average	Average marks
Grade	Performance grade based on average marks
Technologies Used
Python
NumPy
Pandas
Matplotlib
Faker
Project Workflow
1. Data Generation
Generate 250 synthetic student records using Faker and NumPy.
Assign random departments, years, marks, attendance, and internal scores.
2. Data Preprocessing
Verify data types.
Check for missing values.
Ensure data consistency.
3. Feature Engineering
Calculate Total Marks.
Calculate Average Marks.
Assign Grades.
4. Exploratory Data Analysis (EDA)
Descriptive statistics.
Department-wise analysis.
Gender-wise analysis.
Year-wise analysis.
Performance classification.
5. Visualization
Histogram of average marks.
Pie chart of department distribution.
Bar chart of department performance.
Scatter plot of attendance vs average marks.


                               OUTPUT

<img width="562" height="468" alt="image" src="https://github.com/user-attachments/assets/f477e1b5-4f82-4959-9c09-c002a69d7a5f" />

<img width="562" height="455" alt="image" src="https://github.com/user-attachments/assets/0c522f1b-4a94-4d4f-81de-1932b6db0f90" />

<img width="562" height="455" alt="image" src="https://github.com/user-attachments/assets/ff1299a2-66d3-41ce-bd02-71830e7dc937" />

<img width="390" height="411" alt="image" src="https://github.com/user-attachments/assets/b2c928c0-4c1f-4124-bfc0-5a023502a900" />

