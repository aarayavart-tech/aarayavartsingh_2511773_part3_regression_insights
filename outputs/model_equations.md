# Model Equations

## Introduction

Regression analysis was conducted to identify the factors associated with monthly sales performance across retail stores.

Both simple regression and multiple regression models were developed.

The equations below summarize the models used in this analysis.

---

# Simple Regression Model 1

## Monthly Sales vs Marketing Spend

### Equation

Monthly Sales = β0 + β1(Marketing Spend)

### Interpretation

* β0 represents the intercept.
* β1 represents the expected change in monthly sales for each additional unit of marketing spend.

### Business Meaning

A positive coefficient indicates that higher marketing investment is associated with higher monthly sales.

### Model Assessment

* Useful for understanding marketing effectiveness.
* Limited because it considers only one factor.

---

# Simple Regression Model 2

## Monthly Sales vs Footfall

### Equation

Monthly Sales = β0 + β1(Footfall)

### Interpretation

* β0 represents baseline sales.
* β1 represents the increase in sales associated with additional customer visits.

### Business Meaning

Stores with higher customer traffic generally achieve higher monthly sales.

### Model Assessment

* Stronger explanatory power than marketing spend alone.
* Highlights the importance of attracting customers into stores.

---

# Multiple Regression Model

## Final Model Equation

Monthly Sales = β0 + β1(Marketing Spend) + β2(Footfall) + β3(Inventory Availability %) + β4(Mall Dummy) + β5(High Street Dummy) + β6(Residential Dummy)

---

## Coefficient Interpretation

### Intercept (β0)

Represents expected monthly sales for the reference category when all predictor values are zero.

---

### Marketing Spend Coefficient (β1)

Measures the expected increase in monthly sales associated with additional marketing investment while holding other variables constant.

---

### Footfall Coefficient (β2)

Measures the expected increase in monthly sales associated with additional customer visits.

---

### Inventory Availability Coefficient (β3)

Measures the impact of inventory availability on monthly sales.

Higher inventory availability is generally associated with higher sales performance.

---

### Store Type Dummy Coefficients (β4, β5, β6)

Measure the difference in sales relative to the reference store type category.

Positive values indicate higher sales compared with the reference category.

Negative values indicate lower sales compared with the reference category.

---

# Dummy Variable Approach

## Categorical Variable Selected

Store Type

Categories:

* Airport
* Mall
* High Street
* Residential

---

## Reference Category

Airport

The Airport category was excluded from the regression model and used as the reference category.

This approach prevents multicollinearity and avoids the dummy variable trap.

---

## Dummy Variables Created

### Mall Dummy

Mall = 1

Other Store Types = 0

---

### High Street Dummy

High Street = 1

Other Store Types = 0

---

### Residential Dummy

Residential = 1

Other Store Types = 0

---

# Final Model Selection

## Selected Model

Multiple Regression Model

---

## Reason for Selection

The multiple regression model was selected because:

* Highest R-Squared value
* Includes multiple business drivers
* Better predictive performance
* Stronger business relevance
* More useful for management decision-making

---

# Business Conclusion

The analysis indicates that monthly sales are most strongly associated with:

1. Footfall
2. Marketing Spend
3. Inventory Availability

These variables should receive the greatest management attention when planning future business initiatives.
