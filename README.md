# MIT 6.100L: Introduction to Computer Science and Programming in Python

This repository contains the coursework and solutions for the problem sets of MIT 6.100L, "Introduction to Computer Science and Programming in Python". This course is designed for students with little to no prior programming experience and covers the fundamental concepts of computation and programming using Python 3.

## Repository Content

The repository is organized into folders, one for each problem set (`ps0`, `ps1`, `ps2`, etc.). Each folder contains the Python scripts, data files, and testing code related to that specific assignment.

## Problem Sets

This repository covers the following problem sets:

*   **Problem Set 0: Getting Started**
    *   Introduces the basics of Python syntax and using the Spyder IDE.
*   **Problem Set 1: Paying Down Credit Card Debt**
    *   Focuses on using iteration to solve financial calculations, such as determining the time to pay off a loan or save for a down payment.
*   **Problem Set 2: Hangman**
    *   A classic word-guessing game that involves functions, loops, string manipulation, and reading from files.
*   **Problem Set 3: Document Distance**
    *   Explores text processing and similarity analysis by calculating the "distance" between two text documents based on word frequencies.
*   **Problem Set 4: The Permutation Cipher**
    *   An introduction to cryptography and recursion by implementing a simple substitution cipher.
*   **Problem Set 5: Image Processing and Steganography**
    *   Works with image data to apply filters simulating color blindness and to reveal hidden images concealed within other images (steganography).

## Requirements

The assignments are written for **Python 3**.

Most problem sets use only standard Python libraries. However, some have specific dependencies:

*   **Problem Set 5** requires the `Pillow` and `numpy` libraries for image manipulation.

You can install these packages using pip:
```bash
pip install Pillow numpy
```

## Usage

Each problem set folder contains the Python files for that assignment. To run and test your code, follow the instructions within the source files.

Typically, each problem set comes with a dedicated tester script (e.g., `ps1_tester.py`, `test_ps2_student.py`). You can run these tester scripts from your terminal to verify the correctness of your solutions.

For example, to run the tests for Problem Set 1:
```bash
cd ps1
python3 ps1_tester.py
```