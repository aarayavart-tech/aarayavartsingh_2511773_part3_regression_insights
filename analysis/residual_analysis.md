# Residual Analysis

## Introduction

Residual analysis was performed using the selected multiple regression model to evaluate prediction accuracy and identify observations where actual sales differed significantly from predicted sales.

Residuals were calculated using the following formula:

Residual = Actual Monthly Sales − Predicted Monthly Sales

A positive residual indicates that actual sales were higher than predicted sales.

A negative residual indicates that actual sales were lower than predicted sales.

---

## Predicted Sales and Residual Calculation

Predicted sales values were calculated using the final multiple regression equation.

Residuals were then computed for each store record.

These calculations were recorded in the Predictions_Residuals sheet of the regression workbook.

---

## Largest Positive Residuals

The following records showed the largest positive residuals:

| Record Type | Interpretation                           |
| ----------- | ---------------------------------------- |
| Store A     | Actual sales exceeded model expectations |
| Store B     | Stronger performance than predicted      |
| Store C     | Possible local demand advantage          |
| Store D     | Effective store management               |
| Store E     | Exceptional promotional impact           |

### Business Interpretation

Large positive residuals indicate stores that performed significantly better than expected based on the model variables.

Possible reasons include:

* Successful local promotions
* Strong store management
* Seasonal demand spikes
* Customer loyalty
* Local market advantages

These factors are not fully captured by the regression model.

---

## Largest Negative Residuals

The following records showed the largest negative residuals:

| Record Type | Interpretation              |
| ----------- | --------------------------- |
| Store F     | Sales below expectation     |
| Store G     | Lower demand than predicted |
| Store H     | Possible inventory issues   |
| Store I     | Local competition effects   |
| Store J     | Operational challenges      |

### Business Interpretation

Large negative residuals indicate stores that performed worse than expected.

Possible reasons include:

* Stock shortages
* Local competition
* Staffing problems
* Poor customer experience
* Temporary disruptions

These factors may not be included in the current model.

---

## Model Performance Assessment

The residual distribution suggests that the model performs reasonably well for most observations.

Most residuals remain within an acceptable range, indicating that the model captures the major drivers of monthly sales.

However, some stores continue to exhibit unusually large residual values.

---

## Under-Prediction and Over-Prediction

### Under-Predicted Stores

Stores with positive residuals generated higher sales than expected.

This suggests the model may not fully capture:

* Local demand conditions
* Promotional effectiveness
* Store-level management quality

### Over-Predicted Stores

Stores with negative residuals generated lower sales than expected.

This suggests the model may not fully capture:

* Competitive pressures
* Inventory disruptions
* Operational inefficiencies

---

## Limitations

Residual analysis indicates that additional variables may improve model accuracy.

Potential future variables include:

* Customer demographics
* Local economic conditions
* Competitor activity
* Promotional campaign effectiveness
* Store manager performance

---

## Conclusion

Residual analysis confirms that the multiple regression model provides useful business insights while also highlighting areas where additional explanatory variables may improve forecasting performance.

The model explains a substantial portion of monthly sales variation, but some store-specific factors remain unobserved and contribute to prediction errors.
