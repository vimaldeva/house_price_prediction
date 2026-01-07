# 🏠 House Price Prediction

Predict house sale prices using a mix of machine learning models—including an Artificial Neural Network (ANN), Random Forest, and others—and compare performance across RMSE, MAE, MSE, and R². This project walks through data exploration, feature engineering, model training, evaluation, and visualization.

---

## ⚙️ Project Highlights

- **Multiple Models:** Benchmark ANN against tree-based and linear models.
- **Metric Tracking:** Automatically log RMSE, MAE, MSE, and R² to CSV for later comparison and plotting.
- **Visualization Suite:** Plot training history, residuals, prediction vs actuals, and metric comparisons.

---

## 📁 Repository Structure

```text
.
├── dataset/
│   ├── data.csv              # Original dataset(s)
├── notebooks/                # Exploratory notebooks (EDA, experiments)
├── src/
│   ├── house_price_prediction.ipynb
├── metrics/
│   ├── model_metrics.csv     # Aggregated metrics for all models
│   └── metrics_visualization/
├── visualizations/                    # Saved plots (metrics, comparisons, etc.)
├── requirements.txt
└── README.md
