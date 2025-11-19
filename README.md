# 🎓 Analyzing Student Performance Based on Social and Economic Factors

## 📘 Project Overview

This project explores how **social and economic factors** such as parental education, lunch type, and test preparation courses influence students' academic performance in **math, reading, and writing**.

The analysis is based on the **Students Performance in Exams** dataset, which provides valuable insights into how background characteristics affect academic success. The main objective is to apply data mining and machine learning techniques to analyze these relationships and predict students' performance trends.

---

## 🧩 Project Structure (Google Colab Workflow)

### 1. **Title & Introduction**

**Title:** Analyzing Student Performance Based on Social and Economic Factors  
**Objective:** To explore how family background and socioeconomic conditions affect students’ scores and to predict academic performance using data-driven insights.

### 2. **Data Loading**

- Dataset: _Students Performance in Exams_ (available on [Kaggle](https://www.kaggle.com/spscientist/students-performance-in-exams))
- The dataset was loaded into Google Colab via:
  - Direct Kaggle API access, or
  - Manual upload to Colab.

### 3. **Data Cleaning & Preprocessing**

- Checked for and handled missing values.
- Verified and adjusted data types.
- Removed potential outliers to ensure data quality.
- Standardized categorical and numerical values for analysis.

### 4. **Exploratory Data Analysis (EDA)**

- Used **Matplotlib** and **Seaborn** for data visualization.
- Explored score distributions across gender, parental education, lunch type, and test preparation.
- Visualized correlations between features and performance metrics.
- Discovered patterns such as:
  - Students with **standard lunch** and **completed test preparation** performed better.
  - **Parental education level** correlated positively with student scores.

### 5. **Feature Engineering**

- Encoded categorical variables (e.g., gender, lunch type) using label or one-hot encoding.
- Created new features to represent combined performance metrics.
- Scaled numerical features to improve model performance.

### 6. **Model Building**

- Split dataset into training and testing subsets.
- Trained multiple machine learning models, such as:
  - Linear Regression
  - Decision Tree Regressor
  - Random Forest Regressor
- Tuned hyperparameters for better accuracy.

### 7. **Model Evaluation**

- Evaluated performance using:
  - Mean Squared Error (MSE)
  - Root Mean Squared Error (RMSE)
  - R² Score
- Compared model results to select the best performer.

### 8. **Conclusion & Discussion**

- **Findings:**
  - Test preparation and lunch type significantly influence academic success.
  - Parental education level strongly affects reading and writing performance.
- **Limitations:**
  - Dataset size limits generalization.
  - Model accuracy could improve with additional socioeconomic variables.
- **Future Work:**
  - Include more demographic and behavioral data.
  - Explore deep learning models for prediction.

---

## 🧠 Key Tools & Libraries

- Python (Google Colab)
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## 📁 Portfolio Submission

This repository contains:

- The final Jupyter Notebook: [`students_performance_in_exams.ipynb`](./students_performance_in_exams.ipynb)
- This `README.md` documentation
- Visualizations and model outputs (within the notebook)

---

## 📅 Submission Details

**Student Name** ……………………………………**ID**

- 1.Mengistu Animut…………………………………… 0963
- 2.Mekuanennt Biazin……………………………… 1385
- 3.Mengistu Semahegn……………………………… 0916
- 4.Samuel Erstie .…………………………………… 1644
- 5.Mussie Melese ….………………………………… 1194

**Submission Date:** 10/03/2018 E.C.  
**Project Type:** Data Mining / Machine Learning  
**Platform:** Google Colab + GitHub

---

## 🏁 Conclusion

This project provides a clear example of how data science can be applied to **educational analytics**. By identifying key factors influencing performance, schools and policymakers can make data-driven decisions to improve student outcomes.

---

### 🌟 “Data is the new education — analyze it to empower learning.”
