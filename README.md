# 🧪 Medical Insurance Cost Prediction

This project aims to predict individual medical charges billed by health insurance using personal and demographic features. The goal is to build regression models, tune their hyperparameters, and compare their performance to identify the best-performing algorithm.

![Python](https://img.shields.io/badge/Python-3.10-blue.svg) ![License](https://img.shields.io/badge/License-MIT-green.svg)

---

## 📁 Dataset

- Source: [Medical Cost Personal Datasets on Kaggle](https://www.kaggle.com/datasets/mirichoi0218/insurance)
- The dataset contains 7 features:
  - `age`: Age of the primary beneficiary
  - `sex`: Gender of the insurance policyholder
  - `bmi`: Body mass index
  - `children`: Number of dependents covered by insurance
  - `smoker`: Smoking status
  - `region`: U.S. region of residence
  - `charges`: Medical cost billed to the insurance customer (target)

---

## 🧪 Project Workflow

### ✔️ Completed
- Data loading and cleaning
- Sustantial Exploratory Data Analysis (EDA)
  - Distribution analysis
  - Categorical-numerical comparisons
  - Numerical feature exploration with interaction effects 
- `LinearRegression`

### 🚧 In Progress / Upcoming

- Model training and evaluation:
  - `KNeighborsRegressor`
  - `DecisionTreeRegressor`
  - `RandomForestRegressor`
  - `XGBRegressor`
- Hyperparameter tuning using GridSearchCV / RandomizedSearchCV
- Performance comparison using RMSE / MAE / R²

---

## 📂 Folder Structure

```bash
Medical-Insurance-Cost-Prediction/
├── data/                # Raw dataset (insurance.csv)
├── notebooks/           # Jupyter notebooks (EDA, modeling)
├── models/              # Saved model files 
├── LICENSE              # MIT License
├── README.md
└── requirements.txt     # Project dependencies
```

---

## 🛠️ Technologies Used

- Python (Pandas, NumPy, Scikit-learn, XGBoost, Matplotlib, Seaborn)
- Jupyter Notebook
- Git & GitHub

---

## 📈 Goals

To analyze factors influencing medical charges and compare the performance of various regression models in predicting costs accurately. Special focus is given to interaction effects (e.g., smoking × BMI), robust EDA, and transparent model evaluation.

---

## 📄 License

This project is licensed under the MIT License.