# Part 3: Regression-Based Business Insights & Model Interpretation

## Business Problem Summary

This project analyzes the factors that influence monthly sales performance across retail stores using regression analysis. The goal is to identify the variables most strongly associated with sales and provide data-driven recommendations for business decision-making.

The leadership team is interested in understanding whether factors such as marketing spend, footfall, inventory availability, customer ratings, discounts, store type, and region impact monthly sales performance.

---

## Dataset Description

**Dataset File:** `data/business_regression_data.xlsx`

The dataset contains retail store-level information including sales performance, marketing activities, operational metrics, customer experience indicators, and store characteristics.

### Dependent Variable

- `monthly_sales`

### Independent Variables

#### Numerical Variables
- marketing_spend
- footfall
- avg_discount_pct
- inventory_availability_pct
- customer_rating
- staff_count

#### Categorical Variables
- region
- store_type

---

## Data Preparation

The following data preparation activities were completed:

- Reviewed the dataset structure
- Preserved the original dataset
- Verified data quality
- Prepared a cleaned dataset for regression analysis
- Created dummy variables for categorical features
- Prepared prediction and residual calculations

---

## Dummy Variable Approach

Dummy variables were created for categorical variables including:

- region
- store_type

One category was excluded and used as the reference category to avoid multicollinearity (dummy variable trap).

Example:

Reference Category:
- Rural Store

Dummy Variables:
- Urban Store
- Suburban Store

The coefficients for the dummy variables represent the expected difference in monthly sales relative to the reference category.

---

## Regression Approach

### Simple Regression Models

Two simple linear regression models were developed using:

**Dependent Variable**
- monthly_sales

**Independent Variables**
- marketing_spend
- footfall

Each model was evaluated using:

- Regression equation
- Coefficient values
- R-squared
- P-values
- Business interpretation

---

### Multiple Regression Model

A multiple regression model was developed using:

**Dependent Variable**
- monthly_sales

**Independent Variables**
- marketing_spend
- footfall
- inventory_availability_pct
- Dummy variables for store_type and/or region

The model was evaluated using:

- Coefficient interpretation
- P-values
- R-squared
- Business relevance
- Predictive performance

---

## Model Comparison Summary

The simple regression models provided insight into individual business drivers but explained only part of the variation in sales.

The multiple regression model showed stronger explanatory power because it incorporated multiple operational and marketing variables simultaneously.

Comparison criteria included:

- Model variables
- R-squared
- Significant predictors
- Business usefulness
- Limitations

Detailed comparison is documented in:

`analysis/model_comparison.md`

---

## Final Model Selected

The multiple regression model was selected as the final model because:

- It produced the highest explanatory power.
- It included multiple important business drivers.
- It provided stronger predictive performance.
- It offered more actionable business insights.

---

## Residual Analysis Summary

Residual analysis was performed using:

Residual = Actual Sales − Predicted Sales

The analysis identified:

- Largest positive residuals
- Largest negative residuals
- Potential under-predicted stores
- Potential over-predicted stores

Results are documented in:

`analysis/residual_analysis.md`

---

## Business Recommendation

The analysis indicates that variables such as:

- Marketing Spend
- Footfall
- Inventory Availability

appear to have the strongest association with monthly sales performance.

Recommended business actions include:

1. Increase focus on high-performing marketing activities.
2. Improve inventory availability across stores.
3. Implement strategies that increase customer footfall.
4. Monitor differences in performance across store types and regions.

Regression analysis identifies statistical relationships but does not automatically prove causation. Business decisions should therefore combine statistical findings with operational expertise.

---

## Assumptions and Limitations

### Assumptions

- Linear relationships exist between predictors and sales.
- Data is accurate and representative.
- Variables are measured consistently.

### Limitations

- Regression shows association rather than causation.
- External factors may not be included in the dataset.
- Results depend on data quality and model specification.
- Future business conditions may differ from historical data.

---

## Screenshots Included

The repository contains the following screenshots:

- `screenshots/simple_regression_output.png`
- `screenshots/multiple_regression_output.png`
- `screenshots/model_comparison_preview.png`
- `screenshots/residuals_preview.png`

These screenshots provide evidence of regression execution, model comparison, and residual analysis.

---

## Repository Structure

part3_regression_insights/

├── data/
│ └── business_regression_data.xlsx

├── analysis/
│ ├── regression_workbook.xlsx
│ ├── model_comparison.md
│ └── residual_analysis.md

├── outputs/
│ ├── regression_summary.xlsx
│ ├── final_recommendation.md
│ └── model_equations.md

├── screenshots/
│ ├── simple_regression_output.png
│ ├── multiple_regression_output.png
│ ├── residuals_preview.png
│ └── model_comparison_preview.png

└── README.md
