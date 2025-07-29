# ✈️ Flight Price Prediction

This project applies machine learning techniques to predict flight ticket prices based on various features like duration, stops, departure time, class, airline, and more. The dataset is part of the **MLP | Term-2 | 2025 Kaggle Assignment-1**.

---

## 🔍 Objective

Build, evaluate, and tune multiple regression models to estimate flight prices accurately and efficiently.

---

## 📁 Dataset

The dataset contains 40000 rows and 12 columns. It includes both categorical and numerical features related to flights.

---

## 🧰 Technologies Used

- Python 🐍
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- XGBoost, LightGBM
- Kaggle (Notebook Environment)

---

## 🧪 Models Trained

1. Linear Regression
2. SGD Regressor
3. K-Nearest Neighbors (KNN)
4. Random Forest Regressor
5. Gradient Boosting Regressor
6. Extra Trees Regressor
7. XGBoost Regressor
8. LightGBM Regressor

---

## 🧼 Preprocessing Steps

- **Missing Values**: Imputed using appropriate strategies (`median`, `most_frequent`)
- **Categorical Encoding**:
  - One-Hot Encoding (e.g. `source`, `destination`)
  - Ordinal Encoding (e.g. `class`, `stops`, `arrival`, `departure`)
  - Frequency Encoding (for high-cardinality `flight`)
- **Outlier Handling**: Capped using IQR method
- **Scaling**: StandardScaler used for scale-sensitive models

---

## 🧪 Model Evaluation

Metrics used:
- ✅ R² Score
- 📉 RMSE
- 📊 MAE

Best model selected based on validation R² Score and retrained on full training + validation set.

---

## ✅ Final Submission

The top-performing model (e.g., LightGBM / XGBoost / Random Forest) was used to make predictions on the test set, and results were exported as `submission.csv`.

---

## 📈 Results

| Model              | R² Score |  RMSE   |  MAE    |
|--------------------|----------|---------|---------|
| XGBoost            |   0.98   | 3186.31 | 1708.51 |

---

