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

\[
Salary = β₀ + β₁(Age) + β₂(Years\ of\ Experience) + β₃(Education\ Level) + β₄(Gender) + β₅(Job\ Title) + ε
\]

---

### 📌 Explanation of Variables

| Symbol | Description |
|------|-------------|
| Salary | Dependent variable (annual salary) |
| β₀ | Intercept |
| β₁–β₅ | Regression coefficients |
| Age | Employee age |
| Years of Experience | Total work experience |
| Education Level | Highest qualification (coded) |
| Gender | Dummy coded variable |
| Job Title | Coded job role |
| ε | Error term |

---

### 🧮 Coding of Categorical Variables
- Education Level:  
  - 1 = Bachelor’s  
  - 2 = Master’s  
  - 3 = PhD  

- Gender:  
  - 0 = Female  
  - 1 = Male  

- Job Title:  
  - Encoded numerically based on role category

---

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
