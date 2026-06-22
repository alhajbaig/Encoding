# 🚢 Titanic Data Preprocessing: Label Encoding & One-Hot Encoding

A data preprocessing project on the Titanic dataset demonstrating **data cleaning**, **handling missing values**, **Label Encoding**, and **One-Hot Encoding** using **Pandas** and **Scikit-learn**. This project prepares raw data for machine learning models.

---

## 📌 Features

- ✅ Data Exploration
- ✅ Missing Value Handling
- ✅ Duplicate Removal
- ✅ Label Encoding (`Sex`)
- ✅ One-Hot Encoding (`Embarked`)
- ✅ Feature Selection
- ✅ Train-Test Split
- ✅ Feature Scaling
- ✅ Logistic Regression Model
- ✅ Model Evaluation

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## 📂 Dataset

- **Dataset:** Titanic Dataset
- **Source:** Kaggle

---

## 🔄 Data Preprocessing Steps

### 1. Missing Value Treatment
- Filled missing values in `Age` using median.
- Filled missing values in `Embarked` using mode.
- Removed `Cabin` column due to excessive missing values.

### 2. Duplicate Removal
- Removed duplicate rows to ensure data quality.

### 3. Label Encoding
Applied Label Encoding on the `Sex` column:

| Before | After |
|---------|-------|
| Male | 1 |
| Female | 0 |

### 4. One-Hot Encoding
Applied One-Hot Encoding on the `Embarked` column:

| Embarked |
|-----------|
| C |
| Q |
| S |

Converted into:

- Embarked_Q
- Embarked_S

### 5. Feature Scaling
Used StandardScaler on numerical columns:

- Age
- Fare

---

## 📊 Model Used

- Logistic Regression

---

## 📈 Evaluation Metrics

- Accuracy Score
- Confusion Matrix
- Classification Report

---

## 📁 Project Structure

```
Titanic-Encoding-Project/
│
├── Titanic_Project.ipynb
├── Titanic-Dataset.csv
├── cleaned_titanic.csv
├── titanic_model.pkl
├── README.md
├── requirements.txt
└── images/
```

---

## 🚀 Installation

```bash
git clone https://github.com/yourusername/Titanic-Encoding-Project.git

cd Titanic-Encoding-Project

pip install -r requirements.txt
```

---

## ▶️ Run

```bash
jupyter notebook
```

Open `Titanic_Project.ipynb` and execute all cells.

---

## 📚 Concepts Demonstrated

- Data Cleaning
- Missing Value Handling
- Label Encoding
- One-Hot Encoding
- Feature Scaling
- Train-Test Split
- Logistic Regression
- Model Evaluation

---

## ⭐ If you found this project helpful, consider giving it a star!
