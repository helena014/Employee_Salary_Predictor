# Employee_Salary_Predictor
# 💼 Employee Salary Prediction using Regression

This project aims to predict employee salaries based on various features like age, gender, education level, job title, and years of experience. The best-performing model is deployed as a web app using **Streamlit** on **Hugging Face Spaces**.

---

## 📌 Problem Statement

Organizations often need to plan budgets and compensation structures based on various employee attributes. Manual salary estimations are time-consuming and error-prone. This project helps **automate salary predictions**, allowing companies to make **data-driven decisions** in HR planning and workforce budgeting.

---

## 🚀 Project Pipeline (Algorithm)

1. **Import Libraries**  
2. **Load and Explore Dataset**
3. **EDA (Exploratory Data Analysis)**
4. **Outlier Detection and Removal** using IQR
5. **Preprocessing**
   - Label Encoding (`Education Level`)
   - One-Hot Encoding (`Gender`, `Job Title`)
   - Feature Scaling using `MinMaxScaler`
6. **Train-Test Split**
7. **Model Training with Multiple Algorithms**
   - Linear Regression
   - Decision Tree Regressor
   - Random Forest Regressor
   - Gradient Boosting Regressor
   - Support Vector Regressor
8. **Model Evaluation**
   - R² Score, RMSE, MAE
9. **Best Model Selection**: Random Forest Regressor
10. **Model Saving and Deployment with Streamlit**

---

## 🧠 Technologies & Libraries Used

- Python
- pandas, numpy
- seaborn, matplotlib
- scikit-learn
- joblib
- streamlit
- plotly



---

## 🌐 Deployment

The application is deployed using **Streamlit** on **Hugging Face Spaces**.  
🔗 [Live Demo Link(https://huggingface.co/spaces/Helena14/salary-predictor)]

---

## 📸 App Features

- Interactive sidebar inputs
- Salary prediction output with interpretation
- Gauge chart showing salary percentile
- Clean, tabbed UI with EDA visualizations

---

## ✅ Results

- **Best Model**: Random Forest Regressor
- **Performance**:


                   R2 Score          RMSE           MAE
Random Forest       0.976070      8018.180308     2993.175996




