
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
Logistic Regression     → Accuracy: 88.7%
Random Forest           → Accuracy: 93.2%
XGBoost                 → Accuracy: 92.4%
K-Nearest Neighbors     → Accuracy: 91.1%
LightGBM (GBooster)     → Accuracy: 92.3%
Support Vector Machine  → Accuracy: 89.5%

🎯 Best Model: Random Forest Classifier  
✔️ Accuracy: 93.2%
```

---

### 📁 Output

Final predictions were saved to a CSV file:

```python
final_df.to_csv("final_predictions.csv", index=False)
```

---

### ▶️ How to Run

1. Clone the repository
2. Install dependencies

```bash
pip install -r requirements.txt
```

3. Open and run the notebook `churn_prediction.ipynb` in Jupyter or Kaggle

---

### 📬 Contact

For questions or suggestions, feel free to open an issue or contact me via GitHub.

---

