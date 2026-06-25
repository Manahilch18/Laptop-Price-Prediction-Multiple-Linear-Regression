# 💻 Laptop Price Prediction using Linear Regression

A Machine Learning project that predicts laptop prices based on hardware specifications using Multiple Linear Regression and Stochastic Gradient Descent (SGD).

This project was built as part of my Machine Learning learning journey after completing Mathematics for Machine Learning, where I applied concepts from Linear Algebra, Calculus, Probability, and Statistics to a real-world dataset.

---

## 🚀 Project Overview

The goal of this project is to predict laptop prices using features such as:

- RAM
- Weight
- CPU Brand
- GPU Brand
- SSD Storage
- HDD Storage
- Screen Resolution (PPI)
- Operating System
- Laptop Type
- Touch Screen Support

The project demonstrates the complete Machine Learning workflow:

1. Data Inspection
2. Data Preprocessing
3. Feature Engineering
4. One-Hot Encoding
5. Model Training
6. Model Evaluation
7. Residual Analysis
8. Feature Importance Visualization

---

## 📊 Dataset Information

Dataset Size:

- Rows: 1273
- Columns: 13

Target Variable:

- Price

Features:

- Company
- TypeName
- Ram
- Weight
- TouchScreen
- IPS
- PPI
- CPU Brand
- HDD
- SSD
- GPU Brand
- Operating System

---

## 🛠 Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-Learn

---

## 📈 Machine Learning Models

### 1️⃣ Multiple Linear Regression (OLS)

Used as the baseline model for price prediction.

### 2️⃣ Stochastic Gradient Descent (SGD)

Used to optimize the regression model through iterative learning.

---

## 📉 Model Performance

### Linear Regression (OLS)

| Metric | Value |
|----------|----------|
| MAE | 0.22 |
| R² Score | 0.8048 |

### SGD Regressor

| Metric | Value |
|----------|----------|
| MAE | 0.22 |
| R² Score | 0.8049 |

### Interpretation

- The model explains approximately 80% of the variance in laptop prices.
- Average prediction error is low.
- Both OLS and SGD achieved very similar performance.

---

## 📊 Visualizations

### Residual Error Analysis

This plot helps verify whether the model errors are randomly distributed.

✅ Residuals are centered around zero.

✅ No strong pattern observed.

✅ Indicates a reasonably good linear fit.

---

### Feature Importance Analysis

Top features contributing to higher laptop prices:

- Razer Brand
- LG Brand
- Google Brand
- Intel Core i7
- Intel Core i5
- Microsoft Brand
- Workstation Category

These features showed the strongest positive influence on laptop prices.

---

## 📚 What I Learned

Through this project I practiced:

- Data preprocessing
- One-Hot Encoding
- Feature Scaling
- Multiple Linear Regression
- Gradient Descent Optimization
- Model Evaluation Metrics
- Residual Analysis
- Feature Importance Interpretation
- Data Visualization

I also strengthened my understanding of:

- Linear Algebra
- Calculus
- Probability & Statistics
- Machine Learning Fundamentals

---

## 🎯 Future Improvements

- Ridge Regression
- Lasso Regression
- Polynomial Regression
- Hyperparameter Tuning
- Cross Validation
- Model Deployment using Streamlit

---

## 📷 Project Outputs

### Residual Analysis Plot

(Add image here)

### Feature Importance Plot

(Add image here)

---

## 👩‍💻 Author

**Manahil Ishfaq**

AI & Machine Learning Learner

Currently building projects while learning Mathematics, Machine Learning, Data Science, and Generative AI.

GitHub:
https://github.com/Manahilch18

---

⭐ If you found this project interesting, feel free to star the repository.
