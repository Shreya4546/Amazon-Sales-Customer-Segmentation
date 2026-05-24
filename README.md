# Amazon Sales & Customer Segmentation Analysis
### Python Â· Excel Â· Power BI Â· DAX

End-to-end sales analysis of 250 Amazon orders (Febâ€“Apr 2025) covering revenue trends, customer segmentation, and cancellation diagnostics â€” delivered as a 3-page interactive Power BI dashboard.

---

## Business Questions Addressed

1. Which product categories and months drive the most revenue?
2. How do Top vs Regular customers differ in spend and order volume?
3. Where are cancellations concentrated â€” by category and payment method?
4. Which payment methods are preferred by high-value customers?

---

## Key Findings

| Metric | Value |
|---|---|
| Total Sales | â‚¹244K across 250 orders |
| Avg Order Value | â‚¹975.38 |
| Top category | Electronics (â‚¹130K) + Home Appliances (â‚¹105K) = 95%+ of revenue |
| Peak month | February (â‚¹123K), followed by March (â‚¹118K) |
| Top customer segment | "Top" buyers â€” â‚¹147K in sales, ~60% of total revenue, 55.6% of orders |
| Highest cancellation category | Home Appliances (â‚¹36K cancelled) |
| Cancellations by payment | PayPal (32.37%) and Debit Card (30.73%) drove most cancelled order value |
| Credit Card cancellation | 32% of all cancellations came from Credit Card users |

---

## Dashboard Pages

### Page 1 â€” Sales Overview
KPIs: Total Sales Â· Total Orders Â· Avg Order Value

- Sales peaked in February at â‚¹123K, dropping to â‚¹3K in April
- Electronics and Home Appliances together account for over 95% of revenue
- Credit Card (28.56%) and Amazon Pay (25.26%) are the top payment methods by volume

### Page 2 â€” Customer Insights
- Top customers (55.6% of orders) generated â‚¹147K vs â‚¹96K from Regular customers
- Top 3 customers by revenue: Olivia Wilson (â‚¹36,170) Â· Jane Smith (â‚¹31,185) Â· Emma Clark (â‚¹29,700)
- Customer base spans multiple US cities including New York, San Francisco, and Chicago

### Page 3 â€” Order Status Analysis
- Home Appliances had the highest cancellation value (â‚¹36K), followed by Electronics (â‚¹27K)
- Cancellations spiked in March compared to February
- PayPal and Debit Card together account for over 63% of cancelled order value â€” signals potential payment flow issues

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
| `Sales Analysis.ipynb` | Python notebook â€” cleaning, EDA, customer segmentation |
| `amazon_sales_data.csv` | Cleaned dataset ready for Power BI |
| `Amazon Sales Dashboard.pbix` | Full 3-page Power BI dashboard |
