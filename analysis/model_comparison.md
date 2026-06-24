# Model Comparison

## Overview

Three regression models were developed to identify the factors associated with monthly sales performance.

| Model               | Dependent Variable | Independent Variables                                                 | R-Squared | Business Usefulness |
| ------------------- | ------------------ | --------------------------------------------------------------------- | --------- | ------------------- |
| Simple Regression 1 | Monthly Sales      | Marketing Spend                                                       | 0.17      | Moderate            |
| Simple Regression 2 | Monthly Sales      | Footfall                                                              | 0.74      | High                |
| Multiple Regression | Monthly Sales      | Marketing Spend, Footfall, Inventory Availability, Store Type Dummies | 0.82      | Very High           |

---

## Model 1: Marketing Spend Regression

### Variables Used

Dependent Variable:

* Monthly Sales

Independent Variable:

* Marketing Spend

### Results

* Positive coefficient
* R² = 0.17
* Marketing spend shows a positive relationship with sales

### Business Interpretation

Stores that spend more on marketing generally achieve higher sales. However, marketing spend alone explains only a limited portion of sales variation.

### Limitations

* Does not consider customer traffic
* Ignores inventory and store characteristics
* Lower explanatory power

---

## Model 2: Footfall Regression

### Variables Used

Dependent Variable:

* Monthly Sales

Independent Variable:

* Footfall

### Results

* Strong positive coefficient
* R² = 0.74

### Business Interpretation

Customer traffic is strongly associated with monthly sales. Stores with higher footfall generally generate significantly higher revenue.

### Business Usefulness

This model is useful for understanding the importance of attracting customers into stores.

### Limitations

* Does not explain why footfall changes
* Ignores operational variables

---

## Model 3: Multiple Regression Model

### Variables Used

Dependent Variable:

* Monthly Sales

Independent Variables:

* Marketing Spend
* Footfall
* Inventory Availability Percentage
* Store Type Dummy Variables

### Results

* R² = 0.82
* Highest explanatory power among all models
* Most important variables remain statistically significant

### Business Interpretation

Monthly sales are influenced by multiple factors simultaneously. Footfall, marketing investment, and inventory availability all contribute positively to sales performance.

Store type also influences sales outcomes when compared with the reference category.

### Business Usefulness

This model provides the strongest support for business decision-making because it considers multiple operational drivers together.

### Limitations

* Based on historical data
* Does not include macroeconomic conditions
* Regression identifies association rather than causation

---

## Significant Variables

The variables that appear most useful for predicting monthly sales are:

1. Footfall
2. Marketing Spend
3. Inventory Availability

These variables consistently show positive relationships with sales performance.

---

## Final Model Selection

### Selected Model

Multiple Regression Model

### Reason for Selection

* Highest R-Squared value
* Includes multiple business drivers
* Better predictive performance
* More useful for leadership decision-making
* Supports resource allocation and operational planning

---

## Conclusion

The multiple regression model is recommended as the final model because it explains the largest proportion of sales variation and provides the most actionable business insights.
