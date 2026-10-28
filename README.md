# Student Marks Report Generator 📝

A Python-based project that generates a student marks report by calculating total marks, average marks, grades, class average, and the topper.

## 📌 Project Overview

The Student Marks Report Generator processes predefined student records using Python lists, loops, functions, and conditional statements. It calculates individual student performance and generates a summary of the class results.

This project was developed to practice fundamental Python programming concepts and understand how structured data can be processed to produce meaningful reports.

## ✨ Features

* Stores student names and subject marks using nested lists.
* Calculates total marks for each student.
* Calculates individual average marks.
* Assigns grades based on average marks.
* Calculates the overall class average.
* Identifies the student with the highest average.
* Displays the results in the terminal.

## 🛠️ Technologies Used

* **Programming Language:** Python 3
* **Editor:** Cursor / Visual Studio Code
* **Concepts:** Functions, lists, loops, indexing, conditional statements, and arithmetic operations.

## 📂 Project Structure

```text
Student-Marks-Report/
├── messy_py.py
├── README.md
└── AUDIT.md
```

## ⚙️ How It Works

### 1. Student Data

The program stores each student's name and marks in a nested list.

```python
d = [
    ["Rahul", 78, 88, 92],
    ["Priya", 65, 71, 69],
    ["Amit", 90, 94, 85],
    ["Sneha", 55, 60, 58],
    ["Vikram", 82, 79, 88]
]
```

### 2. Total Marks Calculation

The function `f(x)` calculates the total marks for a student.

```python
def f(x):
    t = 0
    for i in range(1, len(x)):
        t = t + x[i]
    return t
```

The loop starts at index `1` because index `0` contains the student's name. The remaining elements contain numerical marks.

### 3. Average Calculation

The program calculates the average by dividing the total marks by three, assuming each student has three subjects.

### 4. Grade Assignment

The program assigns grades according to these thresholds:

| Average Marks | Grade | 
| ----- | ----- | 
| 90 and above | A | 
| 80 to below 90 | B | 
| 70 to below 80 | C | 
| 60 to below 70 | D | 
| Below 60 | F | 

### 5. Class Average

The program calculates the class average by adding all individual student averages and dividing the total by the number of students.

### 6. Topper Identification

The program compares student averages and identifies the student with the highest average.

## ▶️ How to Run the Project

**Prerequisite:** Python 3 must be installed.

1. Clone or download the project repository.
2. Open the project folder in Cursor or Visual Studio Code.
3. Open a terminal in the project directory.
4. Run the program:

```bash
python3 messy_py.py
```

On Windows, use `python messy_py.py` if the `python` command is configured.

## 📊 Sample Output

```text
REPORT
Rahul25886.0B
Priya20568.333333333333333D
Amit26989.666666666666667B
Sneha17357.666666666666664F
Vikram24983.0B

Class average: 76.93333333333334
Topper: Amit89.66666666666667
```

*Note: The output reflects the current program's print statements. Spacing and decimal formatting can be improved for readability.*

## 🔍 Code Audit Summary

A preliminary code audit was performed to review the program's calculations, logic, and code quality.

**Verified calculations:**

* Rahul: 258 total marks, 86.00 average, Grade B
* Priya: 205 total marks, 68.33 average, Grade D
* Amit: 269 total marks, 89.67 average, Grade B
* Sneha: 173 total marks, 57.67 average, Grade F
* Vikram: 249 total marks, 83.00 average, Grade B
* Class average: 76.93
* Topper: Amit, with an average of 89.67

### Audit Findings

The calculations match the supplied dataset and the grading conditions used by the program.

The audit also identified improvements that would make the project more reliable and maintainable:

* Use descriptive function and variable names.
* Validate student records and mark ranges.
* Handle empty datasets safely.
* Improve output formatting.
* Handle tied topper results.
* Add automated tests for calculations and grade assignment.

These are recommendations for future development, not features currently claimed as implemented.

## 🚀 Future Improvements

* Accept student records through user input or a file.
* Support a variable number of subjects.
* Add input validation and error handling.
* Display a neatly formatted results table.
* Handle students with equal highest averages.
* Add automated unit tests.
* Export the report to a CSV file.

## 🎯 Learning Outcomes

This project helped practice:

* Defining and calling Python functions.
* Working with nested lists and indexing.
* Using loops to process records.
* Applying conditional statements.
* Calculating totals and averages.
* Finding the maximum value in a dataset.
* Reviewing code quality and identifying areas for improvement.

## 📋 Audit Documentation

See [`AUDIT.md`](AUDIT.md) for the detailed code audit, including functional findings, potential issues, recommendations, and audit limitations.

## 👩‍💻 Author

Created as a Python programming practice project."# Messy-code-project" 
"# Messy-code-project" 
