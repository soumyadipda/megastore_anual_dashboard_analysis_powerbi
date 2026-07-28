# 🛒 Megastore Annual Dashboard – Power BI Project
_Developed an interactive Power BI dashboard to monitor sales, profit, quantity, top-performing states, and category-wise performance for strategic business insights.._

![Excel](https://img.shields.io/badge/Tool-PowerBI-FFCE3C?style=for-the-badge&logo=microsoft-excel&logoColor=white)
![Level](https://img.shields.io/badge/Level-Beginner-blue?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen?style=for-the-badge)


##  Overview
A Power BI dashboard analyzing a megastore's yearly sales, profit, and quantity (July 2014 – May 2018), built to practice **Power Query** and **Power BI** skills.

---

##  Business Problem
A retail megastore sells products in three main categories: Office Supplies, Technology, and Furniture. The management wants to know:
- Which category and sub-category earns the most profit and sales
- Which states perform best and worst in profit
- How sales and profit change year by year
- Where the business is losing money or has low margins

This dashboard helps answer these questions in one simple view, so the management can make quick decisions.

---

##  Dataset
- **Source:** - <a href="https://github.com/soumyadipda/megastore_anual_dashboard_analysis_powerbi/blob/main/megastore_raw_data.xlsx">Dataset</a> 👈
- **Time period:** 07-01-2014 to 05-01-2018
- **Fields used:** Order Date, Category, Sub-Category, Segment, Ship Mode, State, Sales, Profit, Quantity

---

##  Tools & Technologies
- **Power Query** – for cleaning, shaping, and transforming raw data before loading it into the model
- **Power BI Desktop** – for building the data model, DAX measures, and the final interactive dashboard

---

##  Exploratory Data Analysis (EDA)
- *Gross Profit (Min):* Some orders had very low profit
- *Profit Margin (Min):* Near-zero margins in a few sub-categories
- *Outliers Identified:* High sales but low/negative profit orders
- *Correlation:* Sales and profit mostly move together, but not always (e.g., Copiers: low sales, high profit)

---

##  Key Findings

- *Profit by category:* Office Supplies $0.24M > Technology $0.22M > Furniture $0.14M
- *Sales by category:* Technology $0.84M > Furniture $0.74M > Office Supplies $0.72M
- *Top states (profit):* New York $84K, California $84K, Texas $48K, Washington $34K, Pennsylvania $28K
- *Bottom states (profit):* Maine $454, South Dakota $395, West Virginia $340, North Dakota $230, Wyoming $100
- *Yearly growth:* Sales grew $0.48M → $0.73M (2014–2017); Profit grew $0.11M → $0.20M
- *Best sub-category:* Copiers (high profit, low units); *weakest:* Fasteners, Labels
---

##  Dashboard (Power BI Dashboard shows:)

**The dashboard has**
- ***Filters at the top***➡️ --- (Category, Ship Mode, Segment, Sub-Category, and a Date range slider)
- ***KPI card***⬇️
- 1️⃣*Total Profit:* **($598.66K)** 
- 2️⃣*Total Sales:* **($2.30M)**
- 3️⃣*Total Quantity:* **(38K)**

![Megastore Annual Dashboard](https://github.com/soumyadipda/megastore_anual_dashboard_analysis_powerbi/blob/main/dashboard.jpg)

---

##  Final Recommendations
- Push Office Supplies (best margin)
- Check why Technology has high sales but lower profit
- Reward top states; review pricing in low-profit states
- Promote high-margin items (Copiers); rework low-margin ones (Fasteners, Labels)
---
<h2><a class="anchor" id="author--contact"></a>Author & Contact</h2>

**Soumyadip Dhara**  
Data Analyst  
 📧 Email: dips65781@gmail.com
 
🔗 [LinkedIn](https://www.linkedin.com/in/soumyadipdhara1/)  


