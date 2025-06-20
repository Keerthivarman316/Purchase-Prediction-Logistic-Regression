# 🧠 Purchase Prediction using Logistic Regression

This project predicts whether a user will purchase a product based on their **Age** and **Estimated Salary** using **Logistic Regression**.

---

## 📂 Dataset

- **File**: `Social_Network_Ads.csv`
- **Features**:
  - `Age`
  - `EstimatedSalary`
- **Target**:
  - `Purchased` (0 = Not Purchased, 1 = Purchased)

---

## 🚀 Project Flow

1. Data Preprocessing using `MinMaxScaler`
2. Train-Test Split
3. Model Training using `LogisticRegression`
4. Evaluation using Accuracy, Confusion Matrix, and Classification Report
5. Visualization of Decision Boundary
6. Custom input prediction

---

## 📊 Visualization

Example output:

![Decision Boundary](images/decision_boundary.png)

---

## 🧠 What I Learned

- Building a full ML pipeline using Scikit-learn
- Feature scaling techniques
- Evaluating classifiers using confusion matrix and classification report
- Visualizing decision boundaries with `mlxtend`

---

## 🛠️ Tech Stack

- Python
- Pandas, NumPy
- scikit-learn
- Matplotlib, Seaborn
- mlxtend

---

## 📦 Installation

Install all required libraries:

```bash
pip install -r requirements.txt
