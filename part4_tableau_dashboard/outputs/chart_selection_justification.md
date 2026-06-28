# Chart Selection Justification

## 1. Sales Trend (Line Chart)

**Business Question:** How are sales changing over time?

**Reason for Selection:** A line chart effectively displays trends and seasonal variations across months.

**Visual Encoding:**
- X-axis: Order Date
- Y-axis: Sales

**Design Principle:** Time-series visualization with minimal clutter.

**Mistake Avoided:** Avoided using bar charts for long time-series data.

---

## 2. Regional Performance (Horizontal Bar Chart)

**Business Question:** Which region contributes the highest sales?

**Reason for Selection:** Horizontal bars allow easy comparison between regions.

**Visual Encoding:**
- X-axis: Sales
- Y-axis: Region
- Color: Profit

**Design Principle:** Sorted values improve readability.

**Mistake Avoided:** Avoided pie charts which make comparison difficult.

---

## 3. Category Profitability (Horizontal Bar Chart)

**Business Question:** Which product categories generate the highest profit?

**Reason for Selection:** Horizontal bars effectively compare multiple sub-categories.

**Visual Encoding:**
- X-axis: Profit
- Y-axis: Sub-Category
- Color: Category

**Design Principle:** Descending sorting highlights best-performing products.

**Mistake Avoided:** Avoided stacked charts that reduce comparison accuracy.

---

## 4. Discount vs Profit (Scatter Plot)

**Business Question:** How do discounts influence profitability?

**Reason for Selection:** Scatter plots reveal relationships and patterns between two numerical variables.

**Visual Encoding:**
- X-axis: Discount
- Y-axis: Profit
- Size: Sales
- Color: Category

**Design Principle:** Individual orders are displayed without aggregation.

**Mistake Avoided:** Avoided line charts that incorrectly imply sequential relationships.

---

## Dashboard Design Principles

The dashboard follows executive reporting principles by placing KPI cards at the top, trend analysis in the center, comparative charts below, and interactive filters on the side. Colors remain consistent throughout the dashboard to reduce cognitive load while allowing rapid comparison across business dimensions.
