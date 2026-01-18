# Dataset Management and Basic Analysis System

## Abstract

This project presents a simple Python-based system for managing datasets and performing basic statistical analysis. It is designed primarily for academic and instructional purposes, demonstrating fundamental programming concepts such as file handling, functions, control structures, data structures, and object-oriented programming.

---

## Problem Statement

In many academic and practical scenarios, data are stored in external files and require basic analysis to extract meaningful information. Students often lack a clear, structured example that integrates file handling, data processing, and result reporting using Python. This project addresses this gap by providing a straightforward system that reads numerical and categorical data from files, analyzes the data, and presents the results in a clear and reproducible manner.

---

## Objectives

The objectives of this project are to:

1. Demonstrate how to read numerical and categorical data from external files using Python.
2. Apply functions and loops to compute basic statistical measures such as total, average, minimum, and maximum.
3. Use conditional statements to evaluate performance based on a defined threshold.
4. Apply sets to extract unique categorical values.
5. Implement a simple object-oriented design for data analysis tasks.
6. Save computed results to an output report file.

---

## Project Structure

```
├── numeric_data.csv      # Numerical dataset (input)
├── categories.txt        # Categorical dataset (input)
├── dataset_analysis.py   # Main Python program
├── report.txt            # Generated analysis report
└── README.md             # Project documentation
```

---

## Input Data Description

### Numeric Data (`numeric_data.csv`)

The file contains comma-separated numerical values representing quantities such as students’ marks or sales figures.

Example:

```
45,78,88,62,55
```

### Categorical Data (`categories.txt`)

The file contains one category per line, representing items such as course names or product types.

Example:

```
Physics
Chemistry
Mathematics
Physics
Biology
```

---

## Methodology

The program loads numerical data into a list and categorical data into a set. Iterative loops are used to traverse the numerical dataset in order to compute total, average, minimum, and maximum values. Conditional logic is applied to classify performance based on the computed average. The final results are displayed on the screen and written to a report file for record-keeping.

---

## Sample Output

```
Total: 328.0
Average: 65.6
Minimum: 45.0
Maximum: 88.0
High Performance
Unique Categories: 4
```

---

## Screenshots

Include the following screenshots in this section when submitting or presenting the project:

1. Screenshot showing the input files (`numeric_data.csv` and `categories.txt`).
2. Screenshot of the program running and displaying output in the terminal or Google Colab.
3. Screenshot of the generated `report.txt` file.

---

## Tools and Technologies

* Programming Language: Python
* Development Environment: Local Python environment or Google Colab

---

## Conclusion

This project demonstrates a clear and practical approach to basic dataset management and analysis using Python. It reinforces foundational programming concepts and provides a reusable framework for simple data analysis tasks in academic settings.

---

## License

This project is intended strictly for educational purposes.
