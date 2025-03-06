
# 📌 Simple Grade Calculator

## 📖 Overview
This Python program allows users to enter their marks and determines their grade based on predefined criteria. 🎓✅

---

## 🚀 Steps to Run the Program

### 🔹 Step 1: Take Input from the User
```python
marks = float(input("Enter your number: "))
```
📌 `input("Enter your number: ")` prompts the user to enter their marks.
📌 `input()` returns a string, so we use `float()` to convert it into a decimal number (e.g., 85.5).

---

### 🔹 Step 2: Check the Marks and Assign a Grade
The program uses `if-elif-else` conditions to determine the grade based on the marks entered. 📊

#### 🏆 Step 2.1: Check for A+ Grade
```python
if marks >= 90:
    print("A+ (Excellent)")
```
✅ If marks are **90 or more**, it prints **"A+ (Excellent)"**.

#### 🥇 Step 2.2: Check for A Grade
```python
elif marks >= 80:
    print("A (Very Good)")
```
✅ If marks are **80 or more but less than 90**, it prints **"A (Very Good)"**.

#### 🥈 Step 2.3: Check for B Grade
```python
elif marks >= 70:
    print("B (Good)")
```
✅ If marks are **70 or more but less than 80**, it prints **"B (Good)"**.

#### 🥉 Step 2.4: Check for C Grade
```python
elif marks >= 60:
    print("C (Average)")
```
✅ If marks are **60 or more but less than 70**, it prints **"C (Average)"**.

#### ⚠️ Step 2.5: Check for D Grade
```python
elif marks >= 50:
    print("D (Below Average)")
```
✅ If marks are **50 or more but less than 60**, it prints **"D (Below Average)"**.

#### ❌ Step 2.6: Check for F Grade (Fail)
```python
else:
    print("F (You are fail)")
```
❌ If marks are **less than 50**, it prints **"F (You are fail)"**.

---

## 📝 Example Scenarios

### ✅ Example 1: Input = 92
```bash
Enter your number: 92
A+ (Excellent)
```

### ✅ Example 2: Input = 75
```bash
Enter your number: 75
B (Good)
```

### ❌ Example 3: Input = 45
```bash
Enter your number: 45
F (You are fail)
```

---

## 📌 Summary
✅ The program takes the user's marks as input.
✅ It checks different conditions to assign a grade.
✅ It prints the corresponding grade message.

🎯 Simple, effective, and easy to use! 🚀

