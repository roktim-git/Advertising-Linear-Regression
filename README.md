# 📈 Advertising Sales Prediction using Multiple Linear Regression

A Machine Learning project that predicts product sales based on advertising expenditure on **TV**, **Radio**, and **Newspaper** using **Multiple Linear Regression**.

---

## 📌 Project Overview

This project demonstrates the complete workflow of building a regression model using Python and Scikit-learn:

- Data loading and exploration
- Data cleaning
- Outlier detection and treatment
- Feature selection
- Model training
- Model evaluation
- Data visualization

The goal is to understand how advertising budgets influence product sales and build a model capable of predicting future sales.

---

## 📂 Dataset

The dataset contains advertising budgets spent on different media and the corresponding sales.

| Feature | Description |
|---------|-------------|
| TV | Advertising budget spent on TV |
| Radio | Advertising budget spent on Radio |
| Newspaper | Advertising budget spent on Newspaper |
| Sales | Product sales (Target Variable) |

---

## 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## 📊 Data Preprocessing

The following preprocessing steps were performed:

- Checked dataset information
- Checked missing values
- Checked duplicate records
- Generated descriptive statistics
- Detected outliers using Box Plot and IQR method
- Replaced Newspaper outliers with the median value

---

## 🤖 Machine Learning Model

**Algorithm Used**

- Multiple Linear Regression

### Features

- TV
- Radio
- Newspaper

### Target

- Sales

---

## 📈 Model Evaluation

The model was evaluated using the following metrics:

| Metric | Value |
|---------|------:|
| Mean Absolute Error (MAE) | **1.287** |
| Mean Squared Error (MSE) | **2.940** |
| Root Mean Squared Error (RMSE) | **1.715** |
| R² Score | **0.905** |

### Interpretation

- The model explains approximately **90.5%** of the variance in sales.
- The average prediction error is around **1.29 sales units**.
- Overall, the model performs well on unseen test data.

---

## 📉 Visualizations

The project includes:

- Box Plot for Outlier Detection
- Actual vs Predicted Sales Plot
- Residual Plot

---

## 📁 Project Structure

```
Advertising-Linear_regression/
│
├── advertising.csv
├── abbabfb.py
├── README.md
├── requirements.txt
└── .gitignore
```

---

## 🚀 How to Run

### Clone the repository

```bash
git clone https://github.com/roktim-git/Advertising-Linear-Regression.git
```

### Move into the project folder

```bash
cd Advertising-Linear-Regression
```

### Install dependencies

```bash
pip install -r requirements.txt
```

### Run the project

```bash
python linear_regression.py
```

---

## 📚 Concepts Covered

- Data Cleaning
- Exploratory Data Analysis (EDA)
- Outlier Detection (IQR Method)
- Feature Selection
- Train-Test Split
- Multiple Linear Regression
- Model Evaluation
- Residual Analysis
- Data Visualization

---

## 🎯 Future Improvements

- Feature Scaling
- Polynomial Regression
- Ridge Regression
- Lasso Regression
- Cross Validation
- Hyperparameter Tuning
- Model Comparison

---

## 👨‍💻 Author

**Roktim Ray**

Computer Science Student | Python | Machine Learning | Data Science Enthusiast

GitHub: https://github.com/roktim-git

---

## ⭐ If you found this project useful, consider giving it a star!
