# Olympics-linear-regression

# Linear Regression with Olympic Data – ECON5129

This project applies linear regression using the **normal equation** to model Olympic race times over the years. It also includes a theoretical derivation of a key matrix expression, showcasing both analytical and computational skills.

---

## Assignment Prompt

- [Task5.pdf](./Task5.pdf)

---

## Project Overview

> This project demonstrates linear regression from both a theoretical and applied perspective. It begins with a matrix algebra derivation of the quadratic form \( \mathbf{w}^\top \mathbf{X}^\top \mathbf{X} \mathbf{w} \), and continues with a Python implementation of linear regression using the normal equation to model Olympic winning times as a function of year.

### ✅ Question 1 – Matrix Derivation
- Expanded the quadratic form \( \mathbf{w}^\top \mathbf{X}^\top \mathbf{X} \mathbf{w} \) using matrix multiplication
- Expressed it as:
  \[
  w_0^2 \sum x_{i1}^2 + 2w_0w_1 \sum x_{i1}x_{i2} + w_1^2 \sum x_{i2}^2
  \]
- Demonstrated this step-by-step using Python and LaTeX formatting

### ✅ Question 2 – Linear Regression on Olympic Data
- Loaded Olympic year and race time data
- Implemented linear regression using the **normal equation**:
  \[
  \mathbf{w} = (\mathbf{X}^\top \mathbf{X})^{-1} \mathbf{X}^\top \mathbf{t}
  \]
- Computed coefficients \( w_0 \) and \( w_1 \)
- Plotted the regression line over the Olympic data

---

## Contents

- [Taskq5.ipynb](./Taskq5.ipynb) – Matrix derivation + Olympic regression implementation  


## Tools Used

- Python 3  
- `numpy`, `matplotlib`

---

## 📚 Background

This project was developed during my graduate studies in Data Analytics at the **University of Glasgow**.

---

## Author

Ditep Nantap Rejoice
🔗 [LinkedIn Profile](https://www.linkedin.com/in/nantap-ditep-00490b231)
