# Residual Analysis

## Residual Calculation

Residuals were calculated using:

Residual = Actual Monthly Sales − Predicted Monthly Sales

Positive residuals indicate stores that performed better than predicted by the model.

Negative residuals indicate stores that performed worse than predicted by the model.

---

## Top 5 Positive Residuals

| Store ID | Actual Sales | Predicted Sales | Residual |
|-----------|-----------:|-----------:|-----------:|
| STR-1058 | 870,937.40 | 760,075.49 | 110,861.91 |
| STR-1028 | 713,611.16 | 610,629.64 | 102,981.52 |
| STR-1073 | 813,316.71 | 721,364.21 | 91,952.50 |
| STR-1051 | 787,715.51 | 701,353.45 | 86,362.06 |
| STR-1026 | 625,514.04 | 540,349.06 | 85,164.98 |

### Business Interpretation

These stores significantly outperformed model expectations. This may indicate the presence of additional success factors not captured in the regression model, such as superior local management, stronger brand reputation, favorable market conditions, or special promotional activities.

---

## Top 5 Negative Residuals

| Store ID | Actual Sales | Predicted Sales | Residual |
|-----------|-----------:|-----------:|-----------:|
| STR-1023 | 627,171.90 | 763,946.84 | -136,774.94 |
| STR-1017 | 685,379.08 | 805,585.07 | -120,205.99 |
| STR-1012 | 595,467.60 | 709,793.87 | -114,326.27 |
| STR-1007 | 800,451.94 | 912,101.78 | -111,649.84 |
| STR-1060 | 721,079.35 | 808,079.69 | -87,000.34 |

### Business Interpretation

These stores underperformed relative to model expectations. Possible explanations include local competition, operational challenges, staffing issues, customer experience problems, or external market conditions not included in the dataset.

---

## Model Performance Assessment

The residual analysis shows that the model performs reasonably well for most stores, but certain locations exhibit larger prediction errors.

The existence of both positive and negative residuals suggests that the model does not consistently over-predict or under-predict across all stores.

---

## Potential Model Limitations

Some factors that may influence monthly sales but are not included in the model include:

- Local economic conditions
- Competitor promotions
- Store manager effectiveness
- Brand reputation
- Seasonal local events
- Customer demographics

These omitted variables may explain the larger residuals observed for certain stores.

---

## Conclusion

The residual analysis supports the use of the Multiple Regression Model as the final model. While prediction errors exist for some stores, the model demonstrates strong explanatory power and does not show evidence of systematic over-prediction or under-prediction across the dataset.

