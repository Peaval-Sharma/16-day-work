# Employee Salary Calculator

## 📌 Project Description

This is a simple Python program that calculates the final salary of different types of employees using **Object-Oriented Programming (OOP)** concepts.

The program uses:

* **Inheritance**
* **Method Overriding**
* **Classes and Objects**
* **Constructors (`__init__`)**

There are two types of employees:

1. Manager
2. Developer

Each employee type has a different allowance percentage.

---

## 🛠️ Technologies Used

* Python 3
* Object-Oriented Programming (OOP)

---

## ⚙️ Salary Calculation

### Manager

Manager gets **30% allowance** on the basic salary.

**Formula:**

```text
Allowance = Basic Salary × 30 / 100

Final Salary = Basic Salary + Allowance
```

### Developer

Developer gets **20% allowance** on the basic salary.

**Formula:**

```text
Allowance = Basic Salary × 20 / 100

Final Salary = Basic Salary + Allowance
```

---

## 📂 Project Structure

```text
Employee-Salary-Calculator/
│
├── employee.py
└── README.md
```

---

## ▶️ How to Run

### Step 1: Install Python

Make sure Python is installed on your computer.

Check Python version:

```bash
python --version
```

### Step 2: Open the Project

Open the project folder in **VS Code**.

### Step 3: Run the Program

Open the VS Code terminal and type:

```bash
python employee.py
```

---

## 💻 Sample Output

```text
Enter Manager Name: Rahul
Enter Manager Basic Salary: 50000

--- Manager Details ---
Employee Name : Rahul
Basic Salary  : 50000.0
Allowance     : 15000.0
Final Salary  : 65000.0

Enter Developer Name: Aman
Enter Developer Basic Salary: 40000

--- Developer Details ---
Employee Name : Aman
Basic Salary  : 40000.0
Allowance     : 8000.0
Final Salary  : 48000.0
```

---

## 🧠 OOP Concepts Used

### 1. Inheritance

`Manager` and `Developer` inherit from the `Employee` class.

```python
class Manager(Employee):
```

```python
class Developer(Employee):
```

### 2. Method Overriding

Both `Manager` and `Developer` override the `calculateSalary()` method of the parent class.

```python
def calculateSalary(self):
```

### 3. Constructor

The `__init__()` method is used to initialize employee name and basic salary.

```python
def __init__(self, name, basic_salary):
```

### 4. Classes and Objects

Objects are created using:

```python
m = Manager(name1, salary1)
d = Developer(name2, salary2)
```

---

## 🎯 Features

* Takes employee name as input
* Takes basic salary as input
* Calculates allowance automatically
* Calculates final salary
* Uses different allowance rates for Manager and Developer
* Demonstrates basic Python OOP concepts

---

## 👨‍💻 Author

**Praval Sharma**

---

## 📚 Learning Purpose

This project is created for learning and practicing **Python Object-Oriented Programming**, especially inheritance and method overriding.
