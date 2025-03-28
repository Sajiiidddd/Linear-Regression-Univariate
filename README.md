# 🏡 House Price Prediction using Hardcoded Linear Regression

## 📌 Overview
This project implements a **hardcoded** univariate linear regression model to predict house prices based on square footage. Unlike traditional approaches using Scikit-Learn, this model is built **from scratch**, implementing gradient descent optimization and regularization.

---

## 📊 Dataset
The dataset consists of **50 records** with the following columns:
- 📏 **`Area in sq feet`** (Independent Variable)
- 💰 **`Prices in $`** (Dependent Variable)

---

## 🚀 Features Implemented
- **🔹 Data Preprocessing:**
  - Standardization using `StandardScaler`.
  - Cleaning column names for consistency.
- **🔹 Linear Regression Model:**
  - Manual weight (`W`) and bias (`b`) initialization.
  - Gradient Descent optimization with a learning rate of `0.00001`.
  - Regularization to prevent overfitting.
- **🔹 Performance Evaluation:**
  - Cost function based on Mean Squared Error (MSE).
  - Loss visualization during training.
  - Scatter plot comparing actual vs. predicted prices.

---

## ⚙️ Installation
To run this project, install the required dependencies:
```bash
pip install numpy pandas matplotlib
```

---

## ▶️ Usage
Run the Jupyter Notebook to execute the model:
```bash
jupyter notebook linear_regression_demo.ipynb
```

---

## 📈 Results
✔️ The model effectively predicts house prices using a simple linear function.
✔️ Training loss reduces with iterations, indicating convergence.
✔️ The final weight and bias values define the best-fit line.

---

## 📜 License
This project is licensed under the **MIT License**. See `LICENSE` for details.

🌟 *Feel free to contribute, modify, or use this project for learning!* 🚀

