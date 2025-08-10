#  Sales Performance Analysis 

##  Project Overview
This project presents a comprehensive analysis of **sales performance**, customer trends, product distribution, and supplier efficiency. The goal is to provide clear insights for strategic decision-making using historical and current-year sales data.

The analysis is visualized through **interactive dashboards**, showcasing trends by **time period, geography, product category, payment type, suppliers, and customers**.

<img width="1536" height="560" alt="ChatGPT Image Aug 10, 2025, 10_11_24 PM" src="https://github.com/user-attachments/assets/0d99e79b-de0d-4238-aca6-3678b5cdb401" />

---

##  Dataset Sources & Description
**Sources:**
- Point-of-Sale (POS) transaction logs
- Supplier inventory and shipment records
- Customer database
- Historical sales archives

**Dataset Description:**
- **Period Covered:** 2014–2021 (with detailed breakdown for current and previous years)
- **Data Points:**  
  - Sales amount (USD)
  - Quantity sold (units)
  - Unit price (USD)
  - Customer count
  - Product categories
  - Payment types
  - Geographic regions (countries, divisions)
  - Supplier quantities

---

##  Objectives
1. Measure **Year-over-Year (YoY)** sales and quantity performance.
2. Identify **top-performing products, customers, suppliers, and countries**.
3. Understand **monthly and weekly sales trends**.
4. Evaluate the **impact of payment methods** on sales.
5. Detect **patterns** that can inform marketing and inventory strategies.

<img width="1024" height="474" alt="ChatGPT Image Aug 10, 2025, 10_15_21 PM" src="https://github.com/user-attachments/assets/fe57d1c7-9946-4dc8-bfb5-c6609a5406b1" />

---

##  Tools Used
- **Microsoft Excel / PivotTables** – for initial aggregation and computation.
- **Power BI** – for interactive dashboards and data visualization.
- **Python (Pandas, NumPy, Matplotlib)** – for advanced data preparation and exploratory analysis.
- **GitHub** – for version control and documentation.

---

##  Data Preparation & Cleaning
Steps taken:
1. **Data Consolidation** – Merged multiple raw datasets into a single structured format.
2. **Data Type Formatting** – Ensured proper formatting for dates, numeric values, and currency.
3. **Handling Missing Values** – Imputed missing sales and quantity records based on historical averages.
4. **Outlier Detection** – Flagged abnormal spikes or drops in sales for further review.
5. **Standardization** – Unified product category names, supplier IDs, and country codes.

---

##  Exploratory Data Analysis (EDA)
EDA was performed to uncover patterns before building the dashboard:
- Distribution of sales across **months, weeks, and years**.
- Correlation between **unit price and quantity sold**.
- Customer purchase frequency distribution.
- Supplier contribution by volume.
- Payment method preferences by region.

---

##  Data Analysis
Key metrics calculated:
- **YoY Growth Rate**
- **Total Sales**: $105.4M (Current Year) vs $91M (Previous Year) → **+16.12%**
- **Total Quantity**: 6M units (Current Year) vs 5M units (Previous Year) → **+16.12%**
- **Average Unit Price**: Stable at ~$18
- **Customer Base**: 9.2K customers (no significant change YoY)
- **Top Selling Products**: Energy/Protein beverages, Healthy Food, Kitchen Supplies
- **Top 5 Countries**: India, Bangladesh, Lithuania, Poland, Germany
- **Top Division**: Dhaka ($41M)

---

##  Dashboards
The analysis was visualized in **Excel and Power BI** dashboards, covering:
1. **Year-over-Year Performance**
2. **Weekly & Monthly Sales Trends**
3. **Product Category Analysis**
4. **Top Customers & Suppliers**
5. **Geographic Sales Mapping**
6. **Payment Method Performance**

<img width="1230" height="678" alt="E-COMMERCE SALES 001" src="https://github.com/user-attachments/assets/206cf866-e351-4319-9eba-2cac665f6c67" />

<img width="1237" height="660" alt="E-COMMERCE SALES 002" src="https://github.com/user-attachments/assets/cb16bd1b-3e14-41bc-8b72-14d6d75bc1b5" />

---

##  Key Findings
- **Sales & Quantity Growth:** Both increased by 16.12%, indicating healthy demand expansion.
- **Price Stability:** Unit price remained stable despite increased volume.
- **High Dependency on Card Payments:** ~90% of sales made via card.
- **Geographic Concentration:** 5 countries account for more than 50% of total sales.
- **Division Performance Gap:** Dhaka significantly outperforms other regions.

---

<img width="1536" height="701" alt="ChatGPT Image Aug 11, 2025, 12_30_02 AM" src="https://github.com/user-attachments/assets/0def1620-eed9-4488-8fa2-65846fe4a131" />


##  Recommendations
1. **Expand in High-Performing Countries** – Focus marketing efforts in Bangladesh, India, and Lithuania.
2. **Promote Underperforming Payment Methods** – Offer incentives for mobile and cash payments to diversify transaction channels.
3. **Strengthen Supplier Relationships** – Secure better terms from top-volume suppliers like DENIMACH LTD and Indo Count Industries.
4. **Seasonal Marketing** – Leverage the spike in 4th-week sales through targeted campaigns.
5. **Product Mix Optimization** – Increase stock of best-selling categories such as beverages and healthy food.

---

## Limitations
- Data may contain **unrecorded offline sales** not captured in the system.
- **External market factors** (e.g., economic downturn, supply chain disruptions) are not modeled.
- Unit price rounding may cause small deviations in total revenue calculations.

---

##  Conclusion
This analysis provides a clear view of sales performance and market dynamics. By focusing on **geographic expansion, payment method diversification, and supplier optimization**, the business can sustain and accelerate growth.

---

##  References
- Company POS Transaction Reports (2014–2021)
- Supplier Shipment Logs
- Customer Database Records
- Market Reports on Retail Trends

---

