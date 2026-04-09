# 🚀 Employee Management System (EMS)

> 💡 A SQL-powered Employee Management System designed to manage and analyze employee data.

## ✨ Highlights

* Built 6 relational tables
* Implemented Primary & Foreign Keys
* Created analytical SQL queries
* Covers complete employee lifecycle
* Designed for real-world HR use cases

---

## 📦 Core Modules

| Module        | Description              |
| ------------- | ------------------------ |
| Employee      | Personal & login details |
| JobDepartment | Roles & departments      |
| SalaryBonus   | Salary & bonus structure |
| Qualification | Skills & education       |
| Leaves        | Leave tracking           |
| Payroll       | Salary transactions      |

---

## 🗄️ Database Tables

### Employee

| Column      |
| ----------- |
| emp_ID      |
| firstname   |
| lastname    |
| gender      |
| age         |
| contact_add |
| emp_email   |
| emp_pass    |
| Job_ID      |

---

### JobDepartment

| Column      |
| ----------- |
| Job_ID      |
| jobdept     |
| name        |
| description |
| salaryrange |

---

### SalaryBonus

| Column    |
| --------- |
| salary_ID |
| Job_ID    |
| amount    |
| annual    |
| bonus     |

---

### Qualification

| Column       |
| ------------ |
| QualID       |
| Emp_ID       |
| Position     |
| Requirements |
| Date_In      |

---

### Leaves

| Column   |
| -------- |
| leave_ID |
| emp_ID   |
| date     |
| reason   |

---

### Payroll

| Column       |
| ------------ |
| payroll_ID   |
| emp_ID       |
| job_ID       |
| salary_ID    |
| leave_ID     |
| date         |
| report       |
| total_amount |

---

## 📊 SQL Analysis

### Employee Insights

| Insights                      |
| ----------------------------- |
| Total employees               |
| Department-wise distribution  |
| Average salary per department |
| Top 5 highest-paid employees  |
| Total salary expenditure      |

---

### Department Analysis

| Insights             |
| -------------------- |
| Roles per department |
| Average salary       |
| Highest salary roles |
| Salary distribution  |

---

### Qualification Analysis

| Insights                      |
| ----------------------------- |
| Employees with qualifications |
| Most common qualifications    |
| Highest qualification holders |

---

### Leave Analysis

| Insights                      |
| ----------------------------- |
| Leave trends                  |
| Average leaves per department |
| Highest leaves                |
| Total leaves taken            |

---

### Payroll Analysis

| Insights           |
| ------------------ |
| Monthly payroll    |
| Bonus distribution |
| Highest bonus      |
| Average salary     |

---

## ⚙️ Tech Stack

| Tool  | Purpose       |
| ----- | ------------- |
| MySQL | Database      |
| SQL   | Querying      |
| RDBMS | Data modeling |

---

## 📂 Project Structure

```
Employee-Management-System/
├── EMSproject.sql
├── EMS-ER.pdf
└── README.md
```

---

## 💡 Skills

* SQL Query Writing
* Database Design
* Data Analysis
* Relational Modeling
* Business Insights

---

## 🚀 Future Improvements

* Power BI Dashboard
* Web Interface
* Performance Analytics
* Stored Procedures & Triggers

---

## 👩‍💻 Author

Jeevana
Data Analyst
SQL | Python | Power BI

---

## ⭐ Support

Star the repository if you like this project
