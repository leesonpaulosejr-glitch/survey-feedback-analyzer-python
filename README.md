# Survey Feedback Analyzer (Python)

## Project Overview
This project is a Python-based text analysis tool developed as part of the **Python Fundamentals Module End Assignment**. The goal of the project is to analyze customer survey feedback using basic Python programming concepts such as dictionaries, lists, loops, conditional statements, string manipulation, and user-defined functions.

The program collects feedback entries, performs text cleaning, and extracts insights from the feedback data.

---

## Features

### 1. Preloaded Feedback Data
The program starts with a predefined dataset containing:
- Serial Number
- Customer Name
- Written Feedback
- Rating (1–5)

---

### 2. Add New Feedback
Users can add additional feedback entries by entering:
- Name
- Written Feedback
- Rating (1–5)

The system automatically generates the next serial number.

---

### 3. Text Cleaning
All feedback entries are cleaned using string operations:
- Remove punctuation (. , ! ?)
- Remove extra spaces
- Convert text to lowercase
- Remove leading and trailing spaces

---

### 4. Word Insight Analysis
A user-defined function counts how many feedback entries contain specific words.

The program analyzes occurrences of:
- "good"
- "poor"
- "excellent"

---

### 5. Final Insights
The program provides several analytical insights including:
- Display of cleaned feedback dataset
- Average rating calculation
- Identification of the longest feedback comment
- List of unique words used across all feedbacks

---

### Optional Analysis
Feedback entries can be sorted by rating from highest to lowest.

---

## Technologies Used
- Python
- Jupyter Notebook
- Basic Data Structures (Dictionary, Lists)
- String Methods
- Loops and Conditional Statements

---

## File Structure
Survey-Feedback-Analyzer
│
├── Survey_Feedback_Analyzer.ipynb
└── README.md

---

## Learning Outcomes
Through this project, the following Python concepts were applied:

- Dictionaries of lists
- Loops and conditionals
- String manipulation
- User-defined functions
- Data cleaning techniques
- Basic text analysis

---

## Author
Nikhil Leeson
