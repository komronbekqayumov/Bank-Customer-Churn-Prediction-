
---

## 🧠 Customer Churn Prediction

This project focuses on predicting **customer churn** using supervised machine learning algorithms. The dataset is preprocessed, enhanced with feature engineering, and evaluated across multiple models to identify the most accurate predictor.

---

### 📂 Project Structure

```
├── dataset.csv
├── churn_prediction.ipynb
├── final_predictions.csv
├── models.pkl
├── requirements.txt
└── README.md
```

---

### 🛠 Technologies Used

* Python
* Pandas, NumPy
* Scikit-learn
* XGBoost
* LightGBM
* Matplotlib, Seaborn
* Jupyter Notebook (Kaggle Environment)

---

### 🔄 Workflow

1. **Data Preprocessing**

   * Handled missing values
   * Encoded categorical variables (LabelEncoding, OneHotEncoding)

2. **Feature Engineering**

   * Created new features such as `AgeBalanceRatio`, `IsSenior`, `HasHighBalance`, `ProductsPerYear`, and others to boost model performance

3. **Model Training & Evaluation**
   Models used:

   * Logistic Regression
   * Random Forest
   * XGBoost
   * LightGBM
   * K-Nearest Neighbors (KNN)
   * Support Vector Machine (SVM)

4. **Model Selection**

   * Accuracy scores were compared, and the best-performing model was identified

---

### ✅ Results

```text
Logistic Regression         → Accuracy: 88.57%
Random Forest               → Accuracy: 89.73%
XGBoost                     → Accuracy: 89.50%
LightGBM                    → Accuracy: 89.93%
K-Nearest Neighbors (KNN)   → Accuracy: 87.47%
Support Vector Machine (SVM) → Accuracy: 89.27%


🎯 Best Model: Random Forest Classifier  
✔️ Accuracy: 89.73%
```

---



For questions or suggestions, feel free to open an issue or contact me via GitHub.

---

