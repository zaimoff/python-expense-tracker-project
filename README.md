# Expense Tracker System (Python)

A simple and beginner‑friendly Python project that demonstrates how to build an expense tracking module using lists, dictionaries, validation logic, and aggregation functions. This project is ideal for anyone learning Python fundamentals and wanting to apply them in a practical context.

---

## 🚀 Project Overview

The Expense Tracker System allows users to record expenses, categorize them, and calculate totals. It includes validation to ensure that only positive amounts are accepted and provides functions to compute overall spending as well as category‑specific totals.

A built‑in test runner demonstrates example usage and error handling.

---

## 🧩 Features

### ✔️ Add Expenses
- Each expense includes:
  - Amount  
  - Category  
  - Description  
- Validates that the amount is greater than zero  
- Stores expenses in an in‑memory list  

### ✔️ Aggregation Logic
- Calculate total expenses  
- Calculate total expenses by category  

### ✔️ Display Functionality
- Show all recorded expenses in a clean, readable format  

### ✔️ Exception Handling
- Raises and handles errors for invalid inputs (e.g., non‑positive amounts)

---

## 📁 Project Structure

├── add_expense()
├── calculate_total_expenses()
├── calculate_total_by_category()
├── show_expenses()
└── run_tests()

Everything is contained in a single Python file for clarity and ease of learning.

---

## 🧪 How to Run

1. Clone the repository:
   ```bash
   git clone <your-repo-url>
Run the script:

bash
python expense_tracker.py
View the output:

Total expenses

Category totals

List of all expenses

Error handling demonstration

🎯 Learning Objectives
This project helps you practice:

Working with lists and dictionaries

Writing modular Python functions

Implementing validation logic

Using exceptions effectively

Performing aggregation calculations

Structuring small Python projects

🔮 Future Enhancements
Here are some optional improvements you can build on:

Add date support for each expense

Export expenses to a CSV or JSON file

Add category summaries or charts

Build a CLI or GUI interface

Add unit tests using pytest

📜 License
This project is open‑source and available under the MIT License.
