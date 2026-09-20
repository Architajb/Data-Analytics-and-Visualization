# ANOVA on UCI and Pima Indians Diabetes Datasets

## Aim

To perform One-Way ANOVA on selected numerical variables from the UCI Diabetes and Pima Indians Diabetes datasets.

## Software Requirements

- Python 3.13.2
- Jupyter Notebook 7.3.2

## Libraries Used

- Pandas
- NumPy
- SciPy

## Theory

Analysis of Variance (ANOVA) is a statistical method used to determine whether significant differences exist between group means.

### Features Analyzed

- Glucose
- BloodPressure
- BMI

### Decision Rule

- p-value < 0.05 → Significant Difference
- p-value ≥ 0.05 → No Significant Difference

## Procedure

1. Import the required libraries.
2. Load the datasets.
3. Select relevant numerical columns.
4. Apply One-Way ANOVA.
5. Calculate F-statistics and p-values.
6. Interpret the results.

## Result

The p-values for Glucose, Blood Pressure, and BMI are greater than 0.05. Therefore, there is no statistically significant difference between the group means for the selected variables.