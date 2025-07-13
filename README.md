# 🧠 Decision Tree Classifier on Bank Marketing Dataset

This project aims to predict whether a client will subscribe to a term deposit using a Decision Tree Classifier. The dataset is sourced from the [UCI Bank Marketing Dataset](https://archive.ics.uci.edu/ml/datasets/bank+marketing).

---

## 📌 Objective

To build a decision tree classifier that predicts customer subscription (`yes` or `no`) based on demographic and behavioral data.

---

## 📊 Dataset

- **Rows:** 45,211
- **Columns:** 17+
- **Target Variable:** `y` (subscription)

---

## ✅ Key Tasks Performed

- ✅ Data Cleaning (`unknown` replaced with nulls)
- ✅ Handling missing values (filled with `0`)
- ✅ Exploratory Data Analysis:
  - Balance vs Subscription
  - Age Group vs Subscription
- ✅ Built Decision Tree Classifier (using scikit-learn)
- ✅ Visualized top 3 levels of the decision tree
- ✅ Identified top 10 important features
- ✅ Saved prediction results to CSV

---

## 📊 Top Features (Feature Importance)

| Feature | Importance Score |
|---------|------------------|
| duration | 0.45 (example) |
| poutcome | 0.17 |
| age_group | 0.13 |
| ... | ... |

---

## 📈 Model Accuracy

```text
Accuracy: 0.88
Precision / Recall / F1 reported using sklearn
