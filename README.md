![Sample Image](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRztL0WzSHxYdzc8FmFZ8pCYA8GxsAThVhioAoQIrfPmnM2527iMnLvRXyd_5VO1xYdRg&usqp=CAU)

# 🛒 Retail Sales Insights & Optimization – Walmart  
### *By Yashvardhan Agarwal*

---

## 📖 About
This project, created by **Yashvardhan Agarwal**, analyzes Walmart's sales data to identify high-performing branches and products, examine sales patterns, and understand customer behavior.  
The primary objective is to enhance and optimize sales strategies.  
The dataset utilized in this project is sourced from the **Kaggle Walmart Sales Forecasting Competition**.

---

## 🎯 Purposes of the Project
The main goal of this project is to gain insights from Walmart's sales data and explore the various factors that influence sales across different branches.

---

## 🧾 About Data
This project's data was obtained from the Kaggle Walmart Sales Forecasting Competition and encompasses sales transactions from three Walmart branches situated in **Mandalay, Yangon, and Naypyitaw**.
## About Data
This project's data was obtained from the Kaggle Walmart Sales Forecasting Competition and it encompasses sales transactions from three Walmart branches situated in Mandalay, Yangon, and Naypyitaw, respectively. 

The data contains 17 columns and 1000 rows:
| Column            | Description                                   | Data Type        |
|-------------------|-----------------------------------------------|------------------|
| invoice_id        | Invoice of the sales made                     | VARCHAR(30)      |
| branch            | Branch at which sales were made               | VARCHAR(5)       |
| city              | The location of the branch                    | VARCHAR(30)      |
| customer_type     | The type of the customer                       | VARCHAR(30)      |
| gender            | Gender of the customer making purchase        | VARCHAR(10)      |
| product_line      | Product line of the product sold               | VARCHAR(100)     |
| unit_price        | The price of each product                     | DECIMAL(10, 2)   |
| quantity          | The amount of the product sold                 | INT              |
| VAT               | The amount of tax on the purchase             | FLOAT(6, 4)      |
| total             | The total cost of the purchase                | DECIMAL(12, 4)   |
| date              | The date on which the purchase was made       | DATETIME         |
| time              | The time at which the purchase was made       | TIME             |
| payment           | The total amount paid                         | DECIMAL(10, 2)   |
| cogs              | Cost Of Goods sold                            | DECIMAL(10, 2)   |
| gross_margin_pct  | Gross margin percentage                       | FLOAT(11, 9)     |
| gross_income      | Gross Income                                  | DECIMAL(12, 4)   |
| rating            | Rating                                        | FLOAT(2, 1)      |


---

## 🔍 Analysis List

### 1️⃣ Product Analysis
Perform an analysis to gain insights into different product lines, determine top-performing ones, and identify areas for improvement.

### 2️⃣ Sales Analysis
Analyze sales trends to evaluate the effectiveness of sales strategies and determine necessary modifications.

### 3️⃣ Customer Analysis
Identify customer segments, purchasing trends, and the profitability of each segment.

---

## ⚙️ Approach Used

### **1. Data Wrangling**
- Examine data for NULL or missing values and handle them.  
- Build database and table; ensure `NOT NULL` constraints prevent null entries.

### **2. Feature Engineering**
Create new columns for better insights:
- **time_of_day** – Categorize as Morning, Afternoon, or Evening.  
- **day_name** – Extract day of the week (Mon–Sun).  
- **month_name** – Extract month of transaction (Jan–Dec).  

### **3. Exploratory Data Analysis (EDA)**
Perform EDA to answer project questions and derive insights.

---

## 💡 Business Questions to Answer

### 🏙️ Generic Questions
1. How many distinct cities are present in the dataset?  
2. In which city is each branch situated?  

---

### 🛍️ Product Analysis
1. How many distinct product lines are there?  
2. What is the most common payment method?  
3. What is the most selling product line?  
4. What is the total revenue by month?  
5. Which month recorded the highest COGS?  
6. Which product line generated the highest revenue?  
7. Which city has the highest revenue?  
8. Which product line incurred the highest VAT?  
9. Add a column `product_category` indicating 'Good' or 'Bad' based on average sales.  
10. Which branch sold more products than average?  
11. What is the most common product line by gender?  
12. What is the average rating of each product line?  

---

### 💰 Sales Analysis
1. Number of sales made in each time of the day per weekday.  
2. Identify the customer type that generates the highest revenue.  
3. Which city has the largest VAT percent?  
4. Which customer type pays the most VAT?  

---

### 👥 Customer Analysis
1. How many unique customer types does the data have?  
2. How many unique payment methods are there?  
3. Which is the most common customer type?  
4. Which customer type buys the most?  
5. What is the gender of most customers?  
6. What is the gender distribution per branch?  
7. Which time of the day do customers give the most ratings?  
8. Which time of the day do customers give most ratings per branch?  
9. Which day of the week has the best average ratings?  
10. Which day of the week has the best average ratings per branch?  

---

## 👨‍💻 Author
**Yashvardhan Agarwal**  
_Data Analyst | Developer | Tech Enthusiast_  
📧 *[Add your email or LinkedIn here if you want]*  


