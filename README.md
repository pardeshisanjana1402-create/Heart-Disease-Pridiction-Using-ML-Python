#  Heart Disease Prediction – Machine Learning Project using Python

This project predicts whether a patient has heart disease using basic medical features.
The workflow includes **data cleaning**, **EDA**, **model building**, and a **final report**.

---
## Project Structure

```
project-name/
│
├── data/
│   ├── raw/
│   └── cleaned/
│
├── notebooks/
│   ├── block_a_data_cleaning.ipynb
│   ├── block_b_eda.ipynb
│   ├── block_c_modeling.ipynb
│   └── block_d_final_report.ipynb
│
├── src/
│   ├── data_cleaning.py
│   ├── eda.py
│   ├── modeling.py
│   └── visualization.py
│
├── README.md
└── requirements.py
```

---
## Project Goal

To build an easy and accurate machine learning model that helps identify whether a patient has heart disease based on health parameters.

---
## Block A – Data Cleaning

* Load raw dataset
* label encoding
* Check missing values
* Handle nulls using SimpleImputer
* Remove duplicates
* Convert data into clean format
* Save cleaned data into `data/cleaned/`

---
## Block B – Exploratory Data Analysis (EDA)

* Generate basic statistics
* Plot distributions (age, cholesterol, etc.)
* Heatmap to check correlations
* Countplots and boxplots
* Understand patterns related to heart disease

---
## Block C – Modeling

**Models used:**

* Logistic Regression
* Random Forest
* Gradient Boosting
* SVM (Support Vector Machine)

**Evaluation metrics:**

* Accuracy
* Precision
* Recall
* F1 Score
* ROC-AUC
* Confusion Matrix
* ROC Curve

Selected the best model based on performance.

---
## Block D – Final Report

* Summary of dataset
* Key findings from EDA
* Model comparison
* Best model explanation
* Final conclusion

---
## Technologies Used

```
pandas
numpy
matplotlib
seaborn
scikit-learn
joblib
```

---
##  How to Run

1. Install requirements

   ```
   pip install -r requirements.py
   ```

2. Open Jupyter Notebook

   ```
   jupyter notebook
   ```

3. Run notebooks in order:

   * A → Data Cleaning
   * B → EDA
   * C → Modeling
   * D → Final Report

---
## Author

**Sanjana M. Pardeshi**
Machine Learning | Data Science
