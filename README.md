# Student-Score-Analyzer-C-CSV-Processing-System-


## 📌 Overview

The **Student Score Analyzer** is a C++ project that demonstrates how to work with file handling, arrays, and data processing.

This application reads student scores from a CSV file, performs statistical analysis, classifies grades, and generates a summary report.

---

## ⚙️ Features

* 📂 **CSV File Handling**

  * Creates and reads data from a CSV file (`scores.csv`)

* 📊 **Statistical Analysis**

  * Calculates:

    * Average score
    * Minimum score
    * Maximum score

* 🧮 **Grade Distribution**

  * Classifies scores into:

    * A (70 and above)
    * B (60–69)
    * C (50–59)
    * D (45–49)
    * F (below 45)

* 🎯 **Random Passing Student Selection**

  * Selects a random student with a passing score (≥ 50)

* 📝 **Summary Report Generation**

  * Outputs results into `summary.csv`

---

## 🛠️ Technologies Used

* C++
* File Handling (`fstream`)
* Arrays
* Functions & Modular Programming
* Random Number Generation (`rand`, `srand`)

---

## 📁 Project Structure

```
📦 Student-Score-Analyzer
 ┣ 📄 main.cpp
 ┣ 📄 scores.csv
 ┣ 📄 summary.csv
 ┗ 📄 README.md
```

---

## ▶️ How to Run

1. Compile the program:

   ```bash
   g++ main.cpp -o analyzer
   ```

2. Run the program:

   ```bash
   ./analyzer
   ```

3. Output will be displayed in the terminal and saved to `summary.csv`.

---

## 📊 Sample Output

```
Total number of students: 7

StudentID: 1001   Score: 72
StudentID: 1002   Score: 45
...

Average Score: 64.8
Minimum Score: 39
Maximum Score: 90

A Count: 3
B Count: 1
C Count: 2
D Count: 1
F Count: 1

Random Passing Student: ID = 1005, Score = 90
```

---

## 🚀 Learning Outcomes

Through this project, I learned how to:

* Work with file input and output in C++
* Parse structured data from CSV files
* Perform statistical computations
* Organize code using functions
* Apply logic for classification and filtering

---

## 🔮 Future Improvements

* Replace arrays with vectors
* Add user input for dynamic data entry
* Implement sorting and searching features
* Convert the program into an object-oriented design

---

## 📬 Author

**Jason Mbachu**
Aspiring Software Developer | Interested in AI, Robotics, and System Design

---

⭐ If you found this project helpful or interesting, feel free to star the repository!
