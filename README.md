#  Sales Data Analysis using Python

##  Project Overview

This project analyzes a furniture sales dataset containing 10,000 sales transactions using Python. The analysis includes data cleaning, data aggregation, exploratory data analysis (EDA), and dashboard visualization to identify sales trends, promotional performance, and regional sales distribution. The project concludes with business insights and strategic recommendations to support data-driven marketing decisions.

---

##  Objectives

- Clean and prepare raw sales data for analysis.
- Identify and remove duplicate records.
- Handle missing values.
- Convert date columns into datetime format.
- Extract city information from shipping addresses.
- Analyze total sales performance by city.
- Visualize regional sales distribution.
- Analyze promotional transactions.
- Evaluate the relationship between product prices and total sales.
- Examine discount distribution across product categories.
- Generate business insights and strategic recommendations.

---

##  Tools & Technologies

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

##  Python Skills Demonstrated

- Data Import
- Data Cleaning
- Duplicate Removal
- Missing Value Handling
- Datetime Conversion
- String Manipulation
- Data Filtering
- GroupBy Aggregation
- Data Sorting
- Exploratory Data Analysis (EDA)
- Data Visualization
- Business Insight Generation

---

#  Project Workflow

##  Challenge 1 – Data Cleaning

### Tasks

- Load the Excel dataset using Pandas.
- Identify duplicate records.
- Remove duplicate rows.
- Handle missing values in the `shipping_address` column.
- Convert the `sales_date` column into datetime format.
- Verify the cleaned dataset using `df.info()`.

### Output

- Duplicate records removed.
- Missing values handled successfully.
- Datetime conversion completed.
- Clean dataset ready for analysis.

---

##  Challenge 2 – Data Aggregation & Visualization

### Tasks

- Extract city names from shipping addresses.
- Filter completed transactions.
- Calculate total sales for each city.
- Sort sales from highest to lowest.
- Create a horizontal bar chart.
- Display formatted sales labels.

### Output

- Sales aggregation by city.
- Horizontal bar chart of total sales by city.

---

##  Challenge 3 – Advanced Dashboard

### Tasks

- Filter promotional transactions (`status = completed` and `discount > 0`).
- Aggregate sales performance by product.
- Calculate:
  - Total Revenue
  - Average Discount
  - Average Purchase Quantity
- Create a dashboard consisting of:
  - Scatter Plot (Price vs Total Sales)
  - Box Plot (Discount Distribution by Category)
- Generate business recommendations.

### Dashboard

- Scatter Plot: Product Price vs Total Sales
- Box Plot: Discount Distribution by Product Category

---

#  Key Findings

- The dataset was successfully cleaned by removing duplicate records and handling missing values.
- Sales performance differed across cities, indicating regional variations in customer demand.
- Promotional transactions generated significant sales revenue, although discount levels varied among product categories.
- Higher product prices did not always correspond to higher sales revenue, suggesting that sales volume also plays an important role.
- Discount distributions varied across categories, indicating opportunities to optimize promotional strategies.

---

#  Business Recommendations

### 1. Optimize Promotional Campaigns

Focus promotional campaigns on product categories that consistently generate high sales to maximize marketing effectiveness.

### 2. Strengthen Regional Marketing

Prioritize marketing efforts in cities with the highest sales performance while evaluating improvement strategies for lower-performing regions.

### 3. Improve Discount Strategy

Optimize discount policies by identifying categories where moderate discounts produce the highest revenue without significantly reducing profit margins.

---

#  Project Outputs

- ✅ Data Cleaning
- ✅ Duplicate Removal
- ✅ Missing Value Handling
- ✅ Datetime Conversion
- ✅ Sales Aggregation by City
- ✅ Horizontal Bar Chart
- ✅ Promotional Sales Dashboard
- ✅ Scatter Plot Analysis
- ✅ Box Plot Analysis
- ✅ Business Insight & Recommendations

---

#  Skills Acquired

- Data Cleaning
- Data Wrangling
- Exploratory Data Analysis (EDA)
- Data Visualization
- Business Analytics
- Marketing Analysis
- Python Programming
- Problem Solving
- Critical Thinking

---


# 📷 Project Preview

### Sales Performance by City

> *(Insert bar chart image here)*

```markdown
![Sales by City](images/bar_chart_city.png)
```

### Promotional Sales Dashboard

> *(Insert dashboard image here)*

```markdown
![Dashboard](images/dashboard.png)
```

---

