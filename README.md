# Medical Insurance Cost Prediction

This project focuses on predicting **medical insurance charges** using **Machine Learning regression models**.  
The dataset contains demographic and health-related information such as age, BMI, smoking status, and region.

---

## 📌 Project Objectives
- Perform Exploratory Data Analysis (EDA)
- Preprocess data (encoding, standardization, outlier detection)
- Build regression models to predict insurance charges
- Compare model performance
- Explain model predictions using SHAP and LIME

---

## 📊 Dataset Description
The dataset includes 1338 records with the following features:

- **age** – Age of the individual  
- **sex** – Gender (male/female)  
- **bmi** – Body Mass Index  
- **children** – Number of dependents  
- **smoker** – Smoking status (yes/no)  
- **region** – Residential region in the US  
- **charges** – Medical insurance cost (target variable)

---

## 🔍 Exploratory Data Analysis (EDA)
- Column names and data types
- Summary statistics and averages
- Unique values per column
- Missing value and duplicate check
- Outlier detection using boxplots
- Data visualization

---

## ⚙️ Data Preprocessing
- One-Hot Encoding for categorical variables
- Standardization using StandardScaler
- Removal of duplicate rows
- Outlier visualization

---

## 🤖 Models Used
- Linear Regression
- Ridge Regression (L2 Regularization)
- Lasso Regression (L1 Regularization)

---

## 📈 Model Evaluation
- Mean Squared Error (MSE)
- R² Score
- Actual vs Predicted visualization
- Regression line visualization
- Overfitting vs Underfitting analysis

---

## 🧠 Model Explainability
- **SHAP** for global feature importance
- **LIME** for local prediction explanations

---

## 🔮 Sample Prediction
The model can predict insurance charges for a new individual based on input features such as age, BMI, smoking status, etc.

---

## 🛠️ Tools & Libraries
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- SHAP
- LIME

---

## ✅ Conclusion
The Linear Regression model performed best for this dataset, showing good generalization with lower error compared to more complex models. Smoking status and BMI were identified as the most influential factors affecting insurance charges.

---

## 📌 Author
**Ashrif Ahamed**  
Data Science Student

---

## 📎 License
This project is for educational purposes.

