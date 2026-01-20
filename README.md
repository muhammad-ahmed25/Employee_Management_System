# Employee Management System (File-Based) — Python

A simple **console-based Employee Management System** written in Python that stores employee records in a **text file (CSV format)**.  
You can **Add, View, Search, Delete, and Update** employees, including their **Rank** (e.g., Manager, Boss, Employee).

---

## Features

- ✅ Add a new employee (ID, Name, Salary, Rank)
- ✅ View all employees in a table format
- ✅ Search employees by:
  - ID
  - Name
  - Rank
- ✅ Delete employee by ID
- ✅ Update employee by ID
- ✅ Stores data permanently in a `.txt` file (CSV style)

---

## File Storage Format

Employee records are stored in a text file like this:

emp_id,name,salary,rank
101,Ali,50000,Manager
102,Ayesha,45000,Employee

yaml
Copy code

---

## Requirements

- Python 3.x installed
- Works on Windows, Linux, macOS

---

## How to Run

1. Save your Python code in a file, for example:
employee_system.py

go
Copy code

2. Run it:
```bash
python employee_system.py
Important (Windows Path Fix)
Your code currently has:

python
Copy code
FILE_NAME = "D:\EMPLOYE2.txt"
On Windows, \E can behave like an escape sequence. Use one of these correct versions:

✅ Option 1 (recommended): Raw string

python
Copy code
FILE_NAME = r"D:\EMPLOYE2.txt"
✅ Option 2: Double slashes

python
Copy code
FILE_NAME = "D:\\EMPLOYE2.txt"
✅ Option 3: Put file in same folder as script

python
Copy code
FILE_NAME = "EMPLOYE2.txt"
Menu Options
When you run the program, you will see:

Add Employee

View Employees

Search Employee

Delete Employee

Update Employee

Exit

Notes / Tips
Employee ID should be unique (recommended).

Salary is stored as text in the file (you can convert to int/float if you want validations).

If the file does not exist, it will be created automatically when you add the first employee.

Possible Improvements (Optional)
Add input validation (salary must be numeric, ID must be unique)

Use the csv module properly for safer reading/writing

Add sorting (by salary, rank, name)

Add login/admin access

Author
Created by: Your Name Here

sql
Copy code

If you want, I can also:
- improve the code using the `csv` module properly,
- add salary validation + unique ID checking,
- and make it create headers automatically.
