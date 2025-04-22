# **Titanic-Survival-Prediction**
This project focuses on predicting the survival of Titanic passengers using machine learning techniques. It explores key survival patterns based on demographic attributes and social status through comprehensive Exploratory Data Analysis (EDA) and model development.

### **Titanic Data Analysis**
This project involves an in‑depth exploration of the Titanic passenger dataset to uncover key survival patterns and build machine learning models for classification. 

---

### **📂 Dataset**
The dataset has been uploaded to this repository (see [titanic.xls](titanic.xlsx)).

---

### **🔍 Dataset Overview**
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
5. Logistic Regression showed competitive performance across multiple metrics, providing a solid balance of interpretability and accuracy.

---

### **📊 Modeling Summary**
✅ Best Performing Model

Logistic Regression was identified as the best-performing model due to its consistent performance across accuracy, precision, recall, and F1-score. While all models performed similarly, Logistic Regression provides the added advantage of interpretability and ease of explanation, making it the ideal choice for this classification task.

🧠 Model Selection Rationale
- High accuracy, precision, recall, and F1-score
- Effective at handling complex boundaries in feature space
- Performs well on smaller, well-engineered datasets.
- Fast to train and doesn’t require intensive parameter tuning.
- Still capable of identifying important features such as `sex`, `title`, and `age_group`.
  
---

### **🛠️ Tools & Libraries**
- Python
- Pandas & NumPy
- Scikit-learn
- XGBoost
- Seaborn & Matplotlib

---

### **📌 What I Learned**
1. How to prepare and clean real-world datasets.
2. The strengths and differences between various ML algorithms.
3. How to apply cross-validation for more reliable model evaluation.
4. Building a full machine learning pipeline from data to insights.
   
---

### **🚀 Next Steps**
- Continue to explore additional features that could improve model performance.
- Improve model interpretability with visual tools
- Deploy the best model using a web interface (e.g., Streamlit or Flask)

---

### **📧 Contact & Collaboration**
If you have any suggestions or feedback, feel free to reach out:

📧 anbarhabibah2@gmail.com  
🔗 [LinkedIn – Anbar Habibah](https://www.linkedin.com/in/anbarhabibah)

---

#Python #BeginnerProject #PythonProgramming #LearningPython #DataScienceBeginner #DataScience #Titanic #MachineLearning #EDA #SVM #LogisticRegression #DataExploration #XGBoost #RandomForest #MLModels
