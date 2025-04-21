# **Titanic-Dataset-Exploration**
Exploratory Data Analysis (EDA) and machine learning modeling on the Titanic dataset to uncover survival patterns based on demographics and social status.

### **Titanic Data Analysis**
This project involves an in-depth exploration of the Titanic passenger dataset to uncover key survival patterns and build machine learning models for classification. The dataset is curated from [Frank Harrell’s Hmisc Titanic Dataset](https://hbiostat.org/data/repo/titanic.html) and focuses on variables like passenger `name`, `sex`, `age`, and survival status.

Key steps include:
 - Data cleaning and preprocessing
 - Feature engineering (e.g., title extraction, age grouping)
 - Exploratory Data Analysis (EDA) using visualization
 - Model building using Logistic Regression and Support Vector Machine (SVM)
 - Model evaluation using accuracy, precision, recall, and F1-Score

---

### 🔍 Dataset Overview
Total Records: 500 rows
Key Columns: `name`, s`ex`, `age`, `survived`
Missing Values: 9.82% in `age`
Feature Engineering: Added `title` and `age_group` columns

#### **🔎 Insights:**
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

## **💡 Recommendations for Future Development**
1. Add features like `fare`, `embarked`, or `pclass` for better predictions.
2. Visualize decision boundaries of SVM using 2D projection.
3. Create a web-based interactive survival predictor using Streamlit or Flask.

---

## **Version Libraries**
- pandas v1.5.3
- numpy v1.22.4
- seaborn v0.12.2
- matplotlib v3.7.1
- scikit-learn v1.2.2
- plotly v5.14.1
- missingno v0.5.2

---

If you have any suggestions or feedback, feel free to reach out:

📧 anbarhabibah2@gmail.com  
🔗 [LinkedIn – Anbar Habibah](https://www.linkedin.com/in/anbarhabibah)

#Python #BeginnerProject #PythonProgramming #LearningPython #DataScienceBeginner #DataScience
#DataScience #Titanic #MachineLearning #EDA #SVM
#LogisticRegression #DataExploration
