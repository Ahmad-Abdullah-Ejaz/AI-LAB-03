# AI-LAB-03
# Artificial Intelligence - Lab 03: Python Flow Control, Loops & Problem Solving

This repository contains the completed laboratory tasks for **Lab 03** of the **Artificial Intelligence** course. This lab is dedicated to practical problem-solving using Python's control flow statements, nested loops, sequence manipulations, data type inspections, and string validation techniques.

---

## 📑 Table of Contents

- [Overview](#-overview)
- [Key Learning Objectives](#-key-learning-objectives)
- [Repository Structure](#-repository-structure)
- [Prerequisites](#-prerequisites)
- [How to Run the Code](#-how-to-run-the-code)
- [Task Summaries](#-task-summaries)
- [Author Details](#-author-details)

---

## 🎯 Overview

Algorithm development in AI requires writing structured, robust code with clear control flow and data validation. In this lab, we implemented a diverse set of algorithmic tasks—from numerical filtering and condition testing to string reversal, iterative patterns, and input validation rules.

---

## 🧠 Key Learning Objectives

- **Loop Iteration & Range Filtering:** Generating ranges and testing arithmetic conditions (`%` operator).
- **Conditional Temperature Formulas:** Applying standard mathematical conversion equations between Celsius and Fahrenheit.
- **Dynamic User Feedback Loops:** Building interactive command-line loops with random target generation.
- **Nested Iterations:** Formatting dynamic multi-line visual star patterns.
- **String Traversal & Reversal:** Manipulating strings iteratively without relying strictly on built-in slicing shortcuts.
- **Data Inspection:** Interrogating generic lists containing heterogeneous primitive and composite data structures.
- **Input Rule Verification:** Validating complex passwords through character categorization (`islower()`, `isupper()`, `isdigit()`).

---

## 📂 Repository Structure

```plaintext
.
├── task01_divisible_by_7_and_5.py   # Finds numbers divisible by 7 and multiples of 5 (1500–2700)
├── task02_temp_converter.py         # Converts temperatures between Celsius and Fahrenheit
├── task03_number_guessing.py        # Random number guessing game using while loops
├── task04_star_pattern.py           # Half-diamond star pattern using nested for loops
├── task05_reverse_word.py           # Accepts a word and reverses its characters
├── task06_even_odd_counter.py       # Counts even and odd numbers from a tuple series
├── task07_data_type_inspector.py    # Prints elements and their data types from a mixed list
├── task08_skip_numbers.py           # Uses the continue statement to skip 3 and 6
├── task14_password_validator.py     # Validates user password rules (length, case, digits, symbols)
├── Lab 3.pdf                        # Lab specification manual
└── README.md                        # Documentation for the repository
```

---

## ⚙️ Prerequisites

- **Python 3.8+** installed on your workstation.
- Standard Python libraries (`random` is included with default Python distributions).

Check your installed version:
```bash
python --version
```

---

## 🚀 How to Run the Code

Clone the repository and run any individual script directly from your terminal:

```bash
# Clone the repository
git clone https://github.com/<your-username>/<your-repo-name>.git

# Navigate into the project directory
cd <your-repo-name>

# Execute any task file
python task01_divisible_by_7_and_5.py
python task02_temp_converter.py
python task03_number_guessing.py
python task04_star_pattern.py
python task05_reverse_word.py
python task06_even_odd_counter.py
python task07_data_type_inspector.py
python task08_skip_numbers.py
python task14_password_validator.py
```

---

## 🔍 Task Summaries

| Task File | Description | Core Concept |
| :--- | :--- | :--- |
| `task01_divisible_by_7_and_5.py` | Identifies values divisible by 7 and 5 between 1500 and 2700. | Range iteration, modulo operator |
| `task02_temp_converter.py` | Converts values between Celsius and Fahrenheit. | Mathematical operators, functions |
| `task03_number_guessing.py` | Interactive terminal guessing game with immediate feedback. | `random`, infinite `while` loop, input parsing |
| `task04_star_pattern.py` | Prints a symmetric ascending and descending star pattern. | Nested `for` loops, end-of-line control |
| `task05_reverse_word.py` | Reverses an input string character by character. | String iteration, concatenation |
| `task06_even_odd_counter.py` | Computes separate counts for even and odd integers in a series. | Tuples, conditional parity checks |
| `task07_data_type_inspector.py` | Inspects and displays runtime data types across mixed structures. | Collections, `type()` inspection |
| `task08_skip_numbers.py` | Outputs `0 1 2 4 5`, selectively ignoring `3` and `6`. | Loop control statement (`continue`) |
| `task14_password_validator.py` | Enforces length, casing, digit, and special symbol constraints. | String inspection methods, flag logic |

---

## 👤 Author Details

- **Name:** Ahmad Abdullah Ejaz
- **Course:** Artificial Intelligence Lab
