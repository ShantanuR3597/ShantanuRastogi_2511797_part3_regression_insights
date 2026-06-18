# Model Comparison

## Model 1: Marketing Spend Regression

### Model Details
- **Dependent Variable:** Monthly Sales
- **Independent Variable:** Marketing Spend
- **R²:** 0.167
- **Significant Variable:** Marketing Spend

### Business Usefulness
This model helps evaluate the relationship between marketing investment and monthly sales performance. It confirms that increased marketing spend is associated with higher sales.

### Limitations
The model explains only 16.7% of the variation in monthly sales and ignores operational, customer, and regional factors that may influence sales performance.

---

## Model 2: Footfall Regression

### Model Details
- **Dependent Variable:** Monthly Sales
- **Independent Variable:** Footfall
- **R²:** 0.736
- **Significant Variable:** Footfall

### Business Usefulness
This model demonstrates a strong relationship between customer traffic and monthly sales. Footfall appears to be a major driver of store performance.

### Limitations
The model does not account for inventory availability, staffing levels, customer experience, store characteristics, or regional differences.

---

## Model 3: Multiple Regression Model

### Model Details
- **Dependent Variable:** Monthly Sales
- **Independent Variables:**
  - Marketing Spend
  - Footfall
  - Average Discount Percentage
  - Staff Count
  - Inventory Availability Percentage
  - Competitor Distance
  - Holiday Flag
  - Customer Rating
  - Region Dummy Variables
  - Store Type Dummy Variables

- **R²:** 0.857
- **Adjusted R²:** 0.850
- **Significant Variables:** 11

### Business Usefulness
This model provides the most comprehensive understanding of monthly sales drivers. It evaluates multiple business factors simultaneously and identifies the variables most strongly associated with sales performance.

### Limitations
Regression analysis identifies associations between variables but does not prove causation. The model may also be affected by external factors that are not included in the dataset.

---

# Final Model Selection

## Selected Model
**Multiple Regression Model**

## Reason for Selection

The Multiple Regression Model was selected as the final model because it achieved the highest explanatory power with an R² value of **0.857**, indicating that it explains approximately **85.7%** of the variation in monthly sales.

Unlike the simple regression models, the multiple regression model considers operational, customer, regional, and store-level factors simultaneously. This provides a more realistic representation of business performance and supports stronger decision-making.

The model identified several statistically significant drivers of sales, including:

- Footfall
- Marketing Spend
- Inventory Availability
- Staff Count
- Customer Rating
- Holiday Periods
- Regional Differences
- Store Type Differences

Based on explanatory power, statistical significance, and business relevance, the Multiple Regression Model is the most suitable model for understanding monthly sales performance and guiding business strategy.

