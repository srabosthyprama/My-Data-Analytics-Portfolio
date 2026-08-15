# HR Employee Attrition Analysis

## 📌 Project Overview

This Power BI project analyzes employee attrition and identifies the employee groups and workplace factors linked with higher attrition.

The dashboard helps HR teams understand **who is leaving, where attrition is higher, and which factors may need attention.**

---

## 🗂️ Data Model

<img width="1353" height="678" alt="Screenshot 2026-08-15 145801" src="https://github.com/user-attachments/assets/8029c2e2-e3c0-4da7-be8f-7cab181a9611" />

The data model uses **HR_Data** as the main employee table, connected to three lookup tables:

- **Departments_Lookup** — Department information
- **Education_Lookup** — Education information
- **Jobs_Lookup** — Job role information

The lookup tables are connected to `HR_Data` through their respective IDs, creating a simple **star-schema style model** for analysis and reporting.

---

## 📊 Dashboard Preview

### 1. Overview

<img width="1558" height="834" alt="Screenshot 2026-08-15 145607" src="https://github.com/user-attachments/assets/9d53bbab-959e-4306-bd5f-4d33b5bef86d" />

### 2. Employee Profile

<img width="1557" height="822" alt="Screenshot 2026-08-15 145624" src="https://github.com/user-attachments/assets/704476c7-620b-4932-b002-a3bedc90c4ab" />

### 3. Attrition Factors

<img width="1552" height="829" alt="Screenshot 2026-08-15 145638" src="https://github.com/user-attachments/assets/fe753996-93db-4589-bf37-a17c0cca236c" />

---

## 🔍 Key Insights

### 1. Overall Attrition

- The dataset contains **1,470 employees**, with **238 attritions**.
- Overall attrition rate is **16.19%**.
- **Sales** has the highest department-level attrition rate at **20.85%**, followed by Human Resources at **19.05%**.

### 2. Younger Employees Show Higher Attrition

- Employees aged **18–25** have the highest attrition rate at **35.77%**.
- Entry-level employees also show the highest attrition rate among job levels at **26.34%**.
- This suggests that **younger and early-career employees need more attention from HR**.

### 3. Attrited Employees Have Lower Average Income and Experience

Compared with active employees:

- Average income: **4.81K vs 6.83K**
- Average age: **34 vs 38**
- Average tenure: **5 vs 7 years**

This shows that employees who leave tend to be **younger, lower-paid, and have fewer years with the company**.

### 4. Job Involvement Is Linked with Attrition

- Employees with **Low Job Involvement** have an attrition rate of **33.73%**.
- The rate falls to **9.03%** for employees with Very High Job Involvement.

This indicates that employee engagement and involvement deserve attention.

### 5. Salary Level and Attrition

- Employees in the **Up to 5K** salary slab have the highest attrition rate at **21.76%**.
- Attrition falls to only **3.76%** for employees in the **15K+** salary slab.

Lower-paid employees appear to be a higher-risk group for attrition.

### 6. Overtime and Salary Hike

- Employees who work overtime and received an **Exceptional Salary Increase** have the highest observed attrition rate at **47.83%**.
- Even with a higher salary increase, overtime employees still show a much higher overall attrition rate (**30.77%**) compared with employees who do not work overtime (**10.44%**).

This suggests that **pay increases alone may not fully address the retention risk linked with overtime**.

### 7. Early Company Experience

- **New Employees** have the highest attrition rate at **34.88%**.
- Attrition gradually falls among more experienced employee groups.

This makes the **early stage of an employee's journey** an important area for retention efforts.

### 8. Job Satisfaction Varies by Role

- Low job satisfaction is linked with higher attrition across several roles.
- For example, Research Scientists show **26.27%** attrition at Low Satisfaction compared with **12.73%** at Very High Satisfaction.
- Laboratory Technicians also show higher attrition at Low Satisfaction (**25.00%**).

This suggests that satisfaction should be monitored at the **job-role level**, rather than looking at all employees in the same way.

### 9. Business Travel

- Employees who travel frequently have the highest travel-related attrition rate at **24.91%**.
- Non-travel employees have a much lower rate of **8.00%**.

Frequent travel may be an area worth reviewing, especially in departments where the rate is higher.

---

## 💡 Recommendations

1. **Focus on early-career employees**  
   Introduce stronger onboarding, mentoring, regular check-ins, and career guidance for new and entry-level employees.

2. **Review overtime practices**  
   Monitor overtime workload and scheduling. Higher pay increases may not be enough if employees continue to face heavy workloads.

3. **Improve employee involvement**  
   Give employees clearer responsibilities, regular feedback, training opportunities, and more recognition to improve engagement.

4. **Review lower salary groups**  
   Evaluate starting salaries and salary growth opportunities for employees in the lower salary slabs.

5. **Monitor job satisfaction by role**  
   Identify roles with lower satisfaction and use employee feedback to understand what needs to improve.

6. **Review frequent business travel**  
   Check travel schedules, workload, and flexibility for employees who travel frequently.

---

## 🛠️ Tools Used

- **Power BI**
- **Power Query**
- **DAX**
- **Data Modeling**
- **Data Visualization**

---

## 🎯 Key Takeaway

The analysis shows that attrition is more common among **younger, early-career, lower-paid, less-involved, and overtime-working employees**.  

HR can reduce retention risk by focusing on **early employee support, workload management, employee involvement, career growth, and fair compensation**.
