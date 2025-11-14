# Titanic Dataset – Data Preprocessing & Machine Learning

📌 Project Overview  
This project focuses on cleaning and preprocessing the Titanic dataset and building a simple Logistic Regression model to predict whether a passenger survived.

---

📂 Project Structure  
AIML INTERNSHIP/  
│  
├── src/  
│   └── preprocessing.py  
├── notebooks/  
│   └── preprocessing.ipynb  
├── data/  
│   ├── titanic.csv  
│   └── titanic_clean.csv  
├── requirements.txt  
└── README.md  

---

## Data Preprocessing Steps

### ✔ Missing Values
- Numeric → median  
- Categorical → most frequent (mode)

### ✔ Encoding
- One-Hot Encoding for `Sex`, `Embarked`

### ✔ Feature Engineering
- Added: `FamilySize = SibSp + Parch + 1`

### ✔ Outlier Removal
- Removed using IQR method on `Fare`

### ✔ Feature Scaling
- StandardScaler applied to: `Age`, `Fare`

### ✔ Cleaned File Saved As
`titanic_clean.csv`

---

## 🤖 Machine Learning Model
- Model: Logistic Regression  
- Train/Test Split: 80/20  
- Final Accuracy:  
`75.48%`

---

## 📁 Files Included
- preprocessing.py  
- preprocessing.ipynb  
- titanic.csv  
- titanic_clean.csv  
- requirements.txt  
- README.md  

---

## 🙌 Author
**Kavya V**
