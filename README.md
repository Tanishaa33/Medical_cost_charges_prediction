# 🏥 Medical Cost Prediction Using Machine Learning

## 📌 About the Project

This project predicts **medical insurance costs** using different machine learning regression algorithms.

The dataset contains information about:

- 👤 Age
- ⚧️ Sex
- ⚖️ BMI
- 👶 Number of children
- 🚬 Smoking status
- 🌎 Region

The target variable is **medical charges (`charges`)**.

---

## 🤖 Machine Learning Models

The following regression models were trained and compared:

1. **Linear Regression**
2. **Random Forest Regressor**
3. **Gradient Boosting Regressor**
4. **XGBoost Regressor**

---

## 🔄 Data Preprocessing

The following preprocessing steps were performed:

- 🧹 Cleaned the dataset
- 🔀 Split the data into training and testing sets
- 🔤 Applied One-Hot Encoding to categorical features
- 📊 Processed numerical features
- 🔗 Used Scikit-learn pipelines for preprocessing and model training

---

## 📏 Evaluation Metrics

The models were evaluated using three metrics.

### 📈 R² Score

Measures how well the model explains the variation in medical charges. Higher values indicate more explained variation.

### 📉 MAE

**Mean Absolute Error (MAE)** measures the average absolute difference between actual and predicted medical costs. Lower values are better.

### 📊 RMSE

**Root Mean Squared Error (RMSE)** gives more importance to larger prediction errors. Lower values are better.

---

## 🏆 Model Results

| Model | R² | MAE | RMSE |
|:---|---:|---:|---:|
| Linear Regression | 0.7833 | 4168.76 | 5799.73 |
| Random Forest | 0.8632 | 2536.20 | 4608.54 |
| **Gradient Boosting** | **0.8801** | **2392.58** | **4315.25** |
| XGBoost | 0.8770 | 2438.26 | 4370.72 |

---

## 🛠️ Technologies Used

- 🐍 Python
- 🐼 Pandas
- 🔢 NumPy
- 🤖 Scikit-learn
- 🚀 XGBoost
- 📊 Matplotlib
- 📓 Jupyter Notebook

---

## 📁 Project Structure

```text
Medical_cost_charges_prediction/
│
├── insurance.csv
├── Linear_regression.ipynb
├── Randomforest.ipynb
├── GradientBoosting.ipynb
├── XGBRegressor.ipynb
├── requirements.txt
└── README.md
