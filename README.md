# 🌟 Employee Data Analysis Portfolio  

Hi there! 👋 Welcome to my portfolio, where I showcase how I’ve used data analysis and machine learning to uncover actionable insights about employee retention and attrition. Let’s dive in! 🚀  

---

## 📚 Overview  

This project is all about analyzing employee data 🧑‍💻 sourced from Kaggle to answer key questions like:  
1. How many employees of each education degree have left the company, and how many have stayed?
2. How many employees were recruited each year?
3. What is the average age of employees for each education degree?
4. What is the average years of experience for employees of each education degree?
5. Which education degree is most commonly associated with employees being benched?
6. Display the payment tiers for employees who were benched.
7. Which Column Has the Highest Correlation in Predicting Whether an Employee Will Leave?

The dataset includes **9 columns** filled with information on demographics, education, work experience, and more.  

---

## 🔍 Steps I Took  

### 1️⃣ Data Gathering  
- **Source**: [Kaggle🏆](https://www.kaggle.com/datasets/tawfikelmetwally/employee-dataset)
- **Format**: CSV 📂  
- **Contents**: Employee age, education, joining year, work history, and more.  

### 2️⃣ Data Wrangling  
To clean and prep the dataset for analysis, I:  
- Removed duplicate entries 🗑️  
- Handled missing values 🔄  
- Reformatted data for consistency 🔧  
- Identified and dealt with outliers 🔍  

### 3️⃣ Exploratory Data Analysis (EDA)  
Using **line charts**, **bar charts**, and **tables**, I explored:  
- Trends in attrition 📉  
- Tenure and experience ⏳  
- Education and benching patterns 🎓  

### 4️⃣ Correlation Analysis  
I studied the relationships between variables using:  
- **Point Biserial Correlation**: Nominal vs. numerical 🔢  
- **Chi-Square Test and Cramér's V**: Nominal vs. nominal 🔗  
- **Kendall Tau**: Nominal vs. ordinal ⬆️⬇️  

# Insights and Recommendations

## 💡 Insights

### Employee Retention and Attrition by Education Level 🎓  
- Most employees have a Bachelor's degree, including 1,232 who stayed and 739 who left, making this the largest group in the workforce.  
- Master's degree holders have a balanced retention rate (328 stayed, 309 left), showing some challenges in keeping this group.  
- Ph.D. holders are the smallest group but have the highest retention rate (116 stayed, 40 left).    

### Experience Analysis ⏳  
- Employees with Bachelor's degrees have the longest tenure, with a maximum of 7 years of experience, followed by Master's and Ph.D. holders (5 years each).  
- Many employees, especially Bachelor's degree holders (239), have no prior experience, likely due to entry-level hiring or mismatched roles.  

### Attrition and Experience 🚪  
- Employees who left the company had between 0 and 7 years of experience, meaning attrition occurs across the entire range of tenure for all education levels.  
- For employees with over 3 years of experience, Bachelor's degree holders form the majority of those leaving (208), followed by Master's degree holders (113) and Ph.D. holders (11).  
- This suggests that experienced employees may leave due to unmet career goals or better opportunities elsewhere.   

### Bench Analysis 🪑  
- Bachelor's degree holders have the highest number of benched employees (286), potentially due to over-hiring or misallocation of roles.  
- Most benched employees belong to Payment Tier 3, followed by Tier 2 and Tier 1, which could indicate inefficiencies in managing lower-tier employees.  

---

## 🌟 Recommendations  

### 1️⃣ Improve Retention Strategies for Master's Degree Holders 🎓  
- Conduct **exit interviews** and **satisfaction surveys** to identify reasons for attrition among Master's degree holders.  
- Offer tailored growth opportunities, such as **leadership training** or **advanced technical skills**, to better engage and retain them.  

### 2️⃣ Address Domain Experience Gaps 🧠  
- Provide **structured onboarding** and **training programs** to upskill employees with no prior domain experience, particularly among Bachelor's degree holders.  
- Develop **mentorship programs** where experienced employees guide newcomers.  

### 3️⃣ Targeted Retention for Experienced Employees 💼  
- Introduce incentives like **promotions**, **salary increases**, and **career development plans** for employees with more than 3 years of experience.  
- Foster a strong **organizational culture** to encourage long-term commitment.  

### 4️⃣ Optimize Bench Management 🛠️  
- Reevaluate **hiring practices** to prevent over-hiring, especially for roles requiring Bachelor's degrees.  
- Assign benched employees to **short-term projects**, **cross-training opportunities**, or **skill development programs** to enhance their utilization.  

### 5️⃣ Payment Tier Utilization Strategy 💰  
- Investigate the reasons for higher benching in **Payment Tier 3** and focus on aligning hiring with actual workforce needs.  
- Create pathways for employees in **lower tiers** to advance through internal training and certification programs, reducing benching rates.  

---

## 📊 Recap of Correlation Summary with LeaveOrNot Column

- **Age**: Weak positive correlation (0.114943) — Older employees are slightly more likely to leave.  
- **ExperienceInCurrentDomain**: Very weak positive correlation (0.021181) — Little to no impact on leaving.  
- **JoiningYear**: Weak negative correlation (-0.150650) — Employees who joined earlier are marginally less likely to leave.  

### Categorical Variables:
- **City and Gender**: Statistically significant relationships with LeaveOrNot (*p-value* < 0.05) but weak to moderate associations (*Cramér's V* < 0.3).  
- **EverBenched**: No significant relationship (*p-value* > 0.05) and negligible association (*Cramér's V* = 0.036).  

### Other Factors:
- **Education**: Weak negative correlation — Higher education levels slightly reduce the likelihood of leaving.  
- **PaymentTier**: Weak positive correlation — Higher payment tiers are slightly associated with an increased likelihood of leaving.  

---

## 🛠️ Tools and Technologies  

- **Python**: Pandas, NumPy, Scikit-learn 🐍  
- **Jupyter Notebook**: For interactive exploration 📓  
- **Kaggle**: Data source 🎯  

---
