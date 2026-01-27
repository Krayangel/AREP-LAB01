# Linear Regression Lab

This repository contains two Jupyter notebooks implementing validation of linear regression models using NumPy and Matplotlib.

## Files

1.  **`01_part1_linreg_1feature.ipynb`**:
    *   Models stellar luminosity ($L$) as a function of stellar mass ($M$).
    *   Implements simple linear regression: $L = wM + b$.
    *   Includes gradient descent (loop and vectorized), cost surface visualization, and learning rate experiments.

2.  **`02_part2_polyreg.ipynb`**:
    *   Models stellar luminosity ($L$) using two features: stellar mass ($M$) and temperature ($T$).
    *   Implements polynomial feature engineering to capture nonlinearities and interactions: $X = [M, T, M^2, MT]$.
    *   Compares models with different feature sets and analyzes interaction effects.

## Requirements

*   Python 3.x
*   Jupyter Notebook
*   NumPy
*   Matplotlib


