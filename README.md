# 📊 50 Startups Profit Prediction – Machine Learning Project

## 📁 Project Overview

This project is part of the **Corvit / NAVTTC / SAI - AI (ML | DL) Foundation Course**.  
The goal is to analyze a startup dataset and build a machine learning model to **predict profit based on different expenditures**.

---

## 📂 Repository Structure
- solution.ipynb
- question.ipynb
- 50_startups_dataset.csv
- README.md


---

## 📌 Dataset Description

The dataset contains **50 startup records** with the following features:

* **R&D Spend** → Investment in research & development
* **Administration** → Administrative expenses
* **Marketing Spend** → Marketing budget
* **State** → Location of the startup
* **Profit** → Target variable (to predict)

---

## 🔍 Exploratory Data Analysis (EDA)

Performed detailed EDA to understand data patterns:

* ✔ Distribution plots of features
* ✔ Correlation heatmap
* ✔ State-wise analysis
* ✔ Feature relationships with Profit

---

## 🤖 Model Building

* Applied **Linear Regression**
* Performed **One-Hot Encoding** on categorical feature (State)
* Split dataset into:

  * Training set (80%)
  * Test set (20%)

---

## 📈 Model Performance

* **R² Score:** 0.8987
* **MAE:** 6,961
* **RMSE:** 9,055

👉 The model explains ~**89% of variance**, indicating strong predictive performance.

---

## 📊 Visualizations Included

* ✔ Correlation Heatmap
* ✔ Actual vs Predicted Plot
* ✔ Feature Importance (coefficients) chart

---

## 🧠 Key Insights

* **R&D Spend** has the strongest positive impact on profit
* **Marketing Spend** contributes moderately
* **Administration** has minimal or negative impact
* Location (State) has very small influence compared to spending

---

## ⚠️ Limitations

* Small dataset (50 samples)
* Assumes linear relationships
* Sensitive to outliers
* Does not capture time-based effects

---

## 🚀 Future Improvements

* Use **Polynomial Regression** for non-linearity
* Apply **Regularization (Ridge/Lasso)**
* Try advanced models like:

  * Random Forest
  * XGBoost
* Collect more data for better generalization

---

## 📋 Submission Checklist

* [✓] All cells executed without errors
* [✓] EDA section has at least 3 visualizations
* [✓] Model trained with R² score printed
* [✓] Actual vs Predicted plot included
* [✓] Feature importance chart included
* [✓] Conclusion section filled with analysis

---

## 🎓 Course Info

**Corvit / NAVTTC / SAI - AI (ML | DL) Foundation Course**

---

## 👨‍💻 Author

Muhammad Aliyan

---