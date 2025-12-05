# Student-Marks-Calculator-
A simple python program to calculate student marks and grade

# 🎓 Student Marks Calculator (Python)

A simple and beginner-friendly **Python program** that calculates the **total marks, average, and grade** of a student based on marks entered for three subjects.

This project is perfect for beginners learning Python basics like inputs, arithmetic operations, and conditional statements.

---

## ✨ Features

- ✔ Takes student name and 3 subject marks as input  
- ✔ Calculates **total** and **average**  
- ✔ Assigns **grade** based on average  
- ✔ Displays a clean student report  
- ✔ Very simple and beginner-friendly  

---

## 🛠️ Technologies Used

- **Python 3**
- Inputs & Outputs
- Arithmetic Calculations
- Conditional Statements (if-elif-else)

---

## 📌 Program Code

```python
# Student Marks Calculator

# Taking inputs
name = input("Enter student name: ")
m1 = float(input("Enter marks in Subject 1: "))
m2 = float(input("Enter marks in Subject 2: "))
m3 = float(input("Enter marks in Subject 3: "))

# Calculations
total = m1 + m2 + m3
average = total / 3

# Grade calculation
if average >= 90:
    grade = "A"
elif average >= 75:
    grade = "B"
elif average >= 60:
    grade = "C"
elif average >= 50:
    grade = "D"
else:
    grade = "F"

# Output
print("\n----- Student Report -----")
print("Name:", name)
print("Subject 1 Marks:", m1)
print("Subject 2 Marks:", m2)
print("Subject 3 Marks:", m3)
print("Total Marks:", total)
print("Average Marks:", round(average, 2))
print("Grade:", grade)
