# 🛒 Megastore Annual Dashboard – Power BI Project

##  Overview
This is a Power BI dashboard project made to study the yearly sales, profit, and quantity performance of a retail megastore. The dashboard covers data from **July 2014 to May 2018** and shows results by category, sub-category, state, and year. This project was built to practice and show my skills in **Power Query** and **Power BI**.

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
- **Source:** Retail/Megastore sales dataset (order-level sales data)
- **Time period:** 07-01-2014 to 05-01-2018
- **Fields used:** Order Date, Category, Sub-Category, Segment, Ship Mode, State, Sales, Profit, Quantity

---

##  Tools & Technologies
- **Power Query** – for cleaning, shaping, and transforming raw data before loading it into the model
- **Power BI Desktop** – for building the data model, DAX measures, and the final interactive dashboard

---

##  Exploratory Data Analysis (EDA)
- **Gross Profit (Min):** Lowest recorded profit value found among the sub-categories/orders during data checks
- **Profit Margin (Min):** Some orders/sub-categories showed very thin or near-zero profit margins
- **Outliers Identified:** A few orders had unusually high sales but very low or negative profit, flagged as outliers
- **Correlation Analysis:** Sales and Profit generally move together, but higher sales did not always mean higher profit — some high-sales sub-categories had low profit (e.g., Copiers has fewer units but high profit per unit, while Fasteners has low profit)

---

##  Research Questions & Key Findings

1. **Which category makes the most profit?**
   - Office Supplies leads in profit ($0.24M), followed by Technology ($0.22M) and Furniture ($0.14M)

2. **Which category has the highest sales?**
   - Technology has the highest sales ($0.84M), followed by Furniture ($0.74M) and Office Supplies ($0.72M)
   - Interesting finding: Office Supplies has the lowest sales but the highest profit, meaning it has better profit margins

3. **Which states bring the most profit?**
   - Top 5: New York ($84K), California ($84K), Texas ($48K), Washington ($34K), Pennsylvania ($28K)

4. **Which states bring the least profit?**
   - Bottom 5: Maine ($454.49), South Dakota ($394.83), West Virginia ($339.83), North Dakota ($230.15), Wyoming ($100.20)

5. **How did the business grow over the years?**
   - Sales: 2014 ($0.48M) → 2015 ($0.47M) → 2016 ($0.61M) → 2017 ($0.73M)
   - Profit: 2014 ($0.11M) → 2015 ($0.13M) → 2016 ($0.16M) → 2017 ($0.20M)
   - Both sales and profit grew steadily each year, with the biggest jump between 2015 and 2016

6. **Which sub-categories perform best?**
   - Copiers give the highest profit per sale ($55,617.82 profit on $1,49,528.03 sales, only 234 units) — very high margin
   - Binders have the highest sales quantity (5,974 units) and strong profit ($1,07,242.76)
   - Fasteners and Labels have low profit and low sales, showing weak performance

---

##  Dashboard (Power BI Dashboard shows:)

The dashboard has filters at the top (Category, Ship Mode, Segment, Sub-Category, and a Date range slider) and 3 KPI cards showing **Total Profit ($598.66K)**, **Total Sales ($2.30M)**, and **Total Quantity (38K)**.

Below the filters, the dashboard has these visuals:
- **Category by Profit** – bar chart comparing profit of Office Supplies, Technology, and Furniture
- **Category by Sales** – bar chart comparing sales of the same three categories
- **Top 5 State by Profit** – horizontal bar chart of the 5 best-performing states
- **Bottom 5 State by Profit** – horizontal bar chart of the 5 weakest-performing states
- **Profit and Sales by Year** – combo chart (bar + line) showing yearly trend from 2014 to 2017
- **Sub-Category Table** – detailed table showing Sum of Profit, Sum of Sales, and Sum of Quantity for every sub-category (Accessories, Appliances, Art, Binders, Bookcases, Chairs, Copiers, Envelopes, Fasteners, Furnishings, Labels, etc.)

*(Screenshot of the dashboard should be added here, e.g. `![Dashboard](dashboard_screenshot.png)`)*

---

##  Final Recommendations
- Focus more marketing and stock on **Office Supplies** since it gives the best profit margin
- Investigate why **Technology** has high sales but lower profit compared to Office Supplies — check discounts or shipping costs
- Give special attention to **top states** (New York, California, Texas) for repeat business and loyalty offers
- Review pricing and cost in **low-profit states** (Maine, South Dakota, West Virginia, North Dakota, Wyoming) to reduce losses
- Promote high-margin sub-categories like **Copiers** more, and review pricing for low-margin items like **Fasteners** and **Labels**
- Continue the yearly growth trend by keeping the strategies that worked well in 2016–2017

---

**Soumyadip Dhara**  
Data Analyst  
 Email: dips657812gnail.com
🔗 [LinkedIn](https://www.linkedin.com/in/soumyadipdhara1/)  
🔗 [Portfolio](https://github.com/soumyadipda)
*This project was created for practicing and showcasing skills in Power Query and Power BI dashboard building.*
