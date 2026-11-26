# 🍽️ Restaurant Sales Dashboard

A Python-based data analysis and visualization project that analyzes restaurant sales data using **Pandas, Matplotlib, and CSV**.

The dashboard helps understand restaurant performance by calculating total sales, analyzing sales by category and date, and identifying the top-selling items.

## 📌 Project Overview

The Restaurant Sales Dashboard reads restaurant sales data from a CSV file and performs data analysis to generate useful business insights.

**Sales Calculation:**

```python
Sales = Quantity * Price
```

## 🎯 Objectives

- Load restaurant sales data using Pandas.
- Calculate total sales for each transaction.
- Skip invalid or incomplete rows.
- Analyze sales by category.
- Analyze daily sales trends.
- Identify top-selling items by quantity.
- Identify top-selling items by revenue.
- Display results using charts and visualizations.

## 🛠️ Technologies Used

- Python 3
- Pandas
- Matplotlib
- CSV

## 📂 Project Structure

```text
Restaurant-Sales-Dashboard/
│
├── restaurant_sales.csv
├── restaurant_sales.py
├── README.md
└── requirements.txt
```

## 📊 Dataset Information

The project uses a CSV file named `restaurant_sales.csv`.

The dataset contains the following columns:

| Column | Description |
|---|---|
| Date | Date of transaction |
| Item | Restaurant food item |
| Category | Food category |
| Quantity | Number of items sold |
| Price | Price per item |

### Sample Dataset

| Date | Item | Category | Quantity | Price |
|---|---|---|---:|---:|
| 2026-10-01 | Paneer Tikka | Starter | 10 | 220 |
| 2026-10-01 | Dal Makhani | Main | 15 | 260 |
| 2026-10-01 | Gulab Jamun | Dessert | 20 | 80 |
| 2026-10-02 | Paneer Tikka | Starter | 12 | 220 |
| 2026-10-02 | Veg Biryani | Main | 10 | 240 |
| 2026-10-02 | Gulab Jamun | Dessert | 25 | 80 |

## ⚙️ Features

### 1. Sales Calculation
Calculate sales for every transaction using quantity multiplied by price.

### 2. Sales by Category
Group sales by food categories such as:
- Starter
- Main
- Dessert

### 3. Daily Sales Analysis
Analyze total sales for each date.

### 4. Top-Selling Items by Quantity
Find the food items with the highest number of units sold.

### 5. Top-Selling Items by Revenue
Identify the items generating the highest revenue.

### 6. Data Visualization
Use Matplotlib to create charts for better understanding of restaurant sales.

### 7. Invalid Data Handling
Skip invalid rows and handle missing or incorrect data safely.

## 💻 Installation and Setup

**Step 1: Clone the repository**

```bash
git clone https://github.com/your-username/Restaurant-Sales-Dashboard.git
```

**Step 2: Open the project folder**

```bash
cd Restaurant-Sales-Dashboard
```

**Step 3: Install required libraries**

```bash
pip install pandas matplotlib
```

**Step 4: Run the Python program**

```bash
python restaurant_sales.py
```

## 📦 Requirements

Create a `requirements.txt` file containing:

```text
pandas
matplotlib
```

Install dependencies using:

```bash
pip install -r requirements.txt
```

## 📈 Expected Output

The sample dataset produces the following category-wise sales:

| Category | Total Sales |
|---|---:|
| Main | ₹6,300 |
| Starter | ₹4,840 |
| Dessert | ₹3,600 |
| **Total Sales** | **₹14,740** |

The program also displays:
- Top-selling items by quantity.
- Top-selling items by revenue.
- Daily sales analysis.
- Graphical representations of sales.

## 🚀 Future Improvements

- Develop an interactive dashboard.
- Add monthly and yearly sales analysis.
- Include more restaurant sales datasets.
- Add advanced data visualization.
- Export sales reports to Excel or PDF.

## 👩‍💻 Author

**Your Name**
Neha Gahlot

---

