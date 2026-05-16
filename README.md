# sales-perfomance-analysis
Sales data analysis project with KPIs and insights

This project analyzes two years of sales data (200 rows) to uncover revenue trends, profitability drivers, regional performance, and the impact of discounts on overall business performance.
It demonstrates data cleaning, KPI building, and dashboard development using Google Sheets.

📂 Dataset
The dataset includes:

OrderID – Unique order identifier

OrderDate – Date of purchase

Product – Product name

Category – Product category

Region – Sales region

Sales – Revenue generated

Cost – Cost of goods sold

Discount – Discount applied (%)

CustomerType – New or Returning customer

👉 The dataset intentionally includes missing values, duplicates, and inconsistencies to simulate real-world business data.

🛠 Data Cleaning
Removed duplicate rows

Handled missing values (mean imputation for Sales/Cost, 0 for Discount)

Created Profit column (Sales – Cost)

Extracted Month & Year from OrderDate

Validated data types

📈 Key Performance Indicators (KPIs)
Total Revenue (2 years): ₹81,04,567

Total Profit: ₹23,27,492.99

Profit Margin: 28.72%

Average Order Value: ₹42,655

🔹 Region-wise Revenue Contribution
Region	Contribution
West	25.9%
East	21.6%
North	22.6%
South	29.9%


🔹 Top Performing Products
Product	Sales
Mobile	1,580,824
Mouse	1,463,263
Tablet	1,371,128
Headphones	1,345,183
Laptop	1,181,538
Keyboard	1,162,631


📊 Analysis Highlights
Seasonality: Highest sales in March (₹12,27,662), lowest in December (₹385,707)

Discount Impact: High discounts (>20%) reduce profit margins by ~6.8%

Customer Contribution:

New Customers → 56.19% of revenue

Returning Customers → 43.18% of revenue

Regional Profitability:

Highest → South (30%)

Lowest → East (22%)

💡 Business Insights
Revenue peaks during festive months → leverage seasonal campaigns

Aggressive discounting reduces margins → optimize discount strategy

Electronics category drives highest revenue → prioritize inventory planning

Returning customers contribute significantly → strengthen retention programs
