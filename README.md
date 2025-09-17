# Probability and Statistics Project

This project involves statistical analysis, hypothesis testing, investment optimization, and data modeling using datasets on cryptocurrency trading and student performance. The main focus is on maximizing investment profit, minimizing risk, exploring relationships among variables, and applying both classical and Bayesian inference methods.

## Key Features

- Investment portfolio optimization with cryptocurrency data.
- Statistical hypothesis testing and confidence interval estimation for student grades.
- Bootstrapping for confidence intervals and hypothesis testing.
- Likelihood estimation and distribution fitting for absenteeism data.
- Dependency testing and correlation analysis.
- Simple linear regression modeling.
- Bayesian simulation for educational outcome estimation.
- Empirical validation of Chi-squared test distribution.

## Getting Started

Clone the project

```bash
git clone https://github.com/vesalbargi/probability-statistics.git
```

Create a Python virtual environment

```bash
python -m venv .venv
```

Activate the virtual environment
- On Windows:
  ```bash
  .venv\Scripts\activate
  ```
- On macOS/Linux:
  ```bash
  source .venv/bin/activate
  ```

Install required packages
```bash
pip install matplotlib numpy pandas seaborn scipy
```

Launch Jupyter Notebook and open the project
```bash
jupyter notebook final_project.ipynb
```

## Dataset Description

- `two_currencies.csv`: Daily profit/loss of two cryptocurrencies over 20 days, used for investment optimization.

- `student_performance.csv`: Student attributes and grades, used for statistical analysis and modeling.

## License

This project is licensed under the MIT License.

[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](https://choosealicense.com/licenses/mit/)