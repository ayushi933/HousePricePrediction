# 🏡 House Price Prediction - Advanced Regression Project

Welcome to my beginner-friendly but professionally structured project on predicting house prices using regression techniques. This project was built as part of a data science learning journey and covers the full data preprocessing, feature engineering, modeling, and evaluation pipeline.

---

## 📂 Dataset
This project uses the popular [Kaggle House Prices - Advanced Regression Techniques](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques/data) dataset.

### Files Used:
- `train.csv`: Training data
- `test.csv`: Test data
- `sample_submission.csv`: Submission template
- `data_description.txt`: Feature documentation
- `house_price_prediction.ipynb`: Jupyter notebook with complete workflow

---

## 🛠️ Technologies Used

| Tool | Purpose |
|------|---------|
| **Python** | Programming Language |
| **Pandas, NumPy** | Data manipulation |
| **Matplotlib, Seaborn** | Data visualization |
| **Scikit-learn** | Modeling and evaluation |
| **VS Code + Jupyter Extension** | Development environment |

---

## 🧼 Features Covered

✅ Initial Data Exploration  
✅ Target Variable Analysis (Histograms, Boxplot, Scatter)  
✅ Handling Missing Values (Group-based and Mode Imputation)  
✅ Feature Engineering:
- Total Square Footage
- Total Bathrooms
- Age of House, Garage, Remodel
- Binary flags for pool, basement, fireplace, garage

✅ Categorical Encoding (`LabelEncoder`)  
✅ Feature Scaling (`StandardScaler`)  
✅ Feature Importance with Random Forest  
✅ Correlation Heatmap  
✅ Model Training + Validation  
✅ Residual & Prediction Visualization  
✅ Final Submission File (`submission.csv`)

---

## 📊 Model Performance

| Metric | Value |
|--------|-------|
| **Model** | RandomForestRegressor |
| **RMSE** | _Add your final value here_ |
| **R² Score** | _Optional_ |

---

## 📈 Top Features (by Importance)

_Example:_
- OverallQual  
- TotalSF  
- TotalBath  
- GarageCars  
- YearBuilt  

> _Derived from RandomForest feature importances and correlation matrix._

---

## 📦 Output

- `submission.csv`: Final output file ready for Kaggle submission
- `house_price_prediction.ipynb`: Clean and commented
