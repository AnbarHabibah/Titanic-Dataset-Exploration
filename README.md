# **Titanic-Dataset-Exploration**
Exploratory Data Analysis (EDA) and machine learning modeling on the Titanic dataset to uncover survival patterns based on demographics and social status.

### **Titanic Data Analysis**
This project involves an in-depth exploration of the Titanic passenger dataset to uncover key survival patterns and build machine learning models for classification. The dataset is curated from [Frank Harrell’s Hmisc Titanic Dataset](https://hbiostat.org/data/repo/titanic.html) and focuses on variables like passenger `name`, `sex`, `age`, and survival status.

---

### 🔍 Dataset Overview
Total Records: 500 rows
Key Columns: `name`, `sex`, `age`, `survived`
Missing Values: 9.82% in `age`
Feature Engineering: Added `title` and `age_group` columns

---

### **💡 Project Overview**
The notebook walks through:
 - Loading and cleaning the Titanic dataset
 - Handling missing values and duplicate entries
 - Feature engineering (e.g., title extraction, age grouping)
 - Exploratory Data Analysis (EDA)
 - Training and comparing multiple ML models

---
### **📦 Machine Learning Models Used**
- Logistic Regression
- Decision Tree
- Random Forest
- XGBoost
- K-Nearest Neighbors (KNN)
- Support Vector Machine (SVM)

---

### **🔎 Insights:**
1. Women had higher survival rates due to "Women and Children First" policies.
2. Children under 10, especially toddlers, had the highest survival chances.
3. Adult males (title: "Mr") had the lowest survival rate.
4. Social titles (e.g., "Lady", "Countess") correlate strongly with survival likelihood.
5. Support Vector Machine (SVM) performed best across evaluation metrics.

---

### **📊 Modeling Summary**
✅ Best Performing Model

Support Vector Machine (SVM) demonstrated the best overall performance in classifying survival outcomes based on demographic and title features.

🧠 Model Selection Rationale
- High accuracy, precision, recall, and F1-score
- Effective at handling complex boundaries in feature space
- Performs well on smaller, well-engineered datasets
  
---

### **🛠️ Tools & Libraries**
- Python 3.x
- Pandas & NumPy
- Scikit-learn
- XGBoost
- Seaborn & Matplotlib
- Jupyter Notebook

---

### **📌 What I Learned**
1. How to prepare and clean real-world datasets.
2. The strengths and differences between various ML algorithms.
3. How to apply cross-validation for more reliable model evaluation.
4. Building a full machine learning pipeline from data to insights.
   
---

### **🚀 Next Steps**
- Add feature engineering to enrich input data
- Improve model interpretability with visual tools like SHAP
- Deploy the best model using a web interface (e.g., Streamlit or Flask)

---

If you have any suggestions or feedback, feel free to reach out:

📧 anbarhabibah2@gmail.com  
🔗 [LinkedIn – Anbar Habibah](https://www.linkedin.com/in/anbarhabibah)

#Python #BeginnerProject #PythonProgramming #LearningPython #DataScienceBeginner #DataScience
#DataScience #Titanic #MachineLearning #EDA #SVM
#LogisticRegression #DataExploration #XGBoost #RandomForest  #MLModels
