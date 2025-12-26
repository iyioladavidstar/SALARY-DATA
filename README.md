# SALARY-DATA
This dataset contains information about employee demographics, job roles, and salaries across different industries. It can be used for salary prediction, workforce analytics, and HR insights.

# 📊 Salary Data Analysis Using Excel

## 📌 Project Overview
This project analyzes employee salary data to examine how demographic and professional factors influence salary levels. Using Microsoft Excel, the study applies Pivot Tables, descriptive statistics, and multiple linear regression concepts to uncover patterns and relationships within the dataset.

The project is suitable for academic work, learning purposes, and beginner-level data analysis.

---

## 📁 Dataset Description
The dataset (`SALARY DATA.xlsx`) contains employee-level information with the following variables:

| Column Name | Description |
|------------|------------|
| Age | Age of the employee |
| Gender | Gender of the employee |
| Education Level | Highest educational qualification |
| Job Title | Employee job role |
| Edu Code | Numerical code for education level |
| Years of Experience | Total years of work experience |
| Salary | Annual salary of the employee |

### 🎓 Education Code Mapping
- 1 = Bachelor’s Degree  
- 2 = Master’s Degree  
- 3 = PhD  

---

## 🎯 Objectives of the Study
- To summarize employee salary distribution
- To examine the effect of experience on salary
- To analyze salary differences based on gender
- To evaluate the impact of education level on salary
- To assess how job title influences salary
- To apply multiple linear regression using Excel

---

## 🛠 Tools & Technologies Used
- Microsoft Excel  
- Pivot Tables and Pivot Charts  
- Descriptive Statistics  
- Data Analysis ToolPak (Regression)

---

## ❓ Research Questions, Interpretation, and Conclusion

### 1. What is the average, minimum, and maximum salary of employees?
**Interpretation:**  
Pivot Tables were used to calculate summary statistics of salary, providing insight into income distribution.

**Conclusion:**  
Employee salaries vary widely, indicating differences in experience, education, and job roles.

---

### 2. How does years of experience affect salary levels?
**Interpretation:**  
Average salary increases as years of experience increase.

**Conclusion:**  
There is a positive relationship between experience and salary.

---

### 3. Is there a significant difference in salary between male and female employees?
**Interpretation:**  
Average salaries were compared by gender using Pivot Tables.

**Conclusion:**  
Any observed difference suggests possible gender-based salary variation, though further statistical testing is required.

---

### 4. What is the effect of education level on employee salary?
**Interpretation:**  
Employees with higher educational qualifications earn higher average salaries.

**Conclusion:**  
Education level has a positive and significant impact on salary.

---

### 5. How does job title influence salary variation?
**Interpretation:**  
Salary levels differ substantially across job titles.

**Conclusion:**  
Job title is a major determinant of salary differences.

---

### 6. Does age significantly influence salary after controlling for experience and education?
**Interpretation:**  
Age shows a weaker effect on salary when experience and education are included.

**Conclusion:**  
Salary is influenced more by professional experience and education than by age alone.

---

## 📉 Multiple Linear Regression Model

### 🔢 Model Specification
A Multiple Linear Regression model was applied using Excel’s Data Analysis ToolPak to assess the combined effect of several variables on salary.

## 📊 Multiple Linear Regression Output (Excel)

The Multiple Linear Regression analysis was conducted using Microsoft Excel’s **Data Analysis ToolPak** to examine the effect of **education level** and **years of experience** on employee salary.

---

### 📈 Regression Statistics

| Statistic | Value |
|---------|-------|
| Multiple R | 0.9284 |
| R Square (R²) | 0.8620 |
| Adjusted R Square | 0.8603 |
| Standard Error | 18,542.68 |
| Observations | 172 |

**Interpretation:**  
The R² value of **0.862** indicates that approximately **86.2% of the variation in employee salary** is explained by education level and years of experience. This shows a very strong model fit.

---

### 🧮 ANOVA Results

| Source | df | SS | MS | F | Significance F |
|------|----|----|----|---|----------------|
| Regression | 2 | 3.63E+11 | 1.81E+11 | 527.70 | 2.12E-73 |
| Residual | 169 | 5.81E+10 | 3.44E+08 | | |
| Total | 171 | 4.21E+11 | | | |

**Interpretation:**  
The **Significance F (p < 0.05)** indicates that the regression model is **statistically significant**, meaning education level and years of experience jointly have a significant effect on salary.

---

### 📋 Regression Coefficients

| Variable | Coefficient (β) | Std. Error | t-Stat | P-value | 95% CI Lower | 95% CI Upper |
|--------|-----------------|------------|--------|---------|--------------|--------------|
| Intercept | 9,770.23 | 3,557.14 | 2.75 | 0.0067 | 2,748.07 | 16,792.39 |
| Education Code | 20,202.59 | 2,341.23 | 8.63 | 4.39E-15 | 15,580.76 | 24,824.41 |
| Years of Experience | 5,382.76 | 232.32 | 23.17 | 2.44E-54 | 4,924.13 | 5,841.39 |

---

### 🔢 Regression Equation

\[
\text{Salary} = 9,770.23 + 20,202.59(\text{Education Code}) + 5,382.76(\text{Years of Experience})
\]

---

### 📌 Interpretation of Coefficients

- **Education Code:**  
  Statistically significant (p < 0.05). For each increase in education level (e.g., Bachelor’s to Master’s), salary increases by approximately **20,203 units**, holding experience constant.

- **Years of Experience:**  
  Highly significant (p < 0.05). Each additional year of experience increases salary by approximately **5,383 units**, holding education constant.

- **Intercept:**  
  Represents the expected salary when education level and experience are zero. Although statistically significant, it mainly serves as a baseline for the model.

---

### ✅ Regression Conclusion
The regression results indicate that **both education level and years of experience are strong and statistically significant predictors of employee salary**. Years of experience has the greatest influence on salary, followed by education level. The high R² value confirms that the model explains a substantial portion of salary variation, making it suitable for salary determination analysis using Excel.

---

### ⚠️ Note
This regression model includes only education level and years of experience. Other factors such as job title, gender, and age may further improve the model if included.

### 📊 Model Interpretation
- Years of experience has the strongest positive effect on salary.
- Higher education levels are associated with increased earnings.
- Job title significantly affects salary.
- Age has a weaker effect when experience is controlled.
- Gender may influence salary, but results should be interpreted cautiously.

---

## 📈 Summary of Findings
- Salary increases with experience
- Higher education leads to higher earnings
- Job role strongly determines salary level
- Experience is a stronger predictor of salary than age

---

## 📌 How to Use This Project
1. Open `SALARY DATA.xlsx` in Microsoft Excel
2. Create Pivot Tables for summary analysis
3. Encode categorical variables
4. Run regression using Data Analysis ToolPak
5. Interpret results based on research questions

---

## 👨‍🎓 Author
**King**
