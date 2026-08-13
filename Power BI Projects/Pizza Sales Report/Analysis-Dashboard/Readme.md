# Pizza Sales Performance Dashboard

> Turning raw pizza sales data into actionable business insights with Power BI.

An interactive **Power BI Pizza Sales Performance Dashboard** built to analyze sales performance, customer preferences, seasonal trends, and operational demand patterns.

The goal of this project is not only to understand **what happened**, but also to explore **why it may have happened, what business risks may exist, and what insights or opportunities can be identified from the data**.

---

## Dashboard Preview

<img width="1558" height="836" alt="Screenshot 2026-08-13 114136" src="https://github.com/user-attachments/assets/4f10bff8-1070-42e3-bdc7-0c78d56d48b8" />

### Live Dashboard

[View Interactive Power BI Dashboard](https://app.powerbi.com/view?r=eyJrIjoiODM3MzdiYjEtZDQ3Zi00YmJkLTkxNDgtMmM3N2NmODAyY2NlIiwidCI6IjNjZDA3OTg4LTUyNjMtNDA2NC1hZDU1LWU5NTZhYjNkZDExNyIsImMiOjEwfQ%3D%3D)

---

## Business Objective

The objective of this project is to explore pizza sales data and identify patterns in:

- Revenue and order performance
- Monthly sales trends
- Pizza category preferences
- Pizza size preferences
- Day-of-week demand
- Hourly ordering patterns
- Peak and off-peak periods
- Potential operational and revenue opportunities

---

# Key Performance Indicators

The dashboard tracks five core KPIs:

| KPI | Value |
|---|---:|
| Total Revenue | **$817.86K** |
| Total Orders | **21,350** |
| Total Pizzas Sold | **49,574** |
| Average Order Value | **$38.31** |
| Average Pizzas per Order | **2.32** |

The KPI section also includes **Month-over-Month (MoM) Growth**.

The growth comparison becomes meaningful when a specific month is selected from the **Month Slicer**, allowing the selected month to be compared with the previous month.

---

# What Happened? — Key Findings

## 1. Seasonal Sales Fluctuation

Sales performance varied across the year, showing noticeable seasonal fluctuations.

### Strong-Performing Months

**July** was the strongest month:

- Revenue: **$72.56K**
- Pizzas Sold: **4,392**

Other strong-performing months included:

- **May:** $71.40K revenue | 4,328 pizzas sold
- **November:** $70.40K revenue | 4,266 pizzas sold
-  **March:** $70.40K revenue | 4,261 pizzas sold

### Lower-Performing Months

The weaker-performing months included:

- **February:** $65.16K revenue | 3,961 pizzas sold
- **December:** $64.70K revenue | 3,935 pizzas sold
- **September:** $64.18K revenue | 3,890 pizzas sold
- **October:** $64.03K revenue | 3,883 pizzas sold

The lower performance during September–December suggests that seasonal changes in customer demand and revenue should be looked at more closely.

> **Note:** The dataset shows the sales pattern but does not directly provide the external reasons behind these fluctuations. Factors such as holidays, weather, customer spending, promotions, or local events would require additional data to confirm the root cause.

---

## 2. Pizza Category Preferences

Customer demand varies across pizza categories.

| Category | Share of Pizza Sold |
|---|---:|
| Classic | **30.03%** |
| Supreme | **24.18%** |
| Veggie | **23.50%** |
| Chicken | **22.29%** |

**Classic** was the most popular category, accounting for approximately **30.03%** of total pizzas sold.

**Chicken** had the lowest share at **22.29%**.

### Insight

The strong performance of Classic pizzas suggests that familiar and popular products play an important role in overall customer demand.

The comparatively lower share of Chicken pizzas could represent an opportunity for further analysis around pricing, promotions, combinations, or what customers prefer.

---

## 3. Pizza Size Preferences

Customer demand is highly concentrated around the most popular sizes.

| Pizza Size | Pizzas Sold |
|---|---:|
| Large | **12,736** |
| Medium | **11,159** |
| Regular | **10,490** |
| X-Large | **544** |
| XX-Large | **28** |

**Large** pizzas clearly dominate demand with **12,736 order**.

In contrast, X-Large and XX-Large pizzas had extremely low demand:

- **X-Large:** 544
- **XX-Large:** 28

Together, these two sizes account for **less than 1%** of total order.

### Insight

The very low demand for X-Large and XX-Large sizes highlights a potential area for **menu and inventory optimization**.

A possible recommendation would be to evaluate the cost, margin, ingredient requirements, and frequency of special orders for these sizes before deciding whether they should remain fully available or move toward a special-order model.

---

## 4. Peak Days and Operating Hours

Demand is concentrated around specific days and time periods.

### Busiest Days

**Friday** recorded the highest order volume, followed by **Thursday**.

This pattern highlights Thursday and Friday as important periods for understanding operational demand.

### Busiest Hours

The strongest demand periods were concentrated around:

- **12:00 PM** — Lunch peak
- **5:00 PM–6:00 PM** — Evening peak

The Day & Time heatmap makes these demand patterns easy to identify.

### Insight

When a large share of orders arrives within a few specific hours, there may be a higher risk of operational bottlenecks during peak periods.

At the same time, lower order volumes during other periods suggest potential underutilization of available staff and equipment.

This creates an opportunity to explore **demand-based staffing and off-peak sales strategies**.

---

# Why Might This Be Happening?

The dashboard identifies **patterns**, but the sales dataset alone cannot prove every underlying cause.

Based on domain knowledge, several possible explanations can be considered.

## Seasonal Demand

Higher sales during months such as May and July could potentially be influenced by:

- Summer holidays
- Social gatherings
- Outdoor activities
- Sports or local events
- Changes in customer spending behavior

Similarly, lower sales during September–December may be associated with changes in seasonal demand, customer budgets, holidays, or competitive promotions.

These should be treated as **business hypotheses**, not confirmed causes, unless additional external data is available.

## Large-Size Preference

Large pizzas may be attractive because they are suitable for sharing and can provide better perceived value for families or groups.

This could help explain why Large pizzas significantly outperform X-Large and XX-Large sizes.

## Lunch and Dinner Peaks

The concentration of orders around **12:00 PM** and **5:00–6:00 PM** is consistent with common lunch and post-work/dinner purchasing behavior.

---

# Business Risks and Opportunities

## 1. Inventory Waste

Extremely low demand for **X-Large and XX-Large** pizzas may create potential inventory inefficiencies.

Maintaining ingredients and preparation capacity for products with very low demand could contribute to:

- Higher holding costs
- Ingredient waste
- Additional operational complexity

This suggests that low-performing sizes could be reviewed to see if inventory can be managed more efficiently.

---

## 2. Peak-Hour Bottlenecks

Thursday and Friday demand, especially around lunch and evening peaks, may create additional pressure on:

- Kitchen staff
- Delivery staff
- Order processing
- Preparation capacity

If there are more orders than staff can handle during busy times, customers may have to wait longer and service quality may decrease.

This creates an opportunity to schedule more staff during busy hours and fewer staff during quiet hours.

---

## 3. Underutilized Off-Peak Capacity

Lower-demand periods represent a potential revenue opportunity.

If staff and equipment are not very busy during quiet hours, special offers could encourage some customers to come at those less busy times.

---

## 4. Seasonal Revenue Risk

The weaker performance observed in **September, October, and December** may represent a potential seasonal revenue risk if similar patterns continue.

This highlights an opportunity to investigate seasonal campaigns and compare their performance against previous periods.

---

# Recommendations Based on the Analysis

## 1. Dynamic Staffing

The highest order volumes occur on **Thursday and Friday**, especially around **12:00 PM–1:00 PM** and **5:00 PM–7:00 PM**.

A more demand-based staffing approach could help manage peak-hour pressure while making better use of resources during quieter periods.

---

## 2. Review Low-Demand Pizza Sizes

**X-Large (544)** and **XX-Large (28)** pizzas have very low demand compared with other sizes.

These sizes could be reviewed based on ingredient cost, preparation effort, profitability, and customer demand. If they remain consistently low-performing, a **special-order-only** option could be considered.

---

## 3. Promote the Chicken Category

The **Chicken category accounts for 22.29%** of total pizza sales, the lowest among the four categories.

Targeted **combo offers, bundles, discounts, or cross-selling** could be explored to increase customer interest and improve category performance.

---

## 4. Increase Off-Peak Sales

The **2:00 PM–4:00 PM** period presents a potential opportunity for demand smoothing.

Time-based offers such as **Happy Hour discounts, Buy 1 Get 1, or limited-time combos** could help attract customers during quieter hours and balance demand throughout the day.

---

## 5. Explore Seasonal Promotions

Lower sales during **September, October, and December** suggest an opportunity to test seasonal strategies.

Possible approaches include **limited-time offers, seasonal menu items, discount vouchers, or event-based promotions**, with performance tracked through month-over-month comparisons.
---

# Dashboard Features

The dashboard was designed as an interactive business analysis tool rather than a static report.

## Interactive Filters

The dashboard includes three main slicers:

- **Month**
- **Pizza Category**
- **Pizza Size**

These allow users to explore specific segments and understand how performance changes.

---

## KPI Cards

Five KPI cards provide a quick overview of:

- Total Revenue
- Total Order Quantity
- Total Pizza Sold Quantity
- Average Order Value
- Average Pizza per Order

The KPI cards also include **Month-over-Month Growth** when a specific month is selected.

---

## Monthly Trend Analysis

A line chart displays monthly:

- Orders
- Revenue
- Pizza Sold

using a **Power BI Field Parameter**.

This allows users to switch between different metrics dynamically within the same visual.

---

## Day-of-Week Analysis

A column chart allows users to analyze:

- Orders
- Revenue
- Pizza Sold

by day of the week.

---

## Category Analysis

A donut chart provides a visual breakdown of:

- Orders
- Revenue
- Pizza Sold

by pizza category.

---

## Size Analysis

A column chart compares:

- Orders
- Revenue
- Pizza Sold

across pizza sizes.

---

## Day and Time Demand Analysis

A heatmap shows order volume by:

**Day of Week × Hour**

Additional inverse column and bar visuals provide another view of total orders by day and time.

A dynamic text insight highlights the:

- **Busiest Day**
- **Busiest Time**

This makes the dashboard easier to interpret without manually analyzing every value.

---

# Technical Implementation

## Tools and Technologies

- **Power BI**
- **DAX**
- **Data Visualization**
- **Power BI Field Parameters**
- **Interactive Slicers**
- **KPI Cards**
- **Matrix / Heatmap**
- **Dynamic Text Insights**

## Power BI Techniques Used

The project demonstrates practical Power BI techniques including:

- KPI development
- DAX-based calculations
- Month-over-Month comparison
- Field Parameters for dynamic visual metrics
- Interactive filtering
- Time-based analysis
- Category and size segmentation
- Dynamic business insights
- Dashboard storytelling

