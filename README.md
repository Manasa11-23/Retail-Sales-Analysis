# Retail Sales Performance Analysis

## 📌 Project Overview
This project is a **Python-based Data Analytics project** that analyzes retail sales performance using the **Superstore Dataset** from Kaggle. It was developed as part of a Data Analytics internship, focusing on data cleaning, exploratory data analysis (EDA), and business insight generation through visualizations.

## 🎯 Objective
To analyze sales, profit, quantity, and discount data across different categories, regions, segments, and time periods — and derive key business insights such as top-performing categories, regional performance, and profitability concerns.

## 📂 Dataset
- **Source**: [Superstore Dataset on Kaggle](https://www.kaggle.com/datasets/vivek468/superstore-dataset-final)
- **Format**: CSV (single file)
- **Rows**: ~9,800
- **Columns**: 21 (Order Date, Ship Date, Category, Sub-Category, Region, Sales, Profit, Quantity, Discount, Segment, etc.)

## 🛠️ Tools & Technologies Used
- **Python 3.x** – core programming language
- **Pandas** – data loading, cleaning, and manipulation
- **NumPy** – numerical calculations
- **Matplotlib** – data visualization and chart creation
- **Seaborn** – advanced statistical visualizations
- **Jupyter Notebook** – interactive coding environment
- **Anaconda** – Python environment and package management
- **Kaggle** – dataset source
- **GitHub** – version control and project hosting

## 🔧 Process

### 1. Data Cleaning
- Removed unnecessary columns (Row ID, Postal Code)
- Converted Order Date and Ship Date to datetime format
- Extracted Year, Month from Order Date for trend analysis
- Verified data types for all columns
- Checked for missing values and duplicates

### 2. Exploratory Data Analysis (EDA)
- Computed key metrics: Total Sales, Total Profit, Total Orders, Total Customers, Profit Margin
- Analyzed sales trends over time (monthly/yearly)
- Compared sales and profit across categories, regions, sub-categories, and segments

### 3. Visualizations Created
- **Line Chart** – Monthly Sales Trend Over Time
- **Bar Chart** – Total Sales by Category
- **Bar Chart** – Total Sales by Region
- **Horizontal Bar Chart** – Profit by Sub-Category (highlights loss-making items)
- **Pie Chart** – Sales Distribution by Segment

## 📊 Key Insights

1. **Sales Trend**: Sales showed a steady growth pattern over the years with a noticeable spike in late 2017.
2. **Category Performance**: Technology is the top-selling category, followed closely by Furniture and Office Supplies — all three contribute fairly equally to total revenue.
3. **Regional Performance**: The West region leads in total sales, followed by East, Central, and South. The South region is the weakest performer.
4. **Profitability Concern**: Sub-categories like Tables and Bookcases show negative profit despite reasonable sales — likely due to excessive discounting. This suggests a need to review the discount strategy.
5. **Segment Analysis**: The Consumer segment contributes the highest share of sales compared to Corporate and Home Office segments.

## 💡 Recommendations
- Review and reduce discount rates on loss-making sub-categories like Tables and Bookcases.
- Focus marketing and promotional efforts on the South region to improve its sales performance.
- Investigate the factors behind the late-2017 sales spike and replicate those strategies.
- Prioritize the Technology category as it drives the highest revenue.

## 📁 Repository Structure
```
├── README.md
├── requirements.txt
├── Retail_Sales_Analysis.ipynb
├── Sample - Superstore.csv
├── sales_trend.png
├── sales_by_category.png
├── sales_by_region.png
├── profit_by_subcategory.png
└── sales_by_segment.png
```

## 🚀 How to Run
1. Clone this repository
2. Install required libraries:
   ```
   pip install -r requirements.txt
   ```
3. Open Jupyter Notebook:
   ```
   jupyter notebook
   ```
4. Open `Retail_Sales_Analysis.ipynb`
5. Run all cells: **Kernel → Restart & Run All**

## 👤 Author
Manasa Devi Yadlapalli – Data Analytics Intern
