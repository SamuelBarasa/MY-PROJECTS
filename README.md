# 🏠 House Price Prediction - Ames Housing Dataset

## 📌 Project Objective

To predict house sale prices using machine learning models based on various housing features from the Ames, Iowa dataset. The goal is to evaluate the performance of linear and decision tree regression models.

---

## 📂 Dataset Source

- **Name:** Ames Housing Dataset
- **Source:** [Kaggle - Ames Housing](https://www.kaggle.com/c/house-prices-advanced-regression-techniques/data)

---

## 🧰 Libraries Used

- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `scikit-learn`
- `jupyter` / `notebook`
- `joblib` (optional for saving models)

Install them via:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn notebook

git clone https://github.com/yourusername/house-price-prediction.git
cd house-price-prediction
jupyter notebook
📈 Summary of Findings
Models Trained:
Linear Regression

Decision Tree Regressor

Evaluation Metrics:
Model	RMSE	R² Score
Linear Regression	29152.88	0.89
Decision Tree	35521.86	 0.84



Observations:
OverallQual, GrLivArea, and GarageCars were the most strongly correlated with SalePrice.

Linear regression performed well overall, but slightly under-predicts high-end prices.

Decision Tree offered more flexibility but risked overfitting without pruning.
