# Simple ANOVA Analysis – Compare Marks of Students from 3 Different Classes

## Overview
This project demonstrates how to perform a **One-Way ANOVA (Analysis of Variance)** test using Python to compare the marks of students from three different classes.

The program checks whether there is a statistically significant difference in the average marks among the classes and visualizes the data using a boxplot.

## Technologies Used
- Python
- NumPy
- SciPy
- Matplotlib

## Dataset
Three classes are considered:

- Class A: 75, 80, 85, 90, 95
- Class B: 70, 72, 78, 74, 76
- Class C: 88, 85, 91, 89, 87

## Steps Performed
1. Import required libraries.
2. Define marks for three classes.
3. Perform One-Way ANOVA using `scipy.stats.f_oneway()`.
4. Display the F-statistic and P-value.
5. Determine whether a significant difference exists between the classes.
6. Visualize the marks distribution using a boxplot.

## Output
The program provides:
- F-Statistic value
- P-Value
- Interpretation of ANOVA result
- Boxplot visualization of class marks

## How to Run
1. Install required libraries:
   ```bash
   pip install scipy numpy matplotlib
