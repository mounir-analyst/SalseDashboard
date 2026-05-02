# SalseDashboard
Salse dashboard using Pivot table and Povitchart
🛒 Superstore Sales Analysis Dashboard
An interactive Excel dashboard built entirely using Pivot Tables and Pivot Charts to analyze retail sales data across categories, regions, subcategories, and time.

📊 Dashboard Overview
The workbook contains three sheets:
SheetDescriptionDashboardVisual summary with interactive Pivot ChartsPivotTableUnderlying aggregations powering the dashboardDatasetRaw transactional data (9,994 orders)

📁 Dataset
The raw dataset includes the following fields:
FieldDescriptionOrder ID / Date / Ship DateOrder timing and logisticsCustomer ID / Name / SegmentCustomer info (Consumer, Corporate, Home Office)Region / State / CityUS geographic breakdownCategory / Sub-CategoryProduct hierarchy (3 categories, 17 subcategories)Product NameIndividual productSalesRevenue per line itemQuantityUnits soldDiscountDiscount appliedProfitNet profit per line item
Coverage: Orders from 2015–2018 across the United States

📈 Key Insights from the Dashboard

Total Sales: $2,297,200 across 9,994 orders
Total Profit: $286,397
Top Category by Sales: Technology ($836K), followed by Furniture ($742K) and Office Supplies ($719K)
Top Subcategories: Phones ($330K), Chairs ($328K), Storage ($224K)
Loss-making Subcategories: Tables (-$17.7K), Bookcases (-$3.5K), Supplies (-$1.2K)
Most Customers: California (2,001), New York (1,128), Texas (985)


🛠️ How It Was Built
Step 1 — Raw Data
All analysis starts from the Dataset sheet containing 9,994 rows of transactional data.
Step 2 — Pivot Tables
Multiple Pivot Tables were created to aggregate the data by:

Category & Subcategory → Total Sales, Quantity, Profit
Region → Sales distribution
Year → Year-over-year comparison
Month → Monthly quantity trend
State → Customer count per state
Top Products → Highest-selling individual products

Step 3 — Pivot Charts
Each Pivot Table was converted into a dynamic Pivot Chart:

📊 Bar / Column Charts — Sales by category and subcategory
🍩 Donut Chart — Sales share by region
📉 Line Chart — Quantity trend by month
📊 Grouped Bar Chart — Year-over-year category comparison

Step 4 — Dashboard Assembly
All charts were arranged on the Dashboard sheet with:

Consistent color theme
Slicers linked to all charts for interactive filtering
Clean layout for presentation-ready output


✅ Skills Demonstrated

Excel Pivot Tables (multi-field aggregation)
Pivot Charts (bar, line, donut, grouped)
Dashboard design & layout
Slicer configuration for interactive filtering
Data cleaning and structured table formatting


📂 File Structure
project.xlsx
├── Dashboard       ← Interactive visual dashboard
├── PivotTable      ← Pivot Table aggregations
└── Dataset         ← Raw data (9,994 rows × 21 columns)

🚀 How to Use

Download and open project.xlsx in Microsoft Excel
Navigate to the Dashboard sheet
Use the Category and Year slicers to filter all charts interactively
Explore the PivotTable sheet to see the underlying data aggregations


🧰 Requirements

Microsoft Excel 2016 or later (Pivot Chart and Slicer support required)
