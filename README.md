# 🧠 Bio-Signal Analysis for Smoking Detection

This project builds a machine learning model to predict the presence or absence of smoking in individuals using biological health signals. The project includes data preprocessing, visualization, feature selection, and implementation of multiple machine learning algorithms.

---

## 📁 Dataset Information

- **Records:** ~55,000
- **Attributes:** 27 health-related features including:
  - Demographics: Gender, Age
  - Vitals: Height, Weight, Waist, BP
  - Sensory: Eyesight, Hearing
  - Blood Tests: Hemoglobin, Cholesterol, Glucose, Creatinine
  - Medical: Dental issues, Urine protein, Tartar
  - **Target variable:** `smoking` (0 = No, 1 = Yes)

---

## 🔍 Steps Performed

1. **Importing Libraries**
2. **Loading the Data**
   - Dropping irrelevant columns
   - Understanding data structure
3. **Missing Value Analysis**
4. **Data Visualization**
   - Age distribution, gender correlation, outlier detection
5. **Data Cleaning**
   - One-Hot Encoding of categorical features
6. **Feature Selection**
   - Using feature importance to select top 15 features
7. **Model Building**
   - Logistic Regression
   - Decision Tree
   - Bagging: Random Forest

---

## 📊 Key Visualizations

- Gender-wise smoking distribution
- Age-wise smoker trends
- Boxplots to detect and retain true outliers
- Smoking rate: **36.73%** in dataset
- Most smokers are around age **40**


---

## 🛠️ Tools & Technologies

- Python
- Jupyter Notebook
- NumPy, Pandas
- Matplotlib, Seaborn
- Scikit-learn



