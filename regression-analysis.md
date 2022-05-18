# PE 1 - Applied Statistics & Time Series Analysis

## Regression Analysis
---
### **METHOD OF LEAST SQUARES**
```
This method can be usdd to determine the line of best fit in cases where data points do not fall on the straight line.

It determines the line of best fit for given observed data by minimizing the sum of the squares of the vertical deviations from each data point to the line.
```

1. **METHOD OF LEAST SQUARES**

$Sum Of Residuals = \sum_{i=1}^{n} (y_i-\hat{y_i}) = 0$

$Sum Of Squares Of Residuals = E(a,b) = \sum_{i=1}^{n} (y_i-\hat{y_i})^2 = Least$

2. **FITTING OF SIMPLE LINEAR REGRESSION**

$E(a,b) = \sum_{i=1}^{n} (y_i-\hat{y_i})^2 = \sum_{i=1}^{n} (y_i-a-bx_i)^2$

<small>where a & b are</small> 

$\hat{a} = \bar{y} - \hat{\bar{b}}\bar{x}$ 

$\hat{b} = \frac{covariance(X,Y)}{variance(X)}$

3. **NORMAL EQUATIONS**

EQ 1 : $na + b\sum_{i=1}^{n}x_i = \sum_{i=1}^{n}y_i$

EQ 2 :  $a\sum_{i=1}^{n}x_i + b\sum_{i=1}^{n} {x_i}^2 = \sum_{i=1}^{n}x_i y_i$

4. **PEARSON'S COEFFICIENT OF SIMPLE CORRELATION BETWEEN X & Y**

$\hat{b} = r_{xy}\frac{SD(Y)}{SD(X)}$

---





