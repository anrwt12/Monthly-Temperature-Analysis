# Monthly Temperature Analysis Using NumPy 🌡️🐍

## 📌 Overview

This mini project focuses on analyzing **monthly temperature data using NumPy**.

The project demonstrates how numerical data can be processed and analyzed using Python. It calculates average temperature, identifies the hottest and coldest days, and counts the number of days with above-average temperatures.

---

## 🎯 Project Objectives

The main objectives of this project are:

- Analyze daily temperature data for one month
- Calculate average monthly temperature
- Find maximum and minimum temperatures
- Identify hottest and coldest days
- Count days above average temperature
- Understand NumPy operations for data analysis

---

## 🛠️ Technologies Used

- Python 🐍
- NumPy
- Jupyter Notebook / Google Colab

---

## 📂 Dataset Information

A NumPy array was created containing temperature data for **30 days**.

Example:

```
[22, 24, 23, 25, 26, ... , 21]
```

Dataset contains:

- Total Days: 30
- Data Type: Numerical Temperature Values
- Unit: Celsius (°C)

---

## 🔍 Methodology

### 1. Import NumPy

Imported NumPy library for numerical operations.

```python
import numpy as np
```

---

### 2. Create Temperature Array

Created a NumPy array containing daily temperature records for one month.

---

### 3. Calculate Average Temperature

Used:

```python
np.mean()
```

to calculate the monthly average temperature.

---

### 4. Find Highest and Lowest Temperature

Used:

```python
np.max()
np.min()
```

to identify:

- Maximum temperature
- Minimum temperature

---

### 5. Identify Hottest and Coldest Days

Used:

```python
np.argmax()
np.argmin()
```

to find the index position of:

- Hottest day
- Coldest day

Added `+1` because Python indexing starts from 0, while days start from 1.

---

### 6. Count Above Average Temperature Days

Used boolean filtering with:

```python
np.sum()
```

to count how many days had temperature higher than the monthly average.

---

# 📊 Results

### Monthly Temperature Analysis Output:

```
Average Temperature: 28.50 °C

Highest Temperature: 36 °C on Day 15

Lowest Temperature: 21 °C on Day 30

Days above average temperature: 15
```

---

# 📈 Key Insights

- The average monthly temperature was **28.50°C**.
- The hottest day was **Day 15 with 36°C**.
- The coldest day was **Day 30 with 21°C**.
- Half of the month (15 days) had temperatures above average.

---

# 🎯 Learning Outcomes

Through this project, I learned:

✅ Working with NumPy arrays  
✅ Performing mathematical operations using NumPy  
✅ Using aggregation functions like mean, max, and min  
✅ Finding indexes using argmax and argmin  
✅ Applying Boolean conditions for data filtering  
✅ Basic numerical data analysis using Python  

---

# 🚀 Future Improvements

Possible improvements:

- Analyze temperature data for multiple months
- Add data visualization using Matplotlib
- Create weather trend graphs
- Use real-world weather datasets
- Build an interactive weather dashboard

---

# 📁 Repository Structure

```
Monthly-Temperature-Analysis-NumPy/
│
├── Monthly_Temperature_Analysis.ipynb
├── README.md
└── requirements.txt
```

---

# 👩‍💻 Author

**Anjali Rawat**

🎯 Aspiring Data Analyst | B.Sc Computer Science Student

### Skills:
- Python
- NumPy
- Pandas
- SQL
- Excel
- Power BI
- Machine Learning

---

⭐ If you find this project useful, consider starring this repository!
