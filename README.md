# 🧬 Hepatitis Education (Hepatitis Detection Using Machine Learning)

Welcome to the **Hepatitis Detection** project! This repo showcases a full machine learning pipeline used to predict mortality outcomes in hepatitis patients using real-world clinical data.

Built by students in the **INST452** course, this project combines data wrangling, model evaluation, and ethical AI considerations—all in the context of healthcare.

---

## 🎯 Project Objective

Can we predict **mortality in hepatitis patients** using machine learning?

> ✔️ Goal: Train and evaluate classification models to identify at-risk patients based on their lab values and clinical indicators.

---

## ⚙️ Methods & Tools

- **Language**: R (via R Markdown)
- **Dataset**: [UCI Hepatitis Dataset](https://archive.ics.uci.edu/ml/datasets/hepatitis)
- **Preprocessing**:
  - Missing value imputation
  - Binary encoding of labels
  - Feature normalization and cleanup
- **Algorithms**:
  - Decision Tree 🌳
  - Support Vector Machine (SVM) 🔎
  - k-Nearest Neighbors (KNN) 🧭

---

## 📊 Model Results

| Model      | ROC-AUC | Sensitivity | Specificity |
|------------|---------|-------------|-------------|
| SVM        | 0.84    | 85%         | 78%         |
| Decision Tree | 0.75 | 79%         | 72%         |
| KNN        | 0.72    | 76%         | 68%         |

> 🔍 **SVM** outperformed others in balancing both sensitivity and specificity, making it the preferred model for clinical use cases.

---

## 🌐 Fairness & Ethics

We evaluated model performance across subgroups (e.g., gender) to identify potential biases.

✔️ Fairness tests showed **moderate imbalance**, leading us to recommend **reweighting** strategies in deployment to avoid disparities in care.

---

## 🧠 Insights

- **Bilirubin**, **Sgot**, and **Albumin** levels had strong predictive power.
- Class imbalance and small sample size posed challenges—highlighting the need for richer, more representative clinical data.
- High sensitivity was prioritized to minimize false negatives in life-threatening cases.

---

## 👥 Team Members

- Samuel Muma  
- Chantel Orimoloye  
- Dara Ojebouoh  
- Kyle Tabong  

---

## 📢 How to Use

> _This project is best viewed through the R Markdown report or presentation slides._

1. Clone the repository:
   ```bash
   git clone https://github.com/iamsamuelm/healthcare-data-analytics.git
