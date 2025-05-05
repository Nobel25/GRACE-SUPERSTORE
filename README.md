GRACE SUPERSTORE


MY TABLE CONTENT

1. PROJECT OVERVIEW
2. DATASET SOURCE
3. TOOLS
4. DATA CLEANING
5. EXPLORATORY ANALYSIS
6. DATA ANALYSIS


  
PROJECT OVERVIEW

The projects aims to analyze the Superstore trends at [sample superstore] using the provided dataset.
It identify patterns and potential impacts on the company's sales, profit and the maximun quantity the company had sold.
The findings will support decision-makings and strategic planning for marketing management and more profits.


DATASET SOURCE

This datasdet was obtained through a third party and handed to me by Neovarsity Institution

TOOLS

• Excel Data Extraction

• PowerBi - Data Cleansing

• PowerBi - Data Visualization

DATA CEANING

1. Load the Data
2. Open PowerBi Desktop
3. Click Home → Get Data → Excel
4. Select the Sample - Superstore.xlsx and choose the sheets(s) Orders,People and Returns
5. Click Transform Data → Open Power Query Editor
6. Remove unnecessary columns like Row ID
7. I fixed Data Types by making sure Order Date and Ship Date are set as Date
8. Removed duplicates in Order ID
9. Cleaned up text columns such as Customer Name (trim spaces)

STEP - BY - STEP POWER QUERY    
• Home → Transform Data (Open Power Query)

• Remove Row ID: Right Click on Row ID column → Remove

• Set Data Types: Click each collumn's small icon(e.g.,123,ABC). Assign Date to Order Date and Ship Date. Assign Decimal Number to Sales, Profit, Discount & Quantity.

• Trim and Clean text: Select multiple text columns → Transform Tab → Format → Trim → Format again → Clean

• Remove Duplicates: Highlight Order ID and Product Name → Remove Duplicates

• Replace Nulls: Select columns like Discount → Transform tab → Replace Values → Repplace Null with 0

• Add Order Year column (Optional): Select Order Date → Add column tab → Date → Year

EXPLANATORY ANALYSIS

PAGE 1 - SALES REPORT

This dashboard include the following metrics and visuals: KPIs:

• Total Sales

• Maximum of Saales

• Average Sales

Visual Reports:

• Sales by Sub-Category

• Average of Sales by Segment

• Sales by State and City

• Sales by Ship Mode

• Sales by Region

PAGE 2- PROFIT REPORT

This page will focus on profitability using the following metrics: KPIs:

• Total Profit

• Total Quantity

Visual Reports

• Profit by Category

• Profit by Segment

• Profit by Date

• Profit by Region

• Profit by Sub-Category

DATA ANALYSIS

1. Opened main PowerBi canvas. Clicked Home → Close and Apply ( after cleaning Power Query)
2. Create Calcuated measures (KPIs). Use DAX ( Data Analysis Expressions) for advanced KPIs

    • Total Sales: Total Sales = SUM ('Order'[Sales]) • Maximum Sales: Max Sales = MAX ('Order'[Sales]) • Average Sales: Average Sales = AVERAGE('Order'[Sales])
3. Once created, insert Card Visuals → Drag each measure into a card → Set titles (e.g., "Total Sales").
4. Create Visual Reports:

   ∘ Report - Chart Type - Fields

   ∘ Sales by Sub-Category - Bar Chart - Sub-Category (Axis), Sales(Values)

   ∘ Average Sales by Segment - Column Chart - Segment(Axis), Sales (Average aggregation)

   ∘ Sales by State and City - Map Chart - State/City (Location or Row/Column), Sales

   ∘ Sales by Ship Mode - Donut Chart - Ship Mode (Legend), Sales

   ∘ Sales by Region - Bar Chart - Region (Axis), Sales (Values)








