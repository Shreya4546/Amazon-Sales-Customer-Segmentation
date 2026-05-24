# Amazon Sales & Customer Segmentation Analysis
### Python · Excel · Power BI · DAX

End-to-end sales analysis of 250 Amazon orders (Feb–Apr 2025) covering revenue trends, customer segmentation, and cancellation diagnostics — delivered as a 3-page interactive Power BI dashboard.

---

## Business Questions Addressed

1. Which product categories and months drive the most revenue?
2. How do Top vs Regular customers differ in spend and order volume?
3. Where are cancellations concentrated — by category and payment method?
4. Which payment methods are preferred by high-value customers?

---

## Key Findings

| Metric | Value |
|---|---|
| Total Sales | ₹244K across 250 orders |
| Avg Order Value | ₹975.38 |
| Top category | Electronics (₹130K) + Home Appliances (₹105K) = 95%+ of revenue |
| Peak month | February (₹123K), followed by March (₹118K) |
| Top customer segment | "Top" buyers — ₹147K in sales, ~60% of total revenue, 55.6% of orders |
| Highest cancellation category | Home Appliances (₹36K cancelled) |
| Cancellations by payment | PayPal (32.37%) and Debit Card (30.73%) drove most cancelled order value |
| Credit Card cancellation | 32% of all cancellations came from Credit Card users |

---

## Dashboard Pages

**Page 1 — Sales Overview**

KPIs: Total Sales · Total Orders · Avg Order Value

- Sales peaked in February at ₹123K, dropping to ₹3K in April
- Electronics and Home Appliances together account for over 95% of revenue
- Credit Card (28.56%) and Amazon Pay (25.26%) are the top payment methods by volume

**Page 2 — Customer Insights**

- Top customers (55.6% of orders) generated ₹147K vs ₹96K from Regular customers
- Top 3 customers by revenue: Olivia Wilson (₹36,170) · Jane Smith (₹31,185) · Emma Clark (₹29,700)
- Customer base spans multiple US cities including New York, San Francisco, and Chicago

**Page 3 — Order Status Analysis**

- Home Appliances had the highest cancellation value (₹36K), followed by Electronics (₹27K)
- Cancellations spiked in March compared to February
- PayPal and Debit Card together account for over 63% of cancelled order value — signals potential payment flow issues

---

## Tech Stack

| Tool | Usage |
|---|---|
| Python (Pandas, Matplotlib, Seaborn) | Data cleaning, EDA, feature engineering, customer type labelling |
| Excel | Initial inspection, formatting, null handling |
| Power BI + DAX | 3-page interactive dashboard, KPI cards, cohort visuals |
| Power Query | Data shaping and filtering |

---

## Files

| File | Description |
|---|---|
| `Sales Analysis.ipynb` | Python notebook — cleaning, EDA, customer segmentation |
| `amazon_sales_data.csv` | Cleaned dataset ready for Power BI |
| `Amazon Sales Dashboard.pbix` | Full 3-page Power BI dashboard |

