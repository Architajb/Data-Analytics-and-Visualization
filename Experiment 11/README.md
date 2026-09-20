# Hypothesis Testing Using Z-Test on UCI Diabetes Dataset

## Aim
To determine whether the mean Glucose level in the UCI Diabetes dataset significantly differs from a population mean of 100.

## Software Requirements
- Python 3.13.2
- Jupyter Notebook 7.3.2

## Libraries Used
- Pandas
- NumPy
- Statsmodels

## Theory
A Z-Test is a statistical hypothesis test used to determine whether a sample mean significantly differs from a known population mean.

### Hypotheses
- Null Hypothesis (H₀): Mean Glucose = 100
- Alternative Hypothesis (H₁): Mean Glucose ≠ 100

### Decision Rule
- p-value < 0.05 → Reject H₀
- p-value ≥ 0.05 → Fail to Reject H₀

## Procedure

1. Import required libraries.
2. Load the UCI Diabetes dataset.
3. Select the Glucose column.
4. Perform a one-sample Z-Test.
5. Compare the p-value with the significance level.
6. Draw conclusions based on the result.

