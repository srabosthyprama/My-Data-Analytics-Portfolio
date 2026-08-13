# Pizza Sales Performance Dashboard

> Turning raw pizza sales data into actionable business insights with Power BI.

An interactive **Power BI Pizza Sales Performance Dashboard** built to analyze sales performance, customer preferences, seasonal trends, and operational demand patterns.

The goal of this project is not only to understand **what happened**, but also to explore **why it may have happened, what business risks may exist, and what insights or opportunities can be identified from the data**.

---

## Dashboard Preview

![Pizza Sales Dashboard Preview](images/pizza-sales-dashboard.png)

> Replace `images/pizza-sales-dashboard.png` with the actual path of your dashboard screenshot.

### Live Dashboard

[View Interactive Power BI Dashboard](YOUR_POWER_BI_LIVE_DASHBOARD_LINK)

> Replace `YOUR_POWER_BI_LIVE_DASHBOARD_LINK` with your published Power BI Service link.

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

The dashboard is designed to move from **descriptive analysis** toward **business-focused insights and recommendations**.

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

- **March:** $70.40K revenue
- **May:** $71.40K revenue
- **November:** $70.40K revenue

### Lower-Performing Months

The weaker-performing months included:

- **February:** $65.16K revenue | 3,961 pizzas sold
- **September:** $64.18K revenue
- **October:** $64.03K revenue
- **December:** $64.70K revenue

The lower performance during September–December highlights a potential opportunity for further investigation into seasonal demand and revenue patterns.

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

The comparatively lower share of Chicken pizzas could represent an opportunity for further analysis around pricing, promotions, product combinations, or customer preferences.

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

**Large** pizzas clearly dominate demand with **12,736 pizzas sold**.

In contrast, X-Large and XX-Large pizzas had extremely low demand:

- **X-Large:** 544
- **XX-Large:** 28

Together, these two sizes account for **less than 1%** of total pizzas sold.

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

The Day & Time matrix/heatmap makes these demand patterns easy to identify.

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

This suggests that low-performing sizes could be reviewed as part of a broader inventory optimization analysis.

---

## 2. Peak-Hour Bottlenecks

Thursday and Friday demand, especially around lunch and evening peaks, may create additional pressure on:

- Kitchen staff
- Delivery staff
- Order processing
- Preparation capacity

If demand significantly exceeds available capacity during these periods, longer wait times and reduced service quality could become potential risks.

This creates an opportunity to explore **more demand-aligned staffing schedules**.

---

## 3. Underutilized Off-Peak Capacity

Lower-demand periods represent a potential revenue opportunity.

If staff and equipment have available capacity during quieter hours, targeted promotions could potentially shift a portion of demand toward these periods.

---

## 4. Seasonal Revenue Risk

The weaker performance observed in **September, October, and December** may represent a potential seasonal revenue risk if similar patterns continue.

This highlights an opportunity to investigate seasonal campaigns and compare their performance against previous periods.

---

# Recommendations Based on the Analysis

The following recommendations are **data-driven opportunities identified from the dashboard**, rather than direct operational instructions.

## 1. Explore Dynamic Staffing

The concentration of orders around:

- **Thursday and Friday**
- **12:00 PM–1:00 PM**
- **5:00 PM–7:00 PM**

suggests that a more demand-aligned staffing approach could be explored.

Potential approaches include:

- Flexible staff scheduling
- Part-time staffing during high-demand windows
- Adjusting kitchen capacity around peak periods
- Aligning delivery resources with order volume

### Potential Benefit

Better alignment between staffing capacity and customer demand could help reduce peak-hour pressure while improving utilization during quieter periods.

---

## 2. Review Low-Demand Pizza Sizes

X-Large and XX-Large pizzas generated very low sales:

- **X-Large:** 544 pizzas
- **XX-Large:** 28 pizzas

A potential recommendation is to review these sizes based on:

