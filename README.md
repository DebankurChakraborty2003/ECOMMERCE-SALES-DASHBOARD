# ECOMMERCE-SALES-DASHBOARD
A dynamic, interactive data visualization tool designed to analyze Year-To-Date (YTD) e-commerce performance across product categories, geographic regions, customer segments, and shipping channels. 
## Short Description & Purpose
The Ecommerce Sales Dashboard provides executive-level visibility into overall sales performance, profitability, order volume, and year-over-year (YoY) metrics. Built to bridge high-level KPIs with granular product and geographic breakdowns, this tool helps retail analysts, operations teams, and business strategists identify sales trends, optimize product portfolios, and resolve logistical bottlenecks.  
## Tech Stack
 Power BI Desktop – Primary platform used for visualization, interactive report design, and layout implementation. 
 Power Query – Used for data transformation, cleaning, and preparing transaction-level sales data.
 DAX (Data Analysis Expressions) – Applied to construct dynamic time-intelligence calculations (YTD Sales, PYTD Sales, YoY Growth %), KPI variances, and    ranking metrics.    
## Data Source
Source Data: Transactional e-commerce store dataset containing sales revenues, profit margins, order quantities, customer segments, regional locations, shipping modes, and product categories.  
( https://drive.google.com/drive/folders/1vnI_RR3iDTLb6dH_tluCSsPqWcXPRHKR )
##  Key Features & Highlights
### Business Problem
E-commerce businesses process large volumes of transactional data across multiple states, customer segments, and delivery methods. Without a centralized analytics platform, management struggles to quickly determine: 
- Which product categories drive year-over-year growth vs. revenue decline.
- Regional underperformance and geographic demand concentration.
- Top-performing products vs. bottom-performing items that may require inventory clearance.   
### Goal of the Dashboard
- Provide an immediate executive summary of core performance metrics (Revenue, Profit, Quantity, Margin) with year-over-year growth context.
- Enable seamless cross-filtering by customer segment and geographic region.
- Offer product-level ranking to pinpoint underperforming stock items.
## Walkthrough of Key Visuals
1. Segment Slicers & Filters (Top Right)
   - Interactive buttons allowing users to instantly filter the entire dashboard by Consumer, Corporate, or Home Office segments.
2. Top-Level Metric Cards & Sparklines (Top Section)
   - YTD Sales: $11.53M (▼ -0.83% YoY) with trend sparkline.
   - YTD Profit: $1.34M (▲ 4.50% YoY) with trend sparkline.
   - YTD Quantity: #107.2K (▼ -7.29% YoY) with trend sparkline.
   - YTD Profit Margin: 11.58% (▲ 5.37% YoY) with trend sparkline.
3. Sales by Category (Middle Left Table)
   - Displays current YTD Sales, PYTD (Prior Year-To-Date) Sales, and YoY Growth indicators across Furniture, Office Supplies, and Technology categories.
4. Sales by State (Bottom Left Map)
   - Interactive bubble map displaying sales distribution across US territories (Central, East, South, West regions), helping spot geographical hotspots.
5. Product Performance Rankings (Center Column)
   - Top 5 Products YTD Sales: Bar chart highlighting top revenue generators such as Staple envelope ($57K) and Staples ($52K).
   - Bottom 5 Products YTD Sales: Identifies lowest performing products down to Rediform S.O.S. Phone Message... ($179.99).
6. Regional & Delivery Breakdown (Right Column)
   - YTD Sales by Region: Donut chart detailing revenue share across West (32.22%), East (28.42%), Central (23.19%), and South (16.17%).
   - YTD Sales by Shipment Type: Donut chart detailing distribution across Standard Class (60.51%), Second Class (19.22%), First Class (15.1%), and Same      Day (5.17%).
## Business Impact & Insights
- Margin Optimization: Despite a slight decline in YTD Sales (-0.83%), YTD Profit grew by +4.50% and Margin expanded by +5.37%, indicating improved pricing strategies or lower cost of goods.
- Logistics & Delivery Strategy: Standard Class accounts for 60.51% of shipments. Operations can focus on optimizing standard logistics routes while testing incentives for premium shipping methods.
- Inventory Management: Clear distinction between Top 5 and Bottom 5 items assists inventory teams in restocking high-demand items (Staple envelopes) and phasing out low-turnover stock.
## Dashboard Preview
![Dashboard Preview]()
