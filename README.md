# 🪔 Diwali Sales Analysis

This project analyzes Diwali sales data to uncover customer behavior, identify key segments, and generate actionable business insights for festive season marketing and inventory planning.

## 📌 Table of Contents

- [Overview](#overview)
- [Libraries Used](#libraries-used)
- [Project Workflow](#project-workflow)
- [Key Insights](#key-insights)
- [How to Run](#how-to-run)
- [Future Work](#future-work)
- [License](#license)

---

## 📖 Overview

The goal of this project is to analyze customer purchase patterns during the Diwali season using an Indian retail dataset. We performed data cleaning, exploration, and visualization to help businesses make data-driven decisions.

---

## 🛠 Libraries Used

- `pandas` – data manipulation and analysis  
- `numpy` – numerical operations  
- `matplotlib` – basic plotting  
- `seaborn` – advanced visualizations  
- `os` – file system interaction (optional)

---

## 🔄 Project Workflow

### 1. 📚 Import Libraries
All required Python libraries were imported for data handling and visualization.

### 2. 📥 Import CSV File
The Diwali sales dataset (`diwali_sales.csv`) was loaded using `pandas`.

### 3. 🧹 Data Cleaning
- Dropped missing values.
- Removed null or inconsistent entries.
- Converted data types where necessary.

### 4. 📊 Exploratory Data Analysis (EDA)

#### 🧍 Gender
- Compared purchase behavior between males and females.

#### 🧓 Age
- Analyzed which age groups spend the most during Diwali.

#### 📍 State
- Identified top-performing states in terms of total sales.

#### 💍 Marital Status
- Compared spending between married and unmarried individuals.

#### 💼 Occupation
- Analyzed buying trends based on customers' occupations.

#### 🛒 Product Category
- Found the most purchased product categories.

---

## 📈 Key Insights

- **Males** accounted for the majority of total sales.
- Customers aged **26–35 years** spent the most.
- **Uttar Pradesh, Maharashtra, and Karnataka** were top contributing states.
- **Electronic accessories** and **clothing** were best-selling categories.
- Married customers showed higher purchase frequency and spend.

---

## 🖥️ How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/diwali-sales-analysis.git
   cd diwali-sales-analysis
