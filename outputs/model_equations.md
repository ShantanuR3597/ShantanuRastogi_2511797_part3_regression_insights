# Model Equations

## Overview

Regression analysis was performed to identify the factors most strongly associated with Monthly Sales. Two simple regression models and one multiple regression model were evaluated.

---

# Simple Regression Model 1

## Equation

Monthly Sales = 560800 + (2.1296 × Marketing Spend)

## Interpretation

- Intercept (560,800): Expected monthly sales when marketing spend is zero.
- Marketing Spend Coefficient (2.1296): Every additional unit of marketing spend is associated with an increase of approximately 2.13 units in monthly sales.

## Model Performance

- R² = 0.167
- P-value < 0.001

## Business Meaning

Marketing spend has a statistically significant positive relationship with monthly sales. However, the model explains only 16.7% of the variation in sales, suggesting that additional factors influence store performance.

---

# Simple Regression Model 2

## Equation

Monthly Sales = 446400 + (35.678 × Footfall)

## Interpretation

- Intercept (446,400): Expected monthly sales when footfall is zero.
- Footfall Coefficient (35.678): Each additional customer entering the store is associated with approximately 35.68 additional units in monthly sales.

## Model Performance

- R² = 0.736
- P-value < 0.001

## Business Meaning

Footfall has a strong positive relationship with monthly sales and explains a large proportion of sales variation across stores.

---

# Multiple Regression Model

## Equation

Monthly Sales =

87030

+ (1.2075 × Marketing Spend)

+ (27.3759 × Footfall)

- (4.1710 × Average Discount Percentage)

+ (3483.41 × Staff Count)

+ (3060.20 × Inventory Availability Percentage)

- (3424.62 × Competitor Distance)

+ (151000 × Holiday Flag)

+ (12450 × Customer Rating)

+ (9934 × Region North)

+ (21040 × Region South)

+ (25260 × Region West)

- (24300 × Store Type High Street)

- (11800 × Store Type Mall)

- (44680 × Store Type Residential)

---

# Dummy Variable Approach

The categorical variables Region and Store Type were converted into dummy variables.

## Region

Reference Category: East

Dummy Variables Created:

- region_North
- region_South
- region_West

Interpretation:

The coefficients indicate the expected difference in monthly sales compared to stores located in the East region.

---

## Store Type

Reference Category: Outlet

Dummy Variables Created:

- store_type_High Street
- store_type_Mall
- store_type_Residential

Interpretation:

The coefficients indicate the expected difference in monthly sales compared to Outlet stores.

---

# Important Coefficients

The following variables were statistically significant:

- Marketing Spend
- Footfall
- Staff Count
- Inventory Availability Percentage
- Competitor Distance
- Holiday Flag
- Customer Rating
- Region South
- Region West
- Store Type High Street
- Store Type Residential

The following variables were not statistically significant:

- Average Discount Percentage
- Region North
- Store Type Mall

These variables should be interpreted cautiously because the model does not provide sufficient statistical evidence that they meaningfully influence monthly sales.

---

# Final Model Selected

## Multiple Regression Model

### Reason for Selection

The Multiple Regression Model was selected because:

- Highest R² value (0.857)
- Highest explanatory power
- Includes operational, customer, regional, and store-level factors
- Provides the most realistic representation of business performance
- Supports business decision-making more effectively than the simple regression models

The model explains approximately 85.7% of the variation in monthly sales and was selected as the final model for business recommendations.

