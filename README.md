# Diamonds ML Project

A data analysis and machine learning project focused on bulding regression model to predict diamond prices.

## dataset overview
The dataset contains 10 attributes of almost 54000 diamonds.
-**price:** price in US dollars (numeric)
-**carat:** weight of the diamond (numeric)
-**cut:** quality of the cut (categorical)
-**color:** diamond color (categorical)
-**clarity:** diamond clarity (categorical)
-**depth** total depth percentage (numeric)
-**table:** width of top of diamond relative widest point (numeric)
-**x,y,z:** length, width, depth in mm (numeric)

## table of content
- EDA
- Preprocessing
- ML models
- Performance comparison
- Visualizations and results

## results
| Model             | R² Score | MAE | RMSE |
|-------------------|----------|-----|------|
| Linear Regression |  0.915   | 802 | 1160 |
| Decision Tree     |  0.976   | 319 | 619  |
| XGBoost           |  0.980   | 279 | 559  |

## project structure
- `figures/` – plots and visualizations
- `results` – performance metrics
- `Diamonds_analysis.ipynb` – project notebook
