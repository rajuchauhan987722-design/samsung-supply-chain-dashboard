# samsung-supply-chain-dashboard
Supply Chain Star Schema Data Model with multiple fact tables and interactive Power BI dashboard.
📌 Project Overview
This project is a Supply Chain & Logistics Analytics Dashboard built using Power BI.
The main objective of this project is to practice and implement:
Star Schema Data Modeling
One-to-Many Relationships
Fact and Dimension Tables
Business KPI Development
This project simulates real-world supply chain operations including sales, shipment, procurement, production, and inventory management.
🏗️ Data Modeling Approach
This project follows a Star Schema architecture with proper One-to-Many (1:M) relationships.
🔹 Dimension (1) → Fact (Many)
All relationships are designed as:
Dimension tables filter fact tables
Single-direction filtering
No many-to-many relationships
This improves performance and follows BI best practices.
📂 Data Structure
🔹 Fact Tables
fact_sales.csv
fact_shipment.csv
fact_inventory.csv
fact_production.csv
fact_procurement.csv
These tables store measurable business data like revenue, quantity, shipment details, costs, and inventory values.
🔹 Dimension Tables
dim_date.csv
dim_product.csv
dim_customer.csv
dim_supplier.csv
These tables provide descriptive information used for filtering and analysis.
📊 Dashboard Sections
1️⃣ Overview
Total Revenue
Profit & Profit Margin
Shipment Quantity
Inventory Value
Perfect Order %
2️⃣ Supplier Analysis
Lead Time
Unit Cost
Order Quantity
3️⃣ Inventory & Production
Safety Stock
Defect Units
Inventory Value
4️⃣ Shipment Analysis
Delivered %
Delay by Carrier
Shipping Cost
5️⃣ Customer & Sales
Revenue by Platform
Revenue by Channel
Monthly Growth
📈 Key KPIs
Total Revenue: 176.95M
Profit: 48.56M
Profit Margin: 27.44%
Total Shipments: 8K
Shipment Quantity: 3M
Perfect Order Rate: 75.29%
🛠️ Tools Used
Power BI
CSV Data Files
Star Schema Data Modeling
DAX Measures
🎯 What I Learned
Designing Fact and Dimension tables
Creating One-to-Many relationships
Building KPIs in Power BI
Understanding Supply Chain analytics
Creating multi-page interactive dashboards
👨‍💻 About Me
I am a fresher learning Data Modeling and Business Intelligence, and this project reflects my hands-on practice and understanding of core BI concepts.
