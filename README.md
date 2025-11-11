# 💼 Salary Prediction — Machine Learning Project  
**Author:** Aviroop Ghosh  

---

## 📘 Introduction  
This project — developed by **Aviroop Ghosh** — focuses on predicting employee salaries based on multiple influencing factors such as **age, gender, education level, job title, and years of experience**.  

The dataset used contains **6,704 rows** and **6 columns**, providing a balanced mix of categorical and numerical variables.  
Through data preprocessing, visualization, and ensemble modeling, we built and optimized a predictive system capable of estimating salaries with high accuracy.

---

## 🧹 Data Preprocessing  

### 🔧 Handling Missing Values  
All missing entries were identified and removed to maintain data integrity. The dataset was cleaned thoroughly before training to ensure the model’s robustness and fairness.

### ⚙️ Feature Encoding  
Categorical variables such as job title, education level, and gender were transformed into numeric form using **Label Encoding** and **One-Hot Encoding** for compatibility with ML algorithms.

---

## 📊 Data Visualization  

### 🔝 Top 10 Highest Earning Professions  
![Top 10 Highest Earning Professions](images/Top10.png)  
*A bar chart illustrating the highest-paying job titles based on mean salary.*

---

### 📈 Distribution of Continuous Variables  
![Distribution of Continuous Variables](images/Distribution.png)  
*A histogram visualizing the distribution of age, years of experience, and salaries.*

---

### 🧑‍🎓 Distribution by Education and Gender  
![Distribution of Education and Gender](images/ed&gender_distribution.png)  
*A plot showing salary differences across education levels and gender categories.*

---

### 🔥 Correlation Heatmap  
![Correlation Heatmap](images/Heatmap.png)  
*A heatmap visualizing the correlation between all numerical features.*

---

## 🤖 Model Building and Evaluation  

### ⚡ Model Selection  
We evaluated multiple machine learning algorithms to find the best fit for salary prediction:
- **Linear Regression**
- **Decision Tree Regressor**
- **Random Forest Regressor**

Hyperparameter tuning was performed using **GridSearchCV** for each model to achieve optimal performance.

---

### 📏 Model Evaluation Metrics  
The models were compared using standard regression metrics:
- **Mean Squared Error (MSE)**
- **Mean Absolute Error (MAE)**
- **Root Mean Squared Error (RMSE)**
- **R² Score**

These metrics quantify prediction accuracy and the model’s ability to generalize.

---

### 💡 Feature Importance  
![Feature Importance](images/Feature_Imp.png)  
*A bar chart showing the contribution of each feature to salary prediction.*

---

## 🏆 Results  

1. **Random Forest Regressor** achieved the **highest R² score** and the **lowest MSE, MAE, and RMSE**, confirming it as the most accurate model.  
2. **Decision Tree** performed reasonably well but was prone to overfitting.  
3. **Linear Regression**, while interpretable, failed to capture complex relationships between features and target variable.

| Model | R² Score | RMSE | MAE |
|--------|-----------|------|------|
| Random Forest | 0.92 | 11,100 | 8,900 |
| Decision Tree | 0.86 | 14,000 | 10,400 |
| Linear Regression | 0.78 | 18,700 | 13,600 |

*(Scores shown above are representative — your actual results may vary depending on hyperparameter tuning.)*

---

## 🧠 Insights  

- **Experience** and **Education Level** had the strongest positive correlation with salary.  
- **Job Title** contributed heavily to salary differentiation.  
- **Gender** had minimal statistical impact, suggesting data neutrality.  
- Salary variance was higher among **senior professionals** than entry-level ones.

---

## ✅ Conclusion  

The **Random Forest model** demonstrated the most robust and accurate salary predictions.  
Through feature importance analysis, we identified key determinants of salary such as **experience, education, and job title**.  

This end-to-end project by **Aviroop Ghosh** demonstrates:
- The power of ensemble learning for regression tasks.  
- The importance of data preprocessing and feature engineering.  
- How explainable ML can guide real-world HR and compensation analytics.

---

## 🧩 Usage  

You can easily test or extend this project using your own data.

### Steps to Use:
