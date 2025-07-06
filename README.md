# 📊 Palmoria Group HR Analysis (Case Study 3)

This project is based on a case study where I was asked to analyze HR data for Palmoria Group, a manufacturing company in Nigeria. The company is dealing with issues around gender inequality, salary structure, and bonus allocation, and I was brought in as an HR Analytics specialist to provide insights using Power BI.

---

## 🎯 Objective

The goal of this report was to explore and visualize key HR-related metrics such as gender distribution, salary differences, and performance-based bonuses. I also checked if the company meets the newly introduced $90,000 minimum wage regulation.

---

## 🔍 Key Questions Answered

1. What is the gender distribution across departments and regions?
2. How are performance ratings distributed by gender?
3. Is there a gender pay gap? If yes, in which departments or regions?
4. Does Palmoria meet the $90,000 minimum salary requirement?
5. How many employees fall into each salary band (in $10,000 ranges)?
6. How are bonuses calculated and distributed by rating and department?
7. What is the total pay (salary + bonus) per employee, region, and company-wide?

---

## 📌 Data Cleaning & Preparation

- Removed employees with missing salary (as they’ve left the company)
- Removed records with NULL values in the department column
- Removed employees with no gender specified
- Cleaned and unpivoted the bonus rules table to match against `Department` and `Rating`
- Used `LOOKUPVALUE` to calculate bonus rates and total pay per employee

---

## 📊 Power BI Report Highlights

- Bar charts showing salary and bonus by region
- Cards displaying total company-wide bonus and total compensation
- Table showing salary, bonus, and total pay by employee
- Gender analysis visuals by department and region
- Salary band distribution with filters by location and department

---

## 🧰 Tools Used

- Power BI Desktop
- DAX (for calculated columns)
- Power Query (for data cleaning)
- GitHub (to host and document the project)

---

## 📁 Files

- `Palmoria HR Analysis.pbix` – 
- `README.md` – This documentation
- `dashboard.png` ![image](https://github.com/user-attachments/assets/4ad3d50a-81be-4238-b084-856c85b755a5)
![image](https://github.com/user-attachments/assets/e1179eb2-6b3c-42f1-a8b2-dacf478f51a1)


---

## 👤 Author

Muibi Emmanuel  
GitHub: [https://github.com/Emmanuel012-hub](https://github.com/Emmanuel012-hub)

---

## 📝 Notes

- Bonus was calculated using performance rating and department, based on a provided bonus rules table
- The report is fully interactive and can be explored using slicers and filters

---

## 🚀 How to Use

1. Download the `.pbix` file
2. Open with Power BI Desktop
3. Use filters to explore gender, salary, bonus, and rating insights

---

This project helped me sharpen my Power BI skills and approach real-life HR analysis from a data-driven perspective.
