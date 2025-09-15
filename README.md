# Control-Statement# Control Statements in Python 🔄🐍

This repository contains notes and examples on **Control Statements** in Python.  
Control statements help manage the **flow of execution** in a program.  

---

## 🚀 About the Project
Python provides three main types of control statements:  
1. **Conditional Statements** – decide which block of code runs based on a condition.  
2. **Looping Statements** – execute a block of code repeatedly.  
3. **Jump/Control Flow Statements** – alter the normal flow of loops.  

---

## 📂 Repository Structure
├── conditional_statements.py # if, if-else, if-elif-else
├── looping_statements.py # for loop, while loop
├── jump_statements.py # break, continue, pass
└── README.md

yaml
Copy code

---

## 📖 Topics Covered

### 🔹 Conditional Statements
Used to execute code based on conditions.  

```python
x = 10

if x > 0:
    print("Positive number")
elif x == 0:
    print("Zero")
else:
    print("Negative number")
🔹 Looping Statements
Used to run code multiple times.

✅ for loop
python
Copy code
for i in range(5):
    print("Iteration:", i)
✅ while loop
python
Copy code
count = 0
while count < 5:
    print("Count:", count)
    count += 1
🔹 Jump/Control Flow Statements
Help in modifying the normal execution of loops.

✅ break
python
Copy code
for i in range(10):
    if i == 5:
        break
    print(i)   # prints 0 to 4
✅ continue
python
Copy code
for i in range(5):
    if i == 2:
        continue
    print(i)   # skips 2
✅ pass
python
Copy code
for i in range(3):
    pass   # placeholder, does nothing
🛠️ Installation
Make sure you have Python installed (>=3.8).

bash
Copy code
python conditional_statements.py
python looping_statements.py
python jump_statements.py
🎯 Learning Resources
Python Official Docs – Control Flow

W3Schools – Python Conditions

