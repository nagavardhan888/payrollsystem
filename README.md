# Payroll Management System (Python GUI)

A simple and user-friendly **Payroll Management System** built using **Python **.
This application allows users to manage employee records, calculate salaries, and generate payslips.

---

##  Features
* Add Employee details (Name, ID, Hours, Rate, Bonus)
* View all employees
* Salary calculation with:
* Hourly wages
* Overtime (1.5× rate after 40 hours)
* Bonus addition
* Tax deduction (10%)
* Generate payslip
* Delete employee record
* Menu-driven interface

---

##  Salary Calculation Logic

The system calculates salary using:

* Base Pay = Hours × Rate (up to 40 hours)
* Overtime Pay = Extra Hours × Rate × 1.5
* Gross Salary = Base Pay + Overtime + Bonus
* Tax = 10% of Gross Salary
* Net Salary = Gross Salary – Tax

---

## Tech Stack

*  Python

---

##  Project Structure

```
payrollsystem/
│
├── main.py          # Main application file
├── README.md        # Project documentation
```

---

##  Installation

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/nagavardhan888/payrollsystem.git
cd payrollsystem
```

---

### 2️⃣ Install Requirements

Tkinter comes pre-installed with Python (usually).
If not:

```bash
pip install tk
```

---

## ▶ Running the Application

```bash
python payroll_gui.py
```

---


## Use Case

This project is useful for:

* Learning Python GUI development
* Understanding payroll calculations
* Academic mini-project submissions

---

##  Future Enhancements

* Database integration (SQLite / MongoDB)
* PDF Payslip generation
* Web-based version (React + Node.js)
* Authentication system

---
## Acknowledgements

Developed as a **micro project for learning and academic purposes**.

---
