# MSc Applied Mathematics Python Crash Course

---

This repository contains the material for the live crash course in Python designed for new MSc Applied Mathematics 
students at Imperial, 2026 cohort.

No prior Python experience is assumed.

The course will be an interactive hands-on exercise session, covering Python basics and some of the most commonly used 
libraries (NumPy, Matplotlib) that students will encounter throughout the MSc course.

---
## Structure

### 1. Python Fundamentals 

By the end of the session you should be able to:
- Setup and navigate a Jupyter notebook
- Explain the difference between core data types
- Use Python operators
- Use `for` and `while` loops
- Define and call functions

### 2. Data Structures & Scientific Python

By the end of the session you should be able to:
- Store and manipulate collections of data
- Create NumPy arrays and understand the advantages they offer over Python lists
- Use NumPy to solve common mathematical problems
- Select the appropriate data structure for a given problem

### 3. Working with Data & Visualisation

By the end of the session you should be able to:
- Load data into a Pandas DataFrame from a CSV file and inspect its contents
- Use basic built-in Pandas operations
- Create plots using Matplotlib (line plots, scatter plots, histograms)

### 4. Good Coding Practices

By the end of the session you should be able to:
- Write clean, readable code
- Use docstrings and comments to explain functions
- Apply debugging strategies to identify errors

---
## Pre-Course Instructions

The course will run on Jupyter Notebooks. Students should ensure they can open the `.ipynb` files and run the code. 
There are two options for doing this:

#### 1. Google Colab
You will need a Google email account. After this, you can upload your `.ipynb` files to 
[Google Colab](https://colab.research.google.com). No additional installation is required.

#### 2. Local Jupyter installation
- You will need to make sure that you have Python installed. To do this, open a terminal on your laptop and check you have
Python installed by running:
```bash
python --version
``` 
If you get an error saying Python is not recognised, try running `python3 --version` instead.

- If you don't have Python installed, download it from [here](https://www.python.org/downloads/), make sure you choose the
right operating system (Windows/macOS/Linux).
- Install Jupyter and the libraries that you will be using by running the following in your terminal:
```bash
pip install notebook numpy matplotlib pandas scipy
```
- Launch Jupyter:
```bash
jupyter notebook
```
This should open Jupyter in your browser. Navigate to the folder containing the course `.ipynb` files and open one to 
confirm everything runs.
- As a sanity check, try importing some packages by running the following code in a cell in the notebook:
```python
import numpy
import matplotlib
print("Setup complete!")
```

---
## Questions
Feel free to email me if you run into any issues or have any questions! 
Try to have a working environment before the start of the course.

---
## References
- [lucasmoschen/PyCrashCourse-AppliedMath-MSc](https://github.com/lucasmoschen/PyCrashCourse-AppliedMath-MSc)
- [sarabicego/PyCrashCourse2024](https://github.com/sarabicego/PyCrashCourse2024)

This course was developed for the MSc Applied Mathematics induction at Imperial College London. 


