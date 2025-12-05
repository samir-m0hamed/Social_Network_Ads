# 📘 Predicting Purchase Behavior using Logistic Regression

.

## 📝 Overview

This project applies **Binary Logistic Regression** to predict whether a user will purchase a product based on demographic features from the **Social Network Ads dataset**.  
The pipeline includes **data preprocessing, feature scaling, model training, evaluation, and decision boundary visualization**.

The model demonstrates strong performance with **86% accuracy on test data** and **84% accuracy on training data**.

---

## 📂 Dataset

The dataset contains demographic attributes and purchase decisions.

**Features:**
- Age  
- Estimated Salary  

**Target:**
- Purchased (0 or 1)

This dataset is widely used for practicing binary classification and visualizing decision boundaries.

---

## 🚀 Project Workflow

1. Load and explore the dataset  
2. Preprocess features  
3. Apply feature scaling with `StandardScaler`  
4. Train a Logistic Regression model  
5. Evaluate on training and testing sets  
6. Visualize results and decision boundary  

---

## 🧠 Model Details

**Algorithm:** Logistic Regression  
- Type: Binary Classification  
- Activation: Sigmoid  
- Optimization: Gradient Descent through scikit-learn  
- Decision Boundary: Linear  
- Evaluation Metric: Accuracy and Confusion Matrix  

---

## 📊 Results

### ✔️ Training Performance

- **Accuracy:** 84%

**Confusion Matrix (training data):**

|                       | Pred 0 | Pred 1 |
|-----------------------|--------|--------|
| **Actual 0**          | 190    | 36     |
| **Actual 1**          | 15     | 79     |


---

### ✔️ Testing Performance

- **Accuracy:** 86%

**Confusion Matrix (test data):**

|           | Pred 0 | Pred 1 |
|-----------|--------|--------|
| Actual 0  |   50   |   2    |
| Actual 1  |   9    |   19   |


---

## 📈 Visualizations

The project includes meaningful visualizations such as:

- Scatter plot of testing results  
- Decision boundary  
- Classification regions showing predicted classes  

These visualizations help understand how the model separates buyers vs non-buyers.

---

## 🛠️ Technologies Used

- Python  
- NumPy  
- Pandas  
- Plotly  
- Scikit-Learn  
- Classification
- Binary Logistic Regression

---

## ▶️ Usage

Identifying which customers are likely to purchase the product, allowing us to deliver targeted social media advertisements specifically to them. .


## 🔮 Future Work

- Apply feature selection or regularization  
- Apply hyperparameter tuning  
- Extend feature engineering  
- Collect more diverse demographic features  
- Evaluate model with precision, recall, ROC-AUC

---

## 👤 Author

**Samir Mohamed Samir**  
AI & Machine Learning Enthusiast  

---

## ⭐ Summary

This project demonstrates how **Binary Logistic Regression** can effectively model user purchasing behavior from demographic features using a simple and interpretable method.  
The model achieved **84% accuracy on training data** and **86% on test data**, supported by visual decision boundary analysis.


