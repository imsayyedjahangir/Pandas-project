# Diwali Sales Analysis using Python & Pandas

## 📌 Project Overview
This project focuses on performing an end-to-end data analysis on a retail sales dataset collected during the Diwali festival season in India. The purpose of this analysis is to help businesses identify customer purchasing patterns, top-performing demographics, regional trends, and product preferences to make data-driven marketing and inventory decisions.

Using Python (Pandas, Matplotlib, and Seaborn), the raw data was cleaned, transformed, and analyzed to uncover actionable business insights. The notebook demonstrates real-world EDA (Exploratory Data Analysis) techniques and visualization skills—essential for any data analyst or data scientist role.

## 🎯 Objective
Clean and preprocess the dataset for analysis

Explore customer demographics like gender, age, marital status, and region

Identify which product categories generate the most sales

Reveal which regions/states contribute the most to revenue

Understand customer behavior to guide targeted marketing strategies

 ## 🧰 Tools & Technologies Used
Tool	Purpose
Python	Core programming language
Jupyter Notebook	Interactive coding and documentation
Pandas	Data loading, cleaning, transformation
NumPy	Numerical operations
Matplotlib	Visualization of categorical and numerical data
Seaborn	Statistical plotting and aesthetic charts

## 🗃️ Dataset Description
File Name: Diwali_Sales_Data.csv

Size: ~11 KB

Original Columns: 15+ (reduced after cleaning)

Key Columns Used:

Gender

Age

State

Marital Status

Product_Category

Orders

Amount

Dataset contains anonymized transaction-level sales data collected during a Diwali campaign by a retail company.

## 🧹 Data Cleaning & Preprocessing Steps
✅ Dropped Irrelevant Columns such as 'Status' and 'unnamed1' using df.drop()
✅ Removed Null Values using df.dropna()
✅ Converted Data Types: Changed Amount from float/object to integer for numerical computation
✅ Renamed Columns: Used df.rename() to improve readability (e.g., 'Marital_Status' → 'Shaadi')
✅ Standardized formats for categorical fields (gender, age group) for cleaner analysis

## 🔍 Exploratory Data Analysis (EDA)
1️⃣ Gender-based Insights
Countplot revealed higher purchase frequency from male customers

Revenue comparison showed males contributed more to total sales

2️⃣ Age Group Trends
Age group 26–35 had the highest transaction volume and revenue

Highlighted the importance of targeting millennials in festive marketing

3️⃣ Marital Status & Spending
Analyzed spending patterns of married vs unmarried individuals

Married customers tend to make slightly more high-value purchases

4️⃣ Regional Sales Distribution
States like Uttar Pradesh, Maharashtra, and Karnataka emerged as top performers

Visualization using groupby('State') and sum('Amount') provided a clear sales leaderboard

5️⃣ Product Category Analysis
Identified clothing and electronics as most purchased categories

Helped narrow down popular SKUs and optimize inventory

## 📊 Key Visualizations Created
Bar Charts (Gender, Age group, State-wise sales, Product categories)

Count Plots for frequency-based comparisons

Seaborn styling for clean, publication-ready charts

Custom labels and annotations to make charts self-explanatory

## 📈 Key Business Insights

Insight	Details

💡 Top Buyer Segment	Age group 26–35, primarily male customers

📍 Top Performing States	Uttar Pradesh, Maharashtra, Karnataka

🛍️ Most Popular Categories	Clothing & Electronics

💸 High Revenue Contributors	Married males in 26–45 age group

📦 Sales Opportunity	Focused marketing on millennials in urban metros


## 💼 Skills Demonstrated

-Data cleaning and wrangling

-Real-world business problem solving using data

-Exploratory data analysis with Pandas

-Visualization storytelling with Seaborn and Matplotlib

-Ability to interpret data into business recommendations

-Clean, well-commented Jupyter notebook suitable for team handoff or reporting


## 🔄 Future Enhancements
Compare Diwali sales across multiple years

Perform cohort analysis (repeat buyers vs first-time buyers)

Integrate promotional campaign performance metrics

Build an interactive dashboard (e.g., using Plotly or Power BI)


## 🧠 Final Thoughts
This project is a practical example of how data analytics can help companies understand customer behavior, regional demand, and product preferences during critical retail periods like Diwali. It combines both technical skills and business acumen, making it a strong portfolio piece for aspiring data analysts.

