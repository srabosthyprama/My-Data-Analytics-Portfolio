```markdown
# 🍕 Pizza Sales Performance Dashboard

> **Turning raw pizza sales data into actionable business insights with Power BI**

An interactive **Power BI Pizza Sales Performance Dashboard** built to analyze sales performance, customer preferences, seasonal trends, and operational demand patterns.

The goal of this project is not only to understand **what happened**, but also to identify **why it may have happened, what business risks exist, and what actions management can take** to improve revenue, inventory efficiency, and operational planning.

---

## 📊 Dashboard Preview

![Pizza Sales Dashboard Preview](images/pizza-sales-dashboard.png)

> Replace `images/pizza-sales-dashboard.png` with the actual path of your dashboard screenshot.

### 🔴 Live Dashboard

👉 **[View Interactive Power BI Dashboard](YOUR_POWER_BI_LIVE_DASHBOARD_LINK)**

> Replace `YOUR_POWER_BI_LIVE_DASHBOARD_LINK` with your published Power BI Service link.

---

## 🎯 Business Objective

The main objective of this project is to understand the key factors driving pizza sales and identify opportunities for better business decisions.

The dashboard helps answer questions such as:

- How much revenue and how many orders were generated?
- Which months perform best and worst?
- Which pizza categories are most popular?
- Which pizza sizes do customers prefer?
- Which days and hours experience the highest demand?
- When is the business most likely to face operational pressure?
- Where might inventory or staffing resources be underutilized?
- What actions could help improve peak-hour operations and off-peak sales?

---

## 📌 Key Performance Indicators

The dashboard tracks five core KPIs:

| KPI | Value |
|---|---:|
| 💰 Total Revenue | **$817.86K** |
| 🧾 Total Orders | **21,350** |
| 🍕 Total Pizzas Sold | **49,574** |
| 💵 Average Order Value | **$38.31** |
| 🍕 Average Pizzas per Order | **2.32** |

The KPI section also includes **Month-over-Month (MoM) Growth**.

The growth comparison becomes meaningful when a specific month is selected from the **Month Slicer**, allowing the selected month to be compared with the previous month.

---

# 🔍 What Happened? — Key Findings

## 📈 1. Seasonal Sales Fluctuation

Sales performance varied across the year, showing clear seasonal fluctuations.

### 🟢 Strong-performing months

**July** was the strongest month:

- **Revenue:** $72.56K
- **Pizzas Sold:** 4,392

Other strong-performing months included:

- **March:** $70.40K revenue
- **May:** $71.40K revenue
- **November:** $70.40K revenue

### 🔴 Lower-performing months

The weakest performance was observed during:

- **February:** $65.16K revenue | 3,961 pizzas sold
- **September:** $64.18K revenue
- **October:** $64.03K revenue
- **December:** $64.70K revenue

The decline during September–December is particularly important from a business perspective because it may indicate an opportunity for targeted seasonal campaigns and demand-generation strategies.

> **Note:** The dataset shows the sales pattern but does not directly provide the external reasons behind these fluctuations. Factors such as holidays, weather, customer spending, promotions, or local events would require additional data to confirm the root cause.

---

## 🍕 2. Pizza Category Preferences

Customer demand varies across pizza categories.

| Category | Share of Pizza Sold |
|---|---:|
| 🥇 Classic | **30.03%** |
| 🥈 Supreme | **24.18%** |
| 🥉 Veggie | **23.50%** |
| Chicken | **22.29%** |

**Classic** was the most popular category, accounting for approximately **30.03%** of total pizzas sold.

**Chicken** had the lowest share at **22.29%**.

### 💡 Business Insight

The strong performance of Classic pizzas indicates that familiar and popular products play an important role in overall demand.

The lower share of Chicken pizzas could also represent an opportunity for targeted promotions, bundles, or further product-level analysis.

---

## 📏 3. Pizza Size Preferences

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

### 💡 Business Insight

This creates a potential opportunity to review the cost of maintaining very low-demand sizes.

Rather than removing these sizes immediately, management could first evaluate:

- Ingredient requirements
- Preparation cost
- Profit margin
- Special-order frequency
- Customer demand

If these sizes consistently generate very little revenue or margin, they could potentially be moved to a **special-order-only** option.

---

# ⏰ 4. Peak Days & Operating Hours

Demand is concentrated around specific days and time periods.

### 📅 Busiest Days

**Friday** recorded the highest order volume, followed by **Thursday**.

These days represent the most important periods for operational planning.

### 🕐 Busiest Hours

The strongest demand periods were concentrated around:

- **12:00 PM** — Lunch Peak
- **5:00 PM – 6:00 PM** — Evening Peak

The Day & Time matrix/heatmap makes these demand patterns easy to identify.

### 💡 Business Insight

When a large share of orders arrives within a few specific hours, the business may experience:

**Peak Hours → Higher Workload → Operational Bottlenecks**

while:

**Off-Peak Hours → Lower Workload → Underutilized Capacity**

This suggests that staffing and operational resources should be aligned more closely with actual demand.

---

# 🤔 Why Might This Be Happening?

The dashboard identifies **patterns**, but the sales dataset alone cannot prove every underlying cause.

Based on domain knowledge, several possible explanations can be considered.

## ☀️ Seasonal Demand

Higher sales during months such as May and July could potentially be influenced by:

- Summer holidays
- Social gatherings
- Outdoor activities
- Sports or local events
- Changes in customer spending behavior

Similarly, lower sales during September–December may be associated with changes in seasonal demand, customer budgets, holidays, or competitive promotions.

These should be treated as **business hypotheses**, not confirmed causes, unless additional external data is available.

## 🍕 Large-Size Preference

Large pizzas may be attractive because they are suitable for sharing and can provide better perceived value for families or groups.

This could explain why Large pizzas significantly outperform X-Large and XX-Large sizes.

## ⏰ Lunch & Dinner Peaks

The concentration of orders around **12:00 PM** and **5:00–6:00 PM** is consistent with common lunch and post-work/dinner purchasing behavior.

---

# ⚠️ Business Risks & Opportunities

## 1. 📦 Inventory Waste

Extremely low demand for **X-Large and XX-Large** pizzas may result in unnecessary inventory requirements.

Maintaining ingredients and preparation capacity for products with very low demand can increase:

- Holding costs
- Ingredient waste
- Operational complexity

---

## 2. 👥 Peak-Hour Bottlenecks

Thursday and Friday demand, especially around lunch and evening peaks, can put pressure on:

- Kitchen staff
- Delivery staff
- Order processing
- Preparation capacity

If capacity is not planned around demand, customers may experience longer wait times and reduced service quality.

---

## 3. 🕑 Underutilized Off-Peak Capacity

Lower-demand periods represent an opportunity.

Instead of leaving staff and equipment underutilized, the business could use targeted promotions to shift some demand toward quieter periods.

---

## 4. 📉 Seasonal Revenue Risk

The weaker performance observed in **September, October, and December** may create a revenue risk if the pattern continues.

This suggests the need for seasonal planning rather than relying only on reactive sales strategies.

---

# 💡 Recommended Business Actions

## 👥 1. Dynamic Staffing

Align staffing levels with actual customer demand.

Increase operational capacity around:

- **Thursday & Friday**
- **12:00 PM – 1:00 PM**
- **5:00 PM – 7:00 PM**

This could involve flexible scheduling, additional part-time staff, or better allocation of kitchen and delivery resources.

### Expected Benefit

**Better peak-hour service + shorter wait times + improved resource utilization**

---

## 📦 2. Menu & Inventory Optimization

Review the business case for **X-Large and XX-Large** pizzas.

Instead of removing them immediately, management could test:

> **Special-order only**

If demand and profitability remain extremely low, the business can consider reducing their availability.

For the Chicken category, targeted:

- Combo offers
- Discounts
- Bundles
- Cross-selling

could be tested to increase demand.

---

## 🕑 3. Off-Peak Promotions

Use slower periods to shift demand away from peak hours.

For example:

**Monday–Wednesday | 2:00 PM – 4:00 PM**

Potential strategies include:

- Happy Hour Discounts
- Buy 1 Get 1 offers
- Combo promotions
- Limited-time deals

The objective is not simply to increase total orders, but to **smooth demand across the day**.

---

## 📅 4. Seasonal Campaigns

The lower-performing months can be targeted with specific campaigns.

Potential strategies include:

- Seasonal menu items
- Discount vouchers
- Limited-time offers
- Event-based promotions
- Customer loyalty campaigns

Performance can then be compared against previous months to determine whether these campaigns actually improve revenue.

---

# 🖥️ Dashboard Features

The dashboard was designed as an interactive business analysis tool rather than a static report.

## 🎛️ Interactive Filters

The dashboard includes three main slicers:

- **Month**
- **Pizza Category**
- **Pizza Size**

These allow users to drill into specific segments and understand how performance changes.

---

## 📊 KPI Cards

Five KPI cards provide a quick overview of:

- Total Revenue
- Total Order Quantity
- Total Pizza Sold Quantity
- Average Order Value
- Average Pizza per Order

The KPI cards also include **Month-over-Month Growth** when a specific month is selected.

---

## 📈 Monthly Trend Analysis

A line chart displays monthly:

- Orders
- Revenue
- Pizza Sold

using a **Power BI Field Parameter**.

This allows users to switch between different metrics dynamically within the same visual.

---

## 📅 Day-of-Week Analysis

A column chart allows users to analyze:

- Orders
- Revenue
- Pizza Sold

by day of the week.

---

## 🍕 Category Analysis

A donut chart provides a visual breakdown of:

- Orders
- Revenue
- Pizza Sold

by pizza category.

---

## 📏 Size Analysis

A column chart compares:

- Orders
- Revenue
- Pizza Sold

across pizza sizes.

---

## 🔥 Day & Time Demand Analysis

A matrix/heatmap shows order volume by:

**Day of Week × Hour**

Additional inverse column and bar visuals provide another view of total orders by day and time.

A dynamic text insight highlights the:

- **Busiest Day**
- **Busiest Time**

This makes the dashboard easier for business users to interpret without manually analyzing every value.

---

# 🛠️ Technical Implementation

## Tools & Technologies

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

# 📐 Dashboard Design Approach

The dashboard follows a simple analytical flow:

**KPI Overview**  
↓  
**Monthly Performance**  
↓  
**Day & Time Demand**  
↓  
**Category Performance**  
↓  
**Size Performance**  
↓  
**Business Insights & Actions**

This structure allows users to move from:

> **“How is the business performing?”**

to:

> **“When and what are customers buying?”**

and finally:

> **“What should management do?”**

---

# 🎯 Key Takeaways

The analysis highlights several important business insights:

1. **$817.86K revenue** was generated from **21,350 orders** and **49,574 pizzas sold**.
2. **July** was the strongest month with **$72.56K revenue** and **4,392 pizzas sold**.
3. **February, September, October, and December** showed comparatively weaker sales.
4. **Classic** was the leading pizza category at **30.03%**.
5. **Large** was the most popular size with **12,736 pizzas sold**.
6. **X-Large and XX-Large** had extremely low demand, with only **544 and 28 pizzas sold** respectively.
7. **Friday** was the busiest day.
8. **12:00 PM** and **5:00–6:00 PM** were the major demand peaks.
9. Staffing should be aligned with peak demand rather than distributed evenly throughout the day.
10. Off-peak promotions and seasonal campaigns could help improve capacity utilization and revenue consistency.

---

# 🚀 Final Takeaway

This project demonstrates how a well-designed Power BI dashboard can move beyond **descriptive reporting** and support **business decision-making**.

The objective was not simply to display sales numbers.

It was to connect:

**Data → Pattern → Business Risk → Opportunity → Action**

By understanding when customers buy, what they prefer, and where demand is concentrated, management can make more informed decisions around:

- **Staffing**
- **Inventory**
- **Promotions**
- **Menu strategy**
- **Seasonal planning**

> **Good dashboards don't just tell us what happened. They help us decide what to do next.** 🍕📊

---

# 🔗 Project Links

📊 **Live Power BI Dashboard:**  
[View Interactive Dashboard](YOUR_POWER_BI_LIVE_DASHBOARD_LINK)

💻 **GitHub Repository:**  
[View Project Repository](YOUR_GITHUB_REPOSITORY_LINK)

---

# 👨‍💻 Project Information

**Project Type:** Portfolio Project — Data Analytics & Business Intelligence

**Focus Areas:** Sales Performance | Customer Behavior | Operational Analytics | Business Insights

**Tools:** Power BI | DAX | Data Visualization | Field Parameters
```

