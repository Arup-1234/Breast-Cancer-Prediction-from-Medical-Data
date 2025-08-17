# Breast Cancer Prediction  
**CodeAlpha Internship Project**  

## Overview  
A machine learning project aimed at classifying tumors as **Benign (0)** or **Malignant (1)**.  
Trained and compared multiple ML models and visualized their performance using ROC curves and prediction plots.  

## Dataset  
- Source: UCI Breast Cancer Wisconsin Diagnostic dataset  
- Features: Various cell nucleus measurements (radius, texture, perimeter, area, etc.)  
- Target: 0 = Benign, 1 = Malignant  

## Models  
- Logistic Regression  
- Decision Tree  
- Random Forest  
- Support Vector Machine (SVM)  
- Naive Bayes  
- XGBoost  

## Results  
- Random Forest & XGBoost achieved the highest performance with AUC scores ≈ 0.98–0.99  
- Logistic Regression also performed strongly  

## Tech Stack  
- Python: Scikit-learn, XGBoost, Pandas, NumPy, Matplotlib, Seaborn  

## How to Run  
1. Clone the repo  
```bash
git clone https://github.com/your-username/Breast-Cancer-Prediction.git
cd Breast-Cancer-Prediction
```  

2. Install dependencies  
```bash
pip install -r requirements.txt
```  

3. Open and run `notebook.ipynb`  

---
