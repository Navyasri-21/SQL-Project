# 🏥 Healthcare Data Analysis Project

This project focuses on exploring and analyzing a healthcare dataset using **SQL**, **data cleaning techniques**, and **data visualization**. The goal is to derive meaningful insights to support decision-making in the healthcare domain.

---

## 📊 Project Overview

- **Dataset**: Public healthcare dataset (e.g., patient records, treatments, hospital data)
- **Tools Used**:
  - SQL (for querying and data analysis)
  - Python (for data cleaning and visualization)
  - Pandas, Matplotlib
- **Skills Applied**:
  - Data Cleaning
  - Joins & Subqueries in SQL
  - Aggregation & Filtering
  - Data Visualization
  - Insight Writing

---## 🔄 Data Preparation Workflow

1. **ZIP to CSV Conversion**
   - [your zip extraction code]

2. **Database Connection**
   - [your database connection code]

3. **SQL Querying and Analysis**
   - [your SQL example]

   

## 📁 Folder Structure
├── data/ # Raw dataset from kaggle
├── notebooks/ # Colab notebooks
├── sql_queries/ # SQL files with analysis
├── visualizations/ # Charts and plots
└── README.md # Project documentation


## 📌 Key Features
- ✅ 20+ SQL queries for insights
- ✅ Advanced SQL techniques: joins, case statements, and window functions
- ✅ Cleaned data using Pandas
- ✅ Visualizations for trends in patient visits, costs, outcomes
- ✅ Summary of insights and takeaways


QUESTIONS:
1. Query to check the first few rows of the table
2. Run SQL query to fetch all rows from 'my_table
3. Query the details who are from georgia
4. query the schema of the table
5. What are the unique years available in the dataset?
6. How many records are there for each year?
7. What are the different locations (states/regions) in the data?
8. What is the average Data_Value across all records?
9. What is the highest and lowest Data_Value recorded?
10. Which state (LocationDesc) has the highest average Data_Value?
11. What are the distinct TopicDesc entries (health topics covered
12. How many measures (MeasureDesc) are there for each topic?
13. For a given topic, how do values vary across states?
14. What are the average values per state for a specific year?
15. Which states have Data_Value greater than a threshold (e.g., 50)?
16. What are the top 5 states with the highest values for a specific measure
17. How does Data_Value vary by Gender?
18. What are the most common combinations of Race and Data_Value?
19. What is the trend of Data_Value across different Age groups?
20. How does education level (Education) impact Data_Value?
21. How many rows have null or missing Data_Value?
22. What is the average Data_Value_Std_Err for each topic?
23. Which rows have the largest Low_Confidence_Limit and High_Confidence_Limit gap?
24. What is the average Data Value per year?
25. visualize the year and Data value

🧹 Data Cleaning Highlights

- Removed null/missing values
- Standardized column names
- Filtered invalid entries
- Converted data types (dates, strings)

## 📈 Visualizations

- Line plot of patient visits over months
- Bar chart of most common diagnoses
- Pie chart of treatment outcomes

- ## 💡 Insights

- Most patient visits occur in Q2 and Q3
- Diabetes and Hypertension are top diagnoses
- Success rate of Treatment A is 85%+
