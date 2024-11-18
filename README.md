# Data Distribution Analysis: Baseball Salary Insights

## Overview

This project was completed for the course **MIS 445: Statistics in Business Analytics** at **Colorado State University Global**. It focuses on performing a data distribution analysis of baseball player salaries using the dataset `SASHHELP.BASEBALL`. The analysis includes conducting **summary statistics**, calculating **z-scores**, and visualizing salary distributions with **box plots** and **histograms** to uncover trends, outliers, and key insights into player earnings in the baseball industry.

## Project Description

The primary goal of this project was to analyze the **Salary** variable within the dataset by conducting statistical analysis and visualization. This includes:

1. **Summary Statistics**:
   - Calculation of basic summary statistics, such as **mean**, **standard deviation**, **minimum**, and **maximum**, for the `Salary` variable.
   - Creation of visualizations, including **box plots** and **histograms**, to better understand the distribution of salaries and identify trends.

2. **Z-Score Analysis**:
   - Calculation of **z-scores** for the `Salary` variable using **PROC SQL**, identifying outliers in the dataset. The z-scores show how individual player salaries compare to the overall distribution, helping to pinpoint extreme values.

3. **Interpretation**:
   - An analysis of the summary statistics and z-scores provided insights into salary trends in the baseball industry. The results highlighted a **rightward skew** in the salary distribution, showing a concentration of players with lower salaries and a few outliers with substantially higher earnings.

## Findings

- **Z-Scores**: The z-scores helped identify several outliers, with a few players earning much more than the average.
- **Salary Distribution**: The box plot and histogram visualizations showed a **rightward skew**, indicating that the majority of players earn lower salaries, while a few players earn significantly higher amounts.
- **Key Statistics**:
  - **Mean Salary**: 535,925.88
  - **Standard Deviation**: 451,118.68
  - **Minimum Salary**: 67,500
  - **Maximum Salary**: 2,460,000
  - **N (Number of Players)**: 263
  - **25th Percentile**: 190
  - **75th Percentile**: 750,000
  
These findings were supported by both the **box plot** and **histogram**, which visually represented the distribution's skew and outliers.

## Conclusion

The project provides valuable insights into the salary trends within the baseball industry. By analyzing the distribution of salaries using summary statistics and z-scores, the analysis uncovers patterns such as the concentration of low salaries and the presence of a few high earners. This distribution reflects the economic structure of the baseball industry, where a small number of players earn significantly more than the majority. These findings can help stakeholders understand salary disparities and the overall financial structure in the baseball industry.

## Visualizations

- **Summary Statistics Output**: A report containing basic statistics for the `Salary` variable.
- **Z-Score Calculations**: Output from **PROC SQL** showing the z-scores for salary data.
- **Visualizations**: Box plot and histogram for salary distribution analysis.

## Tools and Technologies Used

- **SAS**: Used for performing statistical analysis and data manipulation.
- **PROC SQL**: SQL procedure in SAS for calculating z-scores.
- **Data Visualization**: Histograms and box plots to represent the salary distribution.

## Course Information

- **Course**: MIS 445: Statistics in Business Analytics
- **Institution**: Colorado State University Global
- **Instructor**: Professor Mark Bateh
- **Date Submitted**: January 7, 2023

## References

- **SAS Documentation**: Used for performing statistical analysis and data manipulation.
- **Statistical Analysis in Business Analytics**: Key textbook and course material that informed the project analysis.
