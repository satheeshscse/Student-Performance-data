# Student Performance Analysis

## Overview
This Python program analyzes student marks from an Excel file and identifies:

- Highest mark student
- Middle mark student
- Lowest mark student
- Total marks
- Average marks
- Statistical summary of all marks
- Performance comparison using a pie chart

## Technologies Used
- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn

## Required Libraries
Install the required libraries using:

```bash
pip install numpy pandas matplotlib seaborn openpyxl
```

## Input File
The program reads data from an Excel file:

`II CSE C -mark.xlsx`

The Excel file should contain the following columns:

- Student Name
- Roll No
- Toc
- Java
- Ml
- CS
- SE
- CN

## Features

### 1. Calculate Total and Average Marks
- Adds marks from all 6 subjects
- Computes average mark for each student

### 2. Find Student Performance Levels
- **Highest Mark Student** → Student with maximum total marks
- **Middle Mark Student** → Student whose total is closest to median marks
- **Lowest Mark Student** → Student with minimum total marks

### 3. Data Visualization
- Displays a pie chart comparing:
  - Highest performer
  - Middle performer
  - Lowest performer

### 4. Statistical Analysis
Shows:
- Mean
- Standard deviation
- Minimum marks
- Maximum marks
- Quartiles

## Output Example

### Highest Mark Student
- Name: DAWOOD MARVA R
- Roll No: 24CS0168
- Total: 549
- Average: 91.5

### Middle Mark Student
- Name: DHARSHAN KUMAR
- Roll No: 24CS0198
- Total: 490
- Average: 81.67

### Lowest Mark Student
- Name: DEEPAK M
- Roll No: 24CS0175
- Total: 335
- Average: 55.83

## Visualization
A pie chart is generated to compare student performance percentages.

## How to Run
1. Place the Excel file in the correct directory.
2. Open Python or Jupyter Notebook.
3. Run the script.

```bash
python student_performance.py
```

## Sample Analysis
The program generates:
- Student ranking analysis
- Total and average marks
- Performance comparison chart
- Statistical summary using `describe()`

## Conclusion
This project helps analyze student academic performance quickly and visually using Python data analysis libraries.
