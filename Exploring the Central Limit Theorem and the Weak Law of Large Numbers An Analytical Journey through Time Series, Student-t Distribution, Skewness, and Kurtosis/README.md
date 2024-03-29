## Exploring the Central Limit Theorem and the Weak Law of Large Numbers: An Analytical Journey through Time Series, Student-t Distribution, Skewness, and Kurtosis

This directory is dedicated to an in-depth exploration of significant statistical concepts, including the Central Limit Theorem (CLT) and the Weak Law of Large Numbers, through practical examples and data analysis. Using Python and its powerful libraries, I analyze time series data, delve into the properties of the Student-t distribution, and examine metrics such as skewness and kurtosis to gain insights into data distribution characteristics.

### Installing necessary libraries 
To run the notebook and replicate the findings, ensure you have the following Python packages installed:
```bash
pip install numpy
pip install matplotlib
pip install scipy
pip install statsmodels
pip install pandas_datareader
```

### Analysis Overview
My journey through this analytical exploration includes:

**Question 1**: Application of the Central Limit Theorem to approximate distributions.

**Question 2**: Downloading and analyzing the Dow Jones Industrial Average to explore time series behaviors.

### Key Findings
- I investigated how the CLT can be used to approximate distributions that don't have a closed-form expression.
- Through plotting and analysis, I explored how the weak Law of Large Numbers manifests in financial time series data.
- I computed and interpreted key statistical measures such as sample mean, variance, skewness, and kurtosis to suggest appropriate models for daily returns.
- By employing the Maximum Likelihood Estimator approach and comparing it with scipy's fit function, I aim to find the best parameters that explain our data.
- My analysis is visualized through histograms, QQ plots, and time series plots to provide clear and intuitive insights into the concepts discussed.
