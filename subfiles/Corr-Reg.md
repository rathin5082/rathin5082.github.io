---
layout: post2
title: Correlation and Regression
subtitle: 
categories: Supervised Learning
---

- ## Covariance and Pearson Correlation
    -  I explored the relationship between different variables and found that as data points varied, the correlation coefficient            changed significantly, reflecting the strength of their relationship. Covariance provided insight into if the variables              tended to rise and fall together. However, it did lack a consistent measure of strength. Pearson Correlation was useful for          determining both the direction and the intensity of association by normalising the relationship between -1 and 1. Correlation        coefficient was greatly affected by the addition of outliers or by altering the distribution of data points. This emphasised         how sensitive Pearson correlation is to the variability and outliers in the dataset.

<img src="https://rathin5082.github.io/assets/images/banners/Covariance.jpg" width="300"/>
 
      
- ## Linear Regression
    -  Through Linear Regression, I discovered that it was possible to model the link between a response variable and a single              predictor variable. The regression line's slope altered when I changed the data points, showing that the dependent variable          was changing at a different rate than the independent variable. The residual plots showed how departures from the line               impacted the model's accuracy, demonstrating that while linear regression presumes a linear relationship, large deviations           can result in inaccurate predictions. The exercise demonstrated how crucial it is to evaluate residual patterns in order to          confirm that a linear model is adequate.

<img src="https://rathin5082.github.io/assets/images/banners/Regression.jpg" width="300"/> 
      
- ## Multiple Linear Regression
    - The multiple linear regression exercise allowed me to see how introducing additional independent variables impacted the              model’s performance. By observing changes in R-squared and adjusted R-squared values, I noticed how some variables contributed       significantly to improving the model’s predictive accuracy, while others did not. Adjusting the coefficients and seeing their        effect on predictions provided insights into the relative importance of each variable. I also learned that adding more               variables can increase the model’s complexity but does not always result in a better fit, especially if some predictors are          not meaningful.

    
- ## Polynomial Regression
    - Investigating polynomial regression showed how adding polynomial terms could improve the representation of non-linear                interactions. I saw that the model suited the data more closely as I changed the degree of the polynomial, particularly in           cases where the connection between the variables was non-linear. Higher-degree polynomials, however, have the potential to           cause overfitting, which would capture noise instead of the underlying trend, therefore this flexibility came at a cost. The         exercise demonstrated how crucial it is to select the right polynomial degree in order to strike a compromise between                generalisation and model correctness.

 <img src="https://rathin5082.github.io/assets/images/banners/poly.jpg" width="300"/> 

 # Learning Outcomes
