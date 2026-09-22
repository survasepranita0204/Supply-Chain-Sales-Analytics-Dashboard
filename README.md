# 📊 Supply Chain & Sales Analytics Dashboard

An interactive **Excel-based Supply Chain & Sales Analytics Dashboard** developed to analyze sales performance, profitability, customer segments, shipping performance, delivery status, and payment methods using the DataCo Supply Chain Dataset.

The project focuses on transforming raw supply chain data into meaningful business insights through **data cleaning, Excel formulas, PivotTables, PivotCharts, slicers, KPIs, and dashboard visualization**.

---

## 🎯 Project Objective

The objective of this project is to analyze supply chain and sales data and answer important business questions related to:

- Sales performance
- Profitability
- Customer segments
- Market performance
- Product categories
- Shipping performance
- Delivery delays
- Payment methods
- Order status

The final dashboard provides an interactive view of the business performance and highlights areas that may require further attention.

---

## 🛠️ Tools & Technologies

- **Microsoft Excel**
- Excel Tables
- Excel Formulas
- XLOOKUP
- IF / IFERROR
- SUM / COUNT / AVERAGE
- PivotTables
- PivotCharts
- Slicers
- Timeline
- Conditional Formatting
- Data Cleaning
- Data Visualization

---

## 📂 Dataset

**Dataset:** DataCo Smart Supply Chain Dataset

The dataset contains approximately **180,000+ records** covering sales, orders, products, customers, markets, shipping, delivery, payment methods, and profitability.

### Important fields used in the analysis

- Order Id
- Order Date
- Sales
- Order Profit Per Order
- Order Item Quantity
- Market
- Order Region
- Customer Segment
- Category
- Shipping Mode
- Delivery Status
- Late Delivery Risk
- Order Status
- Payment Type
- Days for Shipment (Scheduled)
- Days for Shipping (Real)

---

## 🔄 Project Workflow

The project followed a structured data analytics workflow:

### 1. Data Collection
Collected the DataCo Supply Chain dataset for analysis.

### 2. Data Cleaning
- Reviewed the dataset for inconsistencies
- Organized the data into an Excel Table
- Checked important fields and values
- Created calculated fields where required

### 3. Data Analysis
Used Excel formulas and PivotTables to analyze:

- Sales
- Profit
- Orders
- Quantity
- Customer segments
- Markets
- Product categories
- Shipping modes
- Delivery performance
- Payment methods

### 4. Dashboard Development
Created an interactive dashboard using:

- KPI cards
- Charts
- PivotCharts
- Slicers
- Data labels
- Conditional formatting

### 5. Business Insights & Recommendations
Identified important trends and translated them into actionable business recommendations.

---

## 📌 Dashboard KPIs

The dashboard includes the following key performance indicators:

| KPI | Value |
|---|---:|
| Total Sales | $36.78M |
| Total Profit | $3.97M |
| Total Orders | 65.75K |
| Total Quantity | 384K+ |
| Average Order Value | $559.45 |
| Profit Margin | 10.78% |
| Late Delivery Rate | 54.83% |
| Average Delivery Delay | 0.57 Days |

> KPI values are based on the current analysis and may vary slightly depending on dataset version and calculation definitions.

---

## 📊 Dashboard Analysis

The dashboard covers the following areas:

### Sales Analysis
- Monthly Sales Trend
- Sales by Market
- Sales by Product Category

### Profitability Analysis
- Profit by Market
- Profit by Product Category
- Overall Profit Margin

### Shipping & Delivery Analysis
- Late Delivery Rate by Shipping Mode
- Delivery Status Distribution
- Average Delivery Delay

### Customer & Payment Analysis
- Customer Segment Performance
- Payment Type Distribution

---

## 🔍 Key Insights

### 🌍 Market Performance
Europe contributes the largest share of total sales, followed by LATAM.

Europe and LATAM together account for more than half of total sales.

### 🚚 Delivery Performance
54.83% of shipments are classified as late, highlighting delivery performance as an important area for operational analysis.

### 📦 Shipping Mode
First Class has the highest late-delivery rate among the analyzed shipping modes, while Standard Class has a comparatively lower late-delivery rate.

### 👥 Customer Segments
The Consumer segment contributes the largest share of sales, followed by Corporate and Home Office segments.

### 💳 Payment Methods
Debit is the most frequently used payment method, followed by Transfer.

---

## 💡 Business Recommendations

Based on the analysis, the following recommendations were identified:

### 1. Reduce Delivery Delays
Investigate the major causes of late deliveries and optimize shipping operations to improve delivery performance.

### 2. Review First Class Shipping Performance
Analyze the operational bottlenecks contributing to the high late-delivery rate for First Class shipments.

### 3. Strengthen Key Markets
Maintain strong performance in high-contributing markets such as Europe and LATAM while exploring opportunities in lower-performing markets.

### 4. Improve Customer Segment Performance
Continue retaining Consumer customers while identifying opportunities to increase sales from Corporate and Home Office segments.

---

## 📈 Dashboard Features

The dashboard provides interactive filtering through slicers for:

- Market
- Region
- Customer Segment
- Category
- Shipping Mode
- Order Status

Users can filter the dashboard to analyze specific business segments and observe how the KPIs and visualizations change.

---

## 🖼️ Dashboard Preview

![Supply Chain & Sales Analytics Dashboard](Dashboard/Supply_Chain_Sales_Dashboard.png)

---

## 📁 Project Structure

```text
Supply-Chain-Sales-Analytics/
│
├── Dashboard/
│   ├── Supply_Chain_Sales_Dashboard1.png
│   └── Supply_Chain_Sales_Dashboard2.png
│
├── DataCoSupplyChainDataset.xlsx
│
└── README.md
