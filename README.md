# 📊 Superstore Sales EDA Project

This project is a complete Exploratory Data Analysis (EDA) of the Superstore Sales dataset.  
It demonstrates the ability to clean, transform, visualize, and interpret data using **Python**, **pandas**, and **Seaborn**.

---

## 🎯 Project Objectives

- Explore the structure of a real-world retail dataset
- Clean and prepare data for analysis
- Visualize key metrics: segment, category, and monthly sales
- Derive actionable insights that support business decisions

---

## 📁 Dataset

- **Source**: [Kaggle - Superstore Sales Dataset](https://www.kaggle.com/datasets/surajjha101/stores-area-and-sales-data)
- **File used**: `train.csv`
- **Shape**: ~9800 rows × 18 columns
- **Content**: Orders, customers, products, sales, shipping dates, and more

---

## 🧰 Tools & Libraries

- `Python 3.12`
- `pandas` — data manipulation
- `matplotlib`, `seaborn` — visualizations
- `Jupyter Notebook`

---

## 🧼 Data Preparation

- Removed rows with missing postal codes
- Checked and confirmed no duplicates
- Converted date columns (`Order Date`, `Ship Date`) to datetime format
- Created new features:
  - `Month` — for time series analysis
  - `Delivery Time (Days)` — shipping performance metric

---

## 📊 Visualizations

### 🧍 Segment Sales
![Segment Sales](graphs/segment_sales.png)

### 🪑 Category Sales
![Category Sales](graphs/category_sales.png)

### 📈 Monthly Sales Trend
![Monthly Sales](graphs/monthly_sales.png)

---

## 🔍 Key Insights

- 🔹 **Consumer segment** generated the most revenue
- 🔹 **Technology** was the top-selling category
- 🔹 **Sales peaked in December**, indicating seasonal buying patterns
- 🔹 Shipping typically takes 2–4 days; a few late deliveries noted


