# Day 13 – NumPy Data Filtering

## 📌 Overview

This repository contains my **Day 13 task** from the **AI & ML Internship Track**.

The task focuses on using **NumPy** to filter numerical data based on specific conditions. Boolean conditions and Boolean indexing are used to identify values that are above, below, equal to, or within a specified range.

---

## 🎯 Objective

* Understand Boolean conditions in NumPy.
* Practice Boolean indexing.
* Filter numerical values based on thresholds.
* Apply multiple conditions to NumPy arrays.
* Perform basic filtering on student marks and sales data.

---

## 🛠️ Tools & Technologies

* **Python**
* **NumPy**
* **Jupyter Notebook**
* **Git & GitHub**

---

## 📂 Project Structure

```text
Day-13-NumPy-Data-Filtering/
│
└── Day-13-NumPy-Data-Filtering.ipynb
```

---

## 📊 Dataset Used

### Student Marks

The following numerical values were used for filtering:

```python
[45, 67, 89, 32, 76, 54, 91, 38, 82, 60]
```

### Sales Values

A second dataset was used to demonstrate filtering:

```python
[1200, 850, 1500, 650, 2200, 950, 1800, 500]
```

---

## 🔍 Concepts Covered

### 1. NumPy Array Creation

```python
import numpy as np

marks = np.array([45, 67, 89, 32, 76, 54, 91, 38, 82, 60])
```

### 2. Boolean Conditions

```python
marks > 50
```

This produces a Boolean array containing `True` and `False` values.

### 3. Boolean Indexing

```python
marks[marks > 50]
```

This returns only the values greater than 50.

### 4. Filtering Below a Threshold

```python
marks[marks < 50]
```

### 5. Filtering Equal Values

```python
marks[marks == 60]
```

### 6. Multiple Conditions

```python
marks[(marks >= 50) & (marks <= 80)]
```

This filters values between 50 and 80.

---

## 📈 Examples

### Values Above 50

```text
[67 89 76 54 91 82 60]
```

### Values Below 50

```text
[45 32 38]
```

### Values Equal to 60

```text
[60]
```

### Values Greater Than or Equal to 75

```text
[89 76 91 82]
```

### Values Between 50 and 80

```text
[67 76 54 60]
```

---

## 💰 Sales Data Filtering

Sales values were also filtered using NumPy Boolean indexing.

### Sales Above 1000

```text
[1200 1500 2200 1800]
```

### Sales Below 1000

```text
[850 650 950 500]
```

### Sales Between 800 and 1800

```text
[1200 850 1500 950 1800]
```

---

## 🧠 Key Learning

Through this task, I learned how **Boolean indexing** can be used to efficiently select specific elements from a NumPy array based on numerical conditions.

The task helped strengthen my understanding of:

* NumPy arrays
* Boolean expressions
* Boolean arrays
* Boolean indexing
* Threshold-based filtering
* Multiple filtering conditions
* Numerical data analysis

---

## ❓ Interview Questions

### What is Boolean indexing?

Boolean indexing is a NumPy technique used to select elements from an array based on Boolean conditions.

### How do you filter a NumPy array?

A condition can be placed inside square brackets:

```python
data[data > 50]
```

### What is a Boolean array?

A Boolean array contains `True` and `False` values indicating whether individual elements satisfy a specified condition.

### How are multiple conditions applied in NumPy?

The `&` operator is used for **AND**, while the `|` operator is used for **OR**.

Example:

```python
data[(data > 20) & (data < 80)]
```

---

## 📓 Notebook

The complete implementation and outputs are available in:

**`Day-13-NumPy-Data-Filtering.ipynb`**

---

## 👨‍💻 Author

**Divakar R**
B.E. Electronics and Communication Engineering
Adithya Institute of Technology, Coimbatore

---

## 🏷️ Tags

```text
Python
NumPy
Data Filtering
Boolean Indexing
Data Analysis
Jupyter Notebook
AI
Machine Learning
AI ML Internship
```

---

**Repository:** `Day-13-NumPy-Data-Filtering`
**Task:** Day 13 – NumPy Data Filtering
