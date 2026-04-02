# 👥 What Drives Employee Attrition?

### A People & Operations Analytics Study (Capgemini Case)  
### Ricardo Padilla Herrera  

---

## 🎯 Objective  

What factors drive employee attrition, and how can organizations reduce turnover?

Employee attrition is a critical challenge for organizations, impacting productivity, costs, and team stability. This analysis investigates whether attrition is driven by demographic factors or by working conditions, with the goal of identifying the key drivers of employee turnover.

The objective is to provide **data-driven insights to support HR decision-making** and reduce attrition risk.

---

## 🗃️ Dataset  

Employee dataset (HR analytics data)

| Field | Description |
|------|------------|
| Attrition_flag | Employee turnover (1 = left, 0 = stayed) |
| Gender | Employee gender |
| YearsAtCompany | Tenure in years |
| YearsSinceLastPromotion | Time since last promotion |
| MonthlyIncome | Salary level |
| JobLevel | Seniority level |
| OverTime | Overtime status |

**Structure:**  
- Unit of analysis: employee level  
- Binary target variable: attrition  
- Combination of demographic and job-related variables  

---

## 🧠 Analytical Focus  

The analysis evaluates whether attrition is driven by:

- Demographic characteristics (e.g. gender)  
- Career progression (tenure, promotions, income)  
- Working conditions (overtime, workload)  

---

## 🔬 Methods  

- Exploratory Data Analysis (EDA)  
- Hypothesis testing (Chi-square tests)  
- Mean comparison tests (t-tests)  
- Feature analysis  
- Clustering (PCA + KMeans)  
- Predictive modeling (Decision Tree Classifier)  

---

## 📊 Analytical Approach  

- Tested statistical relationships between variables and attrition  
- Compared leavers vs stayers across key features  
- Identified significant vs non-significant drivers  
- Built predictive model to classify attrition risk  

---

## 🔑 Key Findings  

- **Gender is not a significant driver of attrition** (p = 0.185)  
- **Overtime is a major driver of attrition**  
  - 30.1% attrition rate (overtime) vs 10.9% (no overtime)  
- Employees with:
  - Lower income  
  - Longer time since last promotion  
  - Lower job level  
  show higher attrition risk  

👉 Key insight:  
Attrition is primarily driven by **working conditions and career stagnation**, not demographic factors.

---

## 💡 Recommendations  

**1. Reduce Overtime Dependency**  
- Monitor and limit excessive overtime  
- Improve workload distribution  

**2. Improve Career Progression**  
- Shorten promotion cycles  
- Create clearer career paths  

**3. Review Compensation Structure**  
- Ensure competitive salary progression  
- Target at-risk employee segments  

**4. Implement Attrition Monitoring**  
- Use predictive models to identify high-risk employees  
- Enable proactive HR interventions  

---

## ⚠️ Limitations  

- Observational dataset (no causal inference)  
- Potential missing variables (e.g. job satisfaction, manager quality)  
- Static dataset (no time-series dynamics)  

---

## 🚀 Business Impact  

This project demonstrates how People Analytics can:

- Identify the true drivers of employee turnover  
- Challenge incorrect managerial assumptions  
- Support targeted HR strategies to reduce attrition  

---

## 🛠️ Tools & Technologies  

- Python (pandas, numpy)  
- seaborn / matplotlib  
- scikit-learn (KMeans, Decision Tree)  
- Statistical testing (chi-square, t-tests)  

---

## 📌 Key Takeaway  

Employee attrition is not driven by who employees are —  
it is driven by how they are managed.

Overtime and lack of career progression are the strongest predictors of turnover.