- Ingredient requirements
- Preparation cost
- Profit margin
- Special-order frequency
- Customer demand

If further analysis confirms that these sizes contribute very little revenue or margin, a **special-order-only** model could be considered.

---

## 3. Explore Chicken Category Promotions

The Chicken category represented **22.29%** of total pizza sales, making it the lowest-performing category.

This could be explored through:

- Combo offers
- Discounts
- Bundles
- Cross-selling
- Limited-time promotions

A future analysis could compare promotional performance to determine whether these strategies meaningfully increase Chicken category sales.

---

## 4. Explore Off-Peak Promotions

The demand pattern suggests that **2:00 PM–4:00 PM** could be an interesting period for demand-smoothing experiments.

Potential ideas include:

- Happy Hour discounts
- Buy 1 Get 1 offers
- Combo promotions
- Limited-time deals

The objective would be to shift some demand from highly concentrated peak periods toward quieter hours.

---

## 5. Explore Seasonal Campaigns

The weaker performance during **September, October, and December** could be investigated through seasonal sales strategies.

Potential approaches include:

- Seasonal menu items
- Discount vouchers
- Limited-time offers
- Event-based promotions
- Customer loyalty campaigns

The impact of these initiatives could then be measured through month-over-month and year-over-year comparisons.

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

A matrix/heatmap shows order volume by:

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

---

# Dashboard Design Approach

The dashboard follows a simple analytical flow:

**KPI Overview**  
↓  
**Monthly Performance**  
↓  
**Day and Time Demand**  
↓  
**Category Performance**  
↓  
**Size Performance**  
↓  
**Insights and Recommendations**

This structure allows the analysis to move from:

> **"How is the business performing?"**

to:

> **"When and what are customers buying?"**

and finally:

> **"What opportunities can be identified from the data?"**

---

# Key Takeaways

The analysis highlights several important findings:

1. **$817.86K revenue** was generated from **21,350 orders** and **49,574 pizzas sold**.
2. **July** was the strongest month with **$72.56K revenue** and **4,392 pizzas sold**.
3. **February, September, October, and December** showed comparatively weaker sales.
4. **Classic** was the leading pizza category at **30.03%**.
5. **Large** was the most popular size with **12,736 pizzas sold**.
6. **X-Large and XX-Large** had extremely low demand, with only **544 and 28 pizzas sold** respectively.
7. **Friday** was the busiest day.
8. **12:00 PM** and **5:00–6:00 PM** were the major demand peaks.
9. Peak-hour demand highlights a potential opportunity for more demand-aligned staffing.
10. Low-demand sizes and off-peak periods present potential opportunities for inventory optimization and demand-smoothing strategies.

---

# Final Takeaway

This project demonstrates how a Power BI dashboard can move beyond **descriptive reporting** and support **data-driven business thinking**.

The objective was not simply to display sales numbers.

It was to connect:

**Data → Pattern → Insight → Risk → Opportunity → Recommendation**

By analyzing when customers buy, what they prefer, and where demand is concentrated, the dashboard highlights potential areas for:

- **Staffing optimization**
- **Inventory efficiency**
- **Promotional strategies**
- **Menu optimization**
- **Seasonal planning**

> **A good dashboard doesn't just show what happened. It helps uncover where opportunities may exist.**

---

# Project Links

- **Live Power BI Dashboard:** [View Interactive Dashboard](YOUR_POWER_BI_LIVE_DASHBOARD_LINK)
- **GitHub Repository:** [View Project Repository](YOUR_GITHUB_REPOSITORY_LINK)

---

# Project Information

| Detail | Description |
|---|---|
| Project Type | Portfolio Project — Data Analytics & Business Intelligence |
| Focus Areas | Sales Performance, Customer Behavior, Operational Analytics, Business Insights |
| Visualization Tool | Power BI |
| Query / Calculation | DAX |
| Key Features | KPI Cards, Field Parameters, Slicers, Heatmap, Dynamic Insights |
