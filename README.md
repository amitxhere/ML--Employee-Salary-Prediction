# 💼 Salary Prediction Using Machine Learning

## 📌 Project Overview
This project aims to predict employee salaries using various Machine Learning regression algorithms.  
The prediction is based on features such as age, education, experience, job level, and working hours.

Multiple models were trained and evaluated to identify the most suitable algorithm for salary prediction.

---

## 📊 Dataset Description
The dataset contains **5000 records** with the following features:

| Feature Name | Description |
|-------------|------------|
| Age | Age of the employee |
| Education_Years | Years of education |
| Experience_Years | Total years of work experience |
| Job_Level | Job seniority level |
| Hours_Per_Week | Average working hours per week |
| Salary | Annual salary (Target Variable) |

---

## 🔍 Exploratory Data Analysis (EDA)
The following EDA steps were performed:

- Dataset overview and summary statistics
- Correlation analysis using heatmap
- Outlier detection using boxplots and IQR method

### Key Observations:
- Strong correlation between **Experience_Years** and **Salary**
- High multicollinearity observed between **Age** and **Experience**
- Minimal impact of outliers on overall model performance

---

## 🧪 Feature Engineering
- Input features (`X`) and target variable (`y`) were separated
- Train-test split applied (80% training, 20% testing)
- Feature scaling performed using **StandardScaler**

---

## 🤖 Machine Learning Models Used
The following regression models were trained and evaluated:

1. Linear Regression  
2. Ridge Regression  
3. Lasso Regression  
4. K-Nearest Neighbors (KNN)  
5. Support Vector Regression (SVR)  
6. Decision Tree Regression  
7. Random Forest Regression  
8. Gradient Boosting Regression  

---

## 📈 Model Performance Comparison

| Model | R² Score |
|-----|---------|
| Linear Regression | **0.9163** |
| Ridge Regression | 0.9163 |
| Lasso Regression | 0.9162 |
| Gradient Boosting | 0.9129 |
| Random Forest | 0.8949 |
| KNN | 0.8945 |
| Decision Tree | 0.8288 |
| SVR | 0.0316 |

---

## ✅ Results & Insights
- Linear, Ridge, and Lasso Regression achieved the highest R² scores
- Indicates a **strong linear relationship** between features and salary
- Ensemble models performed well but did not outperform linear models
- SVR showed poor performance due to lack of hyperparameter tuning and sensitivity to scaling

---

## 🏆 Final Model Selection
**Linear Regression** was selected as the final model due to:
- Highest accuracy
- Simplicity
- Strong interpretability
- Minimal overfitting

---

## 🧠 Conclusion
The project demonstrates that salary prediction can be effectively achieved using linear models when the data exhibits linear patterns. Ridge and Lasso regression helped confirm that multicollinearity had minimal impact on predictive performance. Overall, Linear Regression proved to be the most efficient and reliable model for this dataset.

---

## 🚀 Future Improvements
- Hyperparameter tuning using GridSearchCV
- Cross-validation
- Model deployment using Streamlit or Flask
- Use of real-world salary datasets

---

## 🛠️ Technologies Used
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- Jupyter Notebook

---


