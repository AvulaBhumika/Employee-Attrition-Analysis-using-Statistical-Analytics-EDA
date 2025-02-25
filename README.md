# Employee Attrition Analysis using Statistical Analytics & EDA

## 📌 Project Overview
Employee attrition is a critical concern for organizations aiming to improve workforce retention. This project explores **employee attrition trends** using **Exploratory Data Analysis (EDA) and Statistical Analytics** to uncover key patterns and insights.

We analyze employee demographic, job satisfaction, compensation, and performance data to identify the major factors contributing to attrition. The study incorporates visualizations and statistical tests to ensure data-driven conclusions.

---

## 📊 Dataset Description
The dataset consists of employee records with 35 columns, including demographic, job-related, and performance-related factors.

### **Key Features:**
- **Demographics:** `Age`, `Gender`, `MaritalStatus`
- **Job Satisfaction & Performance:** `JobSatisfaction`, `JobInvolvement`, `PerformanceRating`, `WorkLifeBalance`
- **Compensation:** `MonthlyIncome`, `StockOptionLevel`, `PercentSalaryHike`
- **Work Environment:** `DistanceFromHome`, `EnvironmentSatisfaction`, `BusinessTravel`
- **Career Progression:** `YearsAtCompany`, `YearsInCurrentRole`, `YearsSinceLastPromotion`
- **Attrition Target Variable:** `Attrition` (Yes/No)

---

## 🎯 Objectives
1. **Understand Attrition Trends** – Identify patterns in employee turnover using data exploration.
2. **Perform Statistical Analysis** – Use hypothesis testing to validate findings.
3. **Provide Data-Driven Insights** – Interpret results to inform HR policies.

---

## 📈 Exploratory Data Analysis (EDA)
We use **Seaborn & Matplotlib** to visualize trends in attrition and other key factors:
- **Univariate Analysis:** Distribution plots for age, income, job satisfaction, etc.
- **Bivariate Analysis:** Relationship between attrition and key features (e.g., Monthly Income vs. Attrition)
- **Categorical Analysis:** Impact of factors like business travel, gender, and job role on attrition.
- **Correlation Matrix & Heatmap:** Identifies multicollinearity among features.

---

## 📊 Statistical Tests Used & Justification
We apply statistical tests to validate insights from EDA and ensure the findings are **not due to random chance**.

### **1️⃣ Chi-Square Test for Independence** (Categorical vs. Categorical)
- **Why?** To check if two categorical variables (e.g., Attrition & BusinessTravel) are related.
- **Example:** Is attrition dependent on business travel frequency?
- **Interpretation:** If p-value < 0.05, there is a significant relationship.

### **2️⃣ T-Test** (Numerical vs. Categorical)
- **Why?** To compare the means of numerical variables (e.g., Monthly Income) between attrition groups.
- **Example:** Do employees who left have significantly lower salaries than those who stayed?
- **Interpretation:** If p-value < 0.05, there is a significant difference.

### **4️⃣ Correlation Analysis**
- **Why?** To measure relationships between numerical variables.
- **Example:** How does job satisfaction correlate with attrition?
- **Interpretation:** High correlation suggests strong relationships between factors.

---

## 📌 Key Insights & Findings
🔹 **Salary & Attrition:** Employees with lower monthly income tend to leave more frequently.
🔹 **Work-Life Balance:** Poor work-life balance strongly correlates with higher attrition.
🔹 **Business Travel Impact:** Employees who frequently travel are more likely to leave.
🔹 **Job Role Differences:** Sales roles show higher attrition than technical roles.
🔹 **Years at Company:** Higher attrition observed in employees with less than 3 years in the company.

---

## 🛠️ Tools & Libraries Used
- **Python**: Pandas, NumPy, Seaborn, Matplotlib, SciPy, Statsmodels
- **Statistical Tests**: Chi-Square, T-Test, ANOVA, Correlation Analysis
- **Visualization Tools**: Heatmaps, Boxplots, Pairplots, Countplots

---

## 💡 Conclusion
This study highlights key factors influencing employee attrition using EDA and statistical analysis. HR teams can leverage these insights to **improve retention strategies**, optimize compensation policies, and enhance employee satisfaction.

📢 **Future Scope:**
✔️ Implement **Predictive Modeling** using Logistic Regression, Random Forest, or XGBoost.
✔️ Explore **Sentiment Analysis** on employee feedback data.

---


