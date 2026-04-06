#  Superstore Sales Analysis (EDA Project)

##  Project Overview
This project is an Exploratory Data Analysis (EDA) of a Superstore dataset.  
The main goal is to analyze sales, profit, customer behavior, and business performance across different categories, regions, and shipping modes.

---

##  Tools & Libraries Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn

---

##  Dataset Information
The dataset includes:
- Order details
- Customer information
- Product categories & sub-categories
- Sales, profit, discount
- Shipping details

---

##  Data Cleaning & Feature Engineering
Performed the following steps:
- Converted `sales` to numeric format
- Converted `order_date` and `ship_date` to datetime
- Created new feature: `delivery_days`
- Created new feature: `profit_ratio`
- Handled missing values using proper methods

---

##  Exploratory Data Analysis (EDA)

###  Sales Analysis
- Total sales calculated
- Category-wise sales distribution
- Region-wise sales contribution

###  Profit Analysis
- Total profit calculation
- Sub-category wise profit analysis
- Loss-making vs profit-making orders

###  Customer Analysis
- Top customers by sales

###  Shipping Analysis
- Shipping mode vs sales analysis
- Delivery time analysis

###  Advanced Analysis
- Discount vs Profit relationship
- Extreme profit/loss detection (outliers)

---

##  Key Insights
- Technology category gives highest sales
- Some orders generate very high profit or loss
- High discount often reduces profit
- A few customers contribute major revenue
- Region-wise performance is uneven

---

##  Key Features Created
- `delivery_days = ship_date - order_date`
- `profit_ratio = profit / sales`

---

## Conclusion
This project demonstrates real-world data analysis workflow using Python.  
It helps in understanding business performance and generating actionable insights from raw data.

---

##  Author
Ujjawal Shah
