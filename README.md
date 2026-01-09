# Python_EDA
# Super Store Exploratory Data Analysis (EDA)

## 📌 Project Overview

This project performs **Exploratory Data Analysis (EDA)** on the **Super Store dataset** to understand sales performance, profitability, customer behavior, shipping preferences, and regional trends. The analysis uses **Python, Pandas, Matplotlib, and Seaborn** and is designed to be **beginner-friendly and interview-ready**.

---

## 📂 Dataset

* **File Name:** `SampleSuperstore.csv`
* **Records:** ~9,994 rows
* **Features:** 13 columns

### Key Columns

* `Category`, `Sub-Category`
* `Sales`, `Profit`, `Quantity`, `Discount`
* `Segment`, `Ship Mode`, `Region`

---

## 🧹 Data Cleaning

* Checked for **missing values** → No missing data found
* Removed **duplicate records**
* Added a new feature:

  * **Profit Margin (%)** = `(Profit / Sales) * 100`

---

## 🔍 Exploratory Data Analysis

### 1️⃣ Category-Level Analysis

* Identified **best-selling** and **most profitable** categories
* Compared **Sales**, **Profit**, and **Quantity** using bar plots

**Insights:**

* Technology category generates the highest profit
* Furniture shows lower profitability compared to sales

---

### 2️⃣ Sub-Category Analysis

* Analyzed **Sales**, **Profit**, and **Quantity** at sub-category level
* Sorted sub-categories by:

  * Highest Sales
  * Highest Profit
  * Highest Quantity Sold

**Insights:**

* Phones and Chairs are top-selling sub-categories
* Tables show **negative profit** despite good sales
* Some items sell more units but generate less profit

---

### 3️⃣ Customer Segment Analysis

* Compared profitability across segments:

  * Consumer
  * Corporate
  * Home Office

**Insight:**

* **Consumer segment** is the most profitable

---

### 4️⃣ Shipping Mode Analysis

* Used count plot to find the **preferred shipping mode**

**Insight:**

* **Standard Class** is the most commonly used shipping method

---

### 5️⃣ Regional Profit Analysis

* Calculated total profit by region
* Visualized using a pie chart

**Insight:**

* **West region** is the most profitable
* Central region contributes the least

---

## 📊 Visualizations Used

* Bar Charts (Vertical & Horizontal)
* Count Plot
* Pie Chart

All plots use **Seaborn themes** (`whitegrid`, `Set2`) for clean and professional visuals.

---

## 🛠️ Technologies Used

* **Python**
* **Pandas** – Data manipulation
* **Matplotlib** – Plotting
* **Seaborn** – Statistical visualizations
* **Jupyter Notebook**
* 
## 📌 Key Business Takeaways

* High sales do not always mean high profit
* Some sub-categories need pricing or cost optimization
* Consumer customers and West region are key profit drivers

