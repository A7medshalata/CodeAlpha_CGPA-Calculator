# CGPA Calculator (C++) 🎓

A simple, interactive, and user-friendly Console Application built in **C++** to calculate the Semester GPA and Cumulative Grade Point Average (CGPA). This project was developed as part of my **CodeAlpha Internship** program (Task 1).

---

## 🚀 Features
* **Dynamic Input:** Allows users to input any number of courses dynamically.
* **Structured Data:** Uses C++ `struct` and `std::vector` to organize and manage course details efficiently.
* **Detailed Summary:** Displays an individual breakdown of each course's grade and credit hours before showing the final result.
* **Precision Formatting:** Output is formatted cleanly to 2 decimal places using `<iomanip>`.

---

## 📊 How the Calculation Works
The program follows the standard academic grading system calculation:
1. **Total Grade Points** = $\sum (\text{Grade Point} \times \text{Credit Hours})$
2. **Total Credits** = $\sum (\text{Credit Hours})$
3. **Final CGPA** = $\frac{\text{Total Grade Points}}{\text{Total Credits}}$

---

## 🛠️ Requirements & Tech Stack
* **Language:** C++11 or higher
* **Compiler:** GCC / Clang / MSVC
* **Standard Libraries Used:** `<iostream>`, `<vector>`, `<iomanip>`
