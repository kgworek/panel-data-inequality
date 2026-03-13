# Panel Data Analysis of Income Inequality

This project analyzes the relationship between income inequality and selected macroeconomic variables using panel data econometric models.

The analysis includes variables such as inflation, GDP growth, government expenditure, and globalization. The goal is to examine how these factors are associated with changes in the Gini coefficient across countries and over time.

## Methods

The following econometric models were estimated:

* Pooled OLS
* Random Effects
* Fixed Effects

Model selection was based on the **Breusch–Pagan test** and the **Hausman test**.
Due to the presence of serial correlation detected by the **Wooldridge test**, the final model uses **robust standard errors**.

## Results

The preferred specification is the **fixed effects model with robust standard errors**.
The results suggest that GDP growth, government expenditure, and globalization are negatively associated with income inequality, while inflation shows a nonlinear relationship with inequality.

## Files

* `panel_income_inequality_analysis.Rmd` – analysis code and report
* `panel_income_inequality_analysis.html` – rendered report
