# 🦴 Skeletal Variation

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?logo=pandas)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter)
![Cisco](https://img.shields.io/badge/Cisco-Networking%20Academy-1BA0D7?logo=cisco)

A data analysis project using **Python** and **Pandas** to explore skeletal anatomy datasets and answer biological questions through data analysis.

> Completed as part of the **Data Science Essentials with Python** course by **Cisco Networking Academy**.

---

## 📖 Project Overview

This project explores the structure of the adult human skeleton and compares skeletal characteristics across species using real datasets.

The analysis focuses on developing fundamental data analysis skills with **Pandas**, including data exploration, filtering, querying, and summarizing information to answer biological questions.

---

## 🎯 Objectives

- Explore skeletal anatomy datasets
- Analyze bone distributions
- Filter and query data using Pandas
- Answer biological questions through data analysis
- Practice exploratory data analysis (EDA)

---

## 🛠️ Technologies Used

- Python 3
- Pandas
- Jupyter Notebook
- Visual Studio Code
- Git & GitHub

---

## 📂 Repository Structure

```text
skeletal-variation/
│
├── skeletal-variation.ipynb
├── adult-human-skeleton.csv
├── bird-neck-bones.csv
├── mammal-neck-bones.csv
├── README.md
```

---

## 📊 Example Analysis

Some of the questions explored in this project include:

- How many rib bones are present in the adult human skeleton?
- Which bird species has the fewest neck vertebrae?
- How can specific bones be filtered using string matching?
- How can Pandas be used to answer biological questions efficiently?

### Example

```python
import pandas as pd

df = pd.read_csv("adult-human-skeleton.csv")

ribs = df[df["name"].str.contains("rib", case=False, na=False)]

print(f"There are {len(ribs)} ribs in the adult human skeleton.")
```

---

## 📈 Skills Demonstrated

- Reading CSV files with Pandas
- Exploring and inspecting datasets
- Filtering DataFrames
- Boolean indexing
- String matching with `.str.contains()`
- Querying and summarizing data
- Writing clean and readable Python code

---

## 🚀 Getting Started

### Clone the repository

```bash
git clone https://github.com/laurabarboza09282/skeletal-variation.git
```

### Install the required library

```bash
pip install pandas
```

### Run the project

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open `skeletal-variation.ipynb` and run the notebook cells.

---

## 📚 Learning Context

This repository contains **my solutions** to exercises from the **Data Science Essentials with Python** course offered by **Cisco Networking Academy**.

The project was completed for educational purposes to strengthen practical skills in Python programming, data manipulation with Pandas, and exploratory data analysis.

---

## 👩‍💻 Author

**Laura dos Santos Barboza**

GitHub: https://github.com/laurabarboza09282

---

## ⚠️ Disclaimer

This repository contains my personal solutions to exercises from the **Data Science Essentials with Python** course offered by **Cisco Networking Academy**.

The original course materials and datasets belong to their respective owners and are shared here solely for educational purposes.

---

## ⭐ Acknowledgments

Special thanks to **Cisco Networking Academy** for providing the course materials and datasets used in this educational project.
