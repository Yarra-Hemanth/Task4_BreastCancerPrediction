# 🩺 Breast Cancer Prediction using Logistic Regression  

## 📌 Project Overview  
This project implements **Logistic Regression** to classify tumors as **benign** or **malignant** using the **Breast Cancer Wisconsin dataset**.    
The main objective is to build a binary classifier, evaluate it with various metrics, and visualize model performance.  

---

## 📂 Dataset  
**Source:** [Breast Cancer Wisconsin Dataset – Kaggle](https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data)  

### Columns:  
- **Features:** Mean, Standard Error, and Worst values of radius, texture, perimeter, area, smoothness, compactness, concavity, etc.  
- **Target:** `diagnosis` → **M** = Malignant (1), **B** = Benign (0)  

---

## ⚙️ Preprocessing Steps  
1. Removed unnecessary columns (`id`, `Unnamed: 32`).  
2. Encoded `diagnosis` column: `M` → 1, `B` → 0.  
3. Train-Test split: 80% training, 20% testing.  
4. Standardized features using `StandardScaler`.  

---

## 📊 Model  
- **Algorithm:** Logistic Regression (`sklearn.linear_model.LogisticRegression`)  
- **Solver:** Default (`lbfgs`), max iterations = 1000  

---

## 🚀 Results  

| Metric        | Value   |  
|---------------|---------|  
| Accuracy      | 97%     |  
| Precision     | 97.62%  |  
| Recall        | 95.35%  |  
| ROC-AUC       | 0.9974  |  

---

## 📈 Visualizations  
- **Confusion Matrix:** Shows correct and incorrect predictions.  
- **ROC Curve:** Displays classification threshold performance.  

---

## 📌 Conclusion  
- Logistic Regression achieved **excellent performance** on this dataset.  
- **ROC-AUC** close to 1 indicates near-perfect separation between classes.  
- Minimal false positives and false negatives make this model highly reliable for medical screening.  
- Due to its simplicity and interpretability, Logistic Regression is a strong choice for this binary classification problem.  

---

## 🛠️ Tools & Libraries  
- Python  
- Pandas, NumPy  
- Scikit-learn  
- Matplotlib, Seaborn  
- Google Colab  

---

## 📜 How to Run  
1. Clone the repository    
   ```bash  
   git clone https://github.com/yourusername/breast-cancer-prediction.git  
   cd breast-cancer-prediction
   
2. Run the notebook in Jupyter or Google Colab.

📬 Contact  
Author: Hemanth Yarra  
LinkedIn: [hemanth-yarra  ](https://www.linkedin.com/in/hemanth-yarra-5a1775305/)
Email: yarrahemanth5@gmail.com  
