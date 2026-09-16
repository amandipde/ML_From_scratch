# Linear Regression from Scratch

A simple implementation of **Linear Regression from scratch using NumPy**, and comparison with `sklearn`.

## What is included

- Simple Linear Regression
- Multiple Linear Regression
- Least Squares / Normal Equation
- Model prediction
- MSE and R² evaluation
- 3D visualization of the regression surface

### Simple Linear Regression
 
The model parameters are obtained using the least-squre Equation: 
$$ 
b_1 = \frac{cov(x,y)} {var(x)} = \frac{\sum (x_i-\bar{x})(y_i-\bar{y})} {\sum (x_i-\bar{x})^2} \\ 
b_0 = \bar{y} -\frac{cov(x,y)} {var(x)}\bar{x} = \bar{y} - b_1 \bar{x}
$$
The implementation is demonstrated using Synthetic dataset 

### Multiple Linear Regression

The model parameters are obtained using the Normal Equation:

$$
\beta = (X^T X)^{-1}X^T y
$$

The implementation is demonstrated using the **Diabetes dataset** from scikit-learn.

## File

`Linear_regression.ipynb` — complete implementation and visualization.

