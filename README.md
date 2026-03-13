# Tableau_Sales_Dashboard
## 📊 Executive Sales & Revenue Analytics Suite

## 📝 Project Overview
[cite_start]This project transforms raw sales datasets  into a comprehensive, 4-part interactive dashboard suite built in Tableau. Designed for senior management, the goal of this project was to move beyond static historical reporting and create a dynamic, forward-looking strategic tool. 

[cite_start]By answering complex business questions, this suite enables leaders to run "What-If" profitability simulations, forecast future sales, and drill down into granular customer and product line behaviors.

[**View the Interactive Dashboard on Tableau Public**](Insert your Tableau Public Link Here)

---

## 🏗️ The Dashboards

### 1. Sales Executive Dashboard
The "Master Control" view for the C-suite, providing immediate pulse-checks on KPIs alongside powerful scenario testing.
* **Profitability Simulation:** A custom "What-If" engine using dynamic parameters allowing users to adjust expected sales volume and cost variables to see the simulated impact on the bottom line via a bullet chart.
* **Product Line Contribution:** A clean Waterfall chart illustrating how different product lines stack up to build total revenue.
* **Dynamic YoY Growth:** A dual-axis chart comparing historical revenue against automated YoY percentage growth, complete with boolean color formatting (Green for positive, Red for negative).

### 2. Customer Revenue Dashboard
A deep-dive into customer purchasing behavior and segmentation.
* **Dynamic Segmentation:** Automated logic that tiers customers into High, Medium, and Low revenue categories based on parameter thresholds.
* **Retention Tracking:** Isolates one-time/occasional buyers from loyal, repeat customers.
* **Deal Size Analysis:** A scatter plot mapping individual customer orders by Deal Size (Large, Medium, Small) and MSRP value.

### 3. Performance & Forecasting Dashboard
A forward-looking view to spot seasonality and predict future runways.
* **Predictive Analytics:** Integrates a 2-year exponential smoothing forecast model against historical actuals, complete with prediction intervals.
* **Top Contributors:** Clean, horizontally sorted bar charts highlighting the Top Territories and Top 3 Customers driving current metrics.

### 4. Revenue Growth Deep-Dive Dashboard
A highly granular, visual breakdown of the data over time and geography.
* **Seasonal Heatmap:** A visual matrix of Monthly Sales vs. Year, allowing users to instantly spot seasonal trends and high-volume periods.
* **Sales vs. Quantity:** A dual-axis time series ensuring that high-revenue months actually correlate with high-volume order counts.

---

## 🛠️ Technical Skills Demonstrated
* **Advanced Calculations:** Level of Detail (LOD) expressions, Quick Table Calculations (Running Sums, YoY Growth).
* **Interactive Parameters:** What-If analysis, Top N filtering, dynamic thresholds.
* **Custom Hierarchies:** Built custom date levels (Year → Quarter → Month) combined with Customer Names for smooth drill-down navigation.
* **Data Visualization Best Practices:** Clean "BANs" (Big Ass Numbers), abbreviated axis formatting (e.g., millions to 'M'), custom tooltips, and strategic color psychology (Red/Green logic).

---
