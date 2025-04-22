# Sleep-Efficiency

## Sleep Efficiency Prediction using Linear Regression

This project analyzes and predicts sleep-related metrics using linear regression. It involves cleaning, transforming, and modeling data to identify the key factors affecting sleep efficiency.

---

### Dataset

The dataset used includes features like:

- Sleep duration
- Deep sleep percentage
- Caffeine consumption
- Alcohol consumption
- Awakenings
- Exercise frequency
- Sleep efficiency (target)

---

### Libraries Used

- **Python**
- **NumPy, Pandas** — Data handling
- **Seaborn, Matplotlib** — Data visualization
- **scikit-learn** — Preprocessing and linear regression modeling
- **Joblib** — Model persistence

---

### Data Preprocessing

- Removed duplicate rows  
- Imputed missing values with column means  
- Applied `log(x + 1)` transformation to skewed features:
  - Sleep duration
  - Deep sleep percentage
  - Caffeine consumption
- Standardized features using `StandardScaler` to normalize scales

---

### Exploratory Data Analysis

Explored relationships between variables using correlation matrices, scatter plots, and distribution plots to inform feature selection and transformation.

---

### Model: Linear Regression

Used **Linear Regression** to predict sleep efficiency based on the cleaned and transformed dataset.

#### Model Evaluation Metrics:
```python
Mean Squared Error (MSE): 0.004
Root Mean Squared Error (RMSE): 0.06
R-squared (R²): 0.75
```

### Summary

This project shows that linear regression can provide meaningful insights into how lifestyle factors (like caffeine consumption, exercise, and sleep duration) impact sleep efficiency. The model's evaluation metrics suggest its potential for further improvement with more complex models or feature engineering.

---

### Author

Helaena Lianne Saldana 
Data Science Student @ Ateneo de Davao University
