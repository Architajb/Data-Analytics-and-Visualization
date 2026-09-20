# Independent T-Test on UCI and Pima Indians Diabetes Datasets

## Aim

To compare the means of selected numerical attributes from the UCI Diabetes and Pima Indians Diabetes datasets using an Independent T-Test.

## Software Requirements

- Python 3.13.2
- Jupyter Notebook 7.3.2

## Libraries Used

- Pandas
- NumPy
- SciPy

## Theory

The Independent T-Test is used to compare the means of two independent groups and determine whether statistically significant differences exist between them.

### Features Compared

- Glucose
- BloodPressure
- BMI

### Decision Rule

- p-value < 0.05 → Significant Difference
- p-value ≥ 0.05 → No Significant Difference

## Procedure

1. Import the required libraries.
2. Load the UCI Diabetes and Pima Indians Diabetes datasets.
3. Select numerical columns for comparison.
4. Perform an Independent T-Test.
5. Analyze the p-values.
6. Determine statistical significance.

## Result

The obtained p-values are greater than 0.05 for Glucose, Blood Pressure, and BMI. Therefore, there is no statistically significant difference between the UCI Diabetes and Pima Indians Diabetes datasets for the selected attributes.