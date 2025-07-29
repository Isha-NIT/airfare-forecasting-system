# ✈️ Flight Price Prediction

A machine learning project to predict flight ticket prices based on various features such as airline, duration, class, departure time, etc.

---

## 🔍 Objective

To develop regression models that accurately predict flight prices using exploratory data analysis, preprocessing pipelines, and ensemble learning techniques.

---

## 📂 Project Structure

- **EDA & Cleaning**: Missing values, duplicates, outliers handled. Categorical and numerical features explored.
- **Preprocessing**: Feature engineering (e.g., frequency encoding for high-cardinality columns), custom pipelines for encoding, scaling, and imputation.
- **Modeling**: Trained and tuned 8 regression models including Random Forest, XGBoost, LightGBM, and Linear Regression.
- **Evaluation**: Assessed using R², RMSE, and MAE on validation and test sets.


---

## 🧰 Tech Stack

- **Languages**: Python
- **Libraries**: pandas, numpy, scikit-learn, XGBoost, LightGBM, matplotlib, seaborn, scipy
- **Tools**: Kaggle Notebooks, GitHub

---

## 📊 Key Highlights

- ✨ EDA revealed insightful trends: price vs. duration (positive), price vs. days_left (negative).
- 🔁 Applied log transformation to stabilize skewed price distribution.
- 🔧 Tuned hyperparameters using `RandomizedSearchCV` on ensemble models.
- 🛠️ Used column-wise transformers with Pipelines for clean and reproducible preprocessing.
- 🏆 Selected best model based on validation R² and retrained it on the full training set before testing.

---

## 📈 Final Results

| Model         | R² Score |   RMSE      |   MAE      |
|---------------|----------|-------------|------------|
| XGBoost       |   0.98   |  3186.31    |  1708.51   |

---

## 🧠 ML Models Used

- Linear Regression
- Stochastic Gradient Descent (SGD)
- K-Nearest Neighbors (KNN)
- Random Forest Regressor
- Extra Trees Regressor
- Gradient Boosting Regressor
- XGBoost Regressor
- LightGBM Regressor

---

## 🔗 GitHub & Deployment

- [https://www.kaggle.com/code/ishaks2005/airfare-forecasting-system](#) 
- (https://github.com/Isha-NIT/airfare-forecasting-system)(#) 

---

## 📬 Contact

For queries, contact via GitHub or ishaks1995@gmail.com

