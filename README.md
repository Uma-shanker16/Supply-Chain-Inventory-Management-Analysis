# End-to-End Power BI Project: Inventory & Supply Chain Management

## Project Background
This project simulates a real-world supply chain analytics environment where a data analyst supports logistics and operations teams in optimizing inventory performance, warehouse capacity, and transportation efficiency.

The goal is to transform raw logistics and inventory data into actionable insights using Power BI and help organizations improve operational efficiency, reduce costs, and meet customer demand.

Insights and recommendations are provided on the following key areas:

- Inventory Performance & Turnover
- Warehouse Utilization
- Transportation Cost Optimization
- Demand, Lead Time & Backorder Analysis


---

## Data Structure & Initial Checks

The dataset was sourced from structured CSV/text files representing inventory, orders, warehouse capacity, transportation, and sales metrics.

Key data fields:

- Inventory Levels  
- Warehouse Capacity  
- Region  
- Category  
- Sales Units  
- Transportation Costs  
- Lead Time  
- Back Orders  
- Order Status  

Initial checks performed:

- Data type corrections (dates, numeric, boolean)
- Missing value handling
- Standardized column naming
- Validation of calculated metrics
- Consistency checks across records

---

## Executive Summary

### Overview of Findings

Warehouse utilization averaged around 35%, showing unused capacity and optimization potential. Transportation costs varied significantly across regions and product categories. Sales demand surged in recent years, increasing backorders and exposing gaps in demand planning and replenishment strategies.

---

## Insights Deep Dive

### Inventory Performance & Turnover

- Inventory turnover remained moderate, indicating stable but improvable sales velocity.
- Days Sales of Inventory averaged ~16 days, reflecting manageable stock levels.
- Low-performing categories showed slower movement and increased holding costs.
- Demand fluctuations impacted supply planning and restocking strategies.

---

### Warehouse Utilization

- Warehouse utilization averaged 34–35%, below optimal operational targets.
- Underutilized capacity indicated inefficiencies in storage planning.
- Regional differences revealed imbalance in distribution.
- Improved allocation strategies can reduce infrastructure costs.

---

### Transportation Cost Optimization

- Furniture in the North region recorded the highest transportation costs.
- Electronics in the West region showed elevated shipping expenses.
- Cost variation linked to demand concentration and logistics planning.
- Route optimization and vendor strategy can lower expenses.

---

### Demand, Lead Time & Backorders

- Average lead time measured approximately 16 days.
- Backorders increased during demand spikes.
- Fulfilled vs pending order analysis exposed operational bottlenecks.
- Sales boom in recent years highlighted forecasting gaps.

---

## Recommendations

Based on analysis, operations and supply chain teams should consider:

- Optimize warehouse allocation to reduce unused capacity
- Improve logistics planning to lower transportation costs
- Strengthen demand forecasting and replenishment models
- Align procurement with inventory turnover trends
- Reduce lead time to improve customer satisfaction

---

## Assumptions and Caveats

- Dataset represents a simulated supply chain environment
- Missing records handled using historical averages
- Lead time assumed consistent across manufacturing cycles
- Transportation anomalies treated as operational outliers
- Single-table structure limits advanced relational modeling

---

## KPIs Used in the Dashboard

### Warehouse Utilization Rate
Warehouse Utilization % =
(SUM(Inventory Levels) / SUM(Warehouse Capacity)) * 100

### Inventory Turnover Ratio
DSI =
(Average Inventory / Cost of Goods Sold) * Number of Days

### Inventory Turnover Ratio
Inventory Turnover =

Cost of Goods Sold / Average Inventory
