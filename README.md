# bank-customer-churn-analysis
Project Overview

Proyek ini menganalisis data pelanggan bank untuk mengidentifikasi faktor-faktor yang mempengaruhi tingkat churn pelanggan dan membangun model pembelajaran mesin untuk memprediksi pelanggan yang kemungkinan akan meninggalkan bank.

Tujuan proyek ini adalah untuk mendukung strategi retensi pelanggan dengan mengidentifikasi pelanggan berisiko tinggi secara dini.

Dataset:
Source: Bank Customer Churn Dataset
Records: 10,000 customers
Target variable: Exited (1 = churn, 0 = non-churn)

Tools & Libraries
Python
pandas, numpy
matplotlib, seaborn
scikit-learn

Methodology:

1. Data cleaning and preprocessing
2. Exploratory Data Analysis (EDA)
3. Feature encoding and scaling
4. Model development (with class balancing):
  a.Logistic Regression
  b.Decision Tree
  c.Random Forest
5. Model evaluation:
  a.Confusion Matrix
  b.Classification Report
  c.Precision–Recall Curve

Results:

Random Forest memiliki hasil terbaik dengan:
Accuracy ≈ 81%
Recall (churn) ≈ 77%
Average Precision ≈ 0.68
Precision–Recall Curve was used due to class imbalance.

Business Insights:
1.nasabah yang sudah tua dan tidak aktif memiliki risiko lebi tinggi untuk churn
2.Keanggotaan aktif secara signifikan mengurangi probabilitas churn.
3.Prediksi threshold dapat disesuaikan berdasarkan strategi retensi (program terbatas vs massal).

Conclusion:

Model ini dapat digunakan sebagai sistem peringatan dini untuk membantu bank memprioritaskan upaya retensi pelanggan secara lebih efektif.
