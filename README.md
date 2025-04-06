This project analyzes sales data from a Superstore using SQL for data cleaning and transformation, and Power BI for creating interactive visual dashboards.

📌 Overview This project analyzes sales data from a Superstore using SQL for data cleaning and transformation, and Power BI for creating interactive visual dashboards.

The goal is to uncover business insights like:

Top-performing regions

Sales vs Profit trends

Category-wise analysis

Shipping performance

Key KPIs & performance metrics

🧰 Tools & Technologies 🛢️ SQL (MySQL Server): For querying and preparing the dataset

📊 Power BI: For building the dashboard and visuals

🗃️ Superstore Dataset: Standard retail sales data

📈 Key Features Cleaned and transformed raw data using SQL

Created KPIs like Total Sales, Total Profit, Avg Discount, Profit Ratio

Filtered insights using:

Region

Segment

Category

Order Date (Time series)

Identified loss-making segments and profitable regions

Custom slicers and visual filters added for interactivity

🧪 Sample SQL Query Used sql Copy Edit SELECT Region, Category, SUM(Sales) AS Total_Sales, SUM(Profit) AS Total_Profit FROM Superstore GROUP BY Region, Category ORDER BY Total_Profit DESC;

📊 Dashboard Preview

<img width="618" alt="image" src="https://github.com/user-attachments/assets/e94b6d46-5153-4691-9c7c-2be08d71de96" />

<img width="623" alt="image" src="https://github.com/user-attachments/assets/efcc52e3-ccf9-40b2-a024-8a0720d6548d" />



