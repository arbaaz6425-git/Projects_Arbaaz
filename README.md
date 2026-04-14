#Projects_Arbaaz
Job Salary Prediction Using Regression
# Job Salary Prediction Using Regression
A machine learning project predicting employee salaries using Linear Regression on a 250K-row dataset.

**Course:** Fundamentals of Machine Learning | BBA AI & DS, Semester 4 — IBS Hyderabad

---

##Objectives
- Analyze relationship between job-related factors and salary
- Build a Linear Regression model using Scikit-learn
- Evaluate model using MAE, MSE, RMSE, and R² Score

---

##Dataset
- **Source:** Kaggle (open-source)
- **Size:** 2,50,000 rows × 10 columns
- **Target Variable:** `salary` (annual compensation)
- **Key Features:** `experience_years`, `education_level`, `skills_count`, `industry`, `company_size`, `location`, `remote_work`, `certifications`

---

## Tech Stack
`Python` `Pandas` `NumPy` `Scikit-learn` `Matplotlib` `Seaborn`

---

## 🔄 Workflow
1. Import libraries & load dataset
2. Data preprocessing — duplicate removal, null handling (mean imputation)
3. Feature selection → `X = experience_years`, `y = salary`
4. Train-Test Split (70/30)
5. Train Linear Regression model
6. Predict & evaluate performance
7. Visualize regression line on scatter plot

---

## 📊 Results
| Metric | Value |
|--------|-------|
| Intercept (b₀) | 118,633.22 |
| Coefficient (b₁) | 2,703.32 |

> **Equation:** `Salary = 118633.22 + 2703.32 × Experience_Years`

---

## 🚀 How to Run
```bash
git clone https://github.com/arbaaz6425-git/job-salary-prediction.git
pip install pandas numpy matplotlib seaborn scikit-learn
jupyter notebook Salary_Prediction_project_Codes.ipynb
```

---

## Author
**Arbaaz Ahmed Ansari** — [LinkedIn](https://linkedin.com/in/arbaaz-ahmed-ansari) | arbaazahmed112005@gmail.com
