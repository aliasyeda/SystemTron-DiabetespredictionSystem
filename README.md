# SystemTron-DiabetespredictionSystem

# 🧪 Diabetes Prediction System | SystemTron Internship Project

This project predicts whether a person is diabetic or not using Machine Learning (Logistic Regression). The model is trained on medical data like glucose level, BMI, age, insulin, and more.

## 📁 Dataset

- Format: CSV (from Google Sheets)
- Columns include: Pregnancies, Glucose, BloodPressure, SkinThickness, Insulin, BMI, DiabetesPedigreeFunction, Age, Outcome

## ✅ Technologies Used
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn (Logistic Regression)

## 🔎 Workflow Summary

1. **Data Loading**
   - Read CSV file into Pandas DataFrame
   - View and clean data

2. **Exploratory Data Analysis (EDA)**
   - Use `.describe()` and `.info()`
   - Visualize class distribution and feature correlation

3. **Data Preprocessing**
   - Split data into features (X) and target (y)
   - Perform train-test split (80/20)
   - Scale features using `StandardScaler`

4. **Model Building**
   - Logistic Regression model is trained
   - Predictions made on test set

5. **Evaluation**
   - Accuracy Score
   - Confusion Matrix
   - Classification Report

6. **New Patient Prediction**
   - Accepts new patient data
   - Predicts if the patient is diabetic or not

## 🧠 Sample Prediction Output

Prediction: Not Diabetic
Accuracy Score: 78.5%

---

💡 Why Logistic Regression?

Best for binary classification problems like this (Yes/No)

Easy to understand and fast to train

Great baseline model for medical prediction tasks

---

## 👨‍💻 Author

Developed by
**Syeda Alia Samia**  
GitHub:[Syeda Alia Samia](https://github.com/your-github-username)

