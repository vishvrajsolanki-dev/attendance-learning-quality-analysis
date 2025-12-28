# Attendance vs Learning Quality Analysis

## Overview
Educational institutions often assume that high attendance automatically leads to better learning. This project analyzes whether attendance alone is a reliable indicator of learning quality using real academic data.

## Dataset
The project uses the UCI Student Performance dataset, which contains demographic information, study habits, attendance records, and academic performance of secondary school students.

## Problem Statement
Does higher attendance truly reflect better learning quality, or are additional factors required to understand student learning?

## Approach
- Loaded and explored real academic data
- Used number of absences as an attendance indicator
- Engineered a custom Learning Quality variable using study time, failures, and attendance
- Analyzed the relationship between attendance and learning quality
- Trained a simple Logistic Regression model to support the analysis

## Tools Used
- Python
- Pandas
- Matplotlib
- Scikit-learn
- Jupyter Notebook

## Key Insight
The analysis shows that while attendance is related to learning quality, it is not sufficient on its own to fully represent how well a student is learning.

## Conclusion
This project demonstrates a thoughtful, data-driven evaluation of a common assumption in education and highlights the importance of using multiple indicators to assess learning quality.
