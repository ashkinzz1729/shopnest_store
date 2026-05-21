# ShopNest Store — Exploratory Data Analysis (EDA)

A beginner-level Python EDA project on an e-commerce store dataset.
Analysed 99,000+ orders to find trends in sales, delivery, payments, and customer behaviour.

---

## What This Project Is About

ShopNest is an online store similar to Amazon or Flipkart.
The dataset has 9 CSV files covering orders, customers, products, sellers, payments, and reviews.

I explored the data to answer these simple business questions:
- How many orders are placed every month?
- Which product categories sell the most?
- How do customers prefer to pay?
- Are orders being delivered on time?
- What ratings do customers give?
- Which states have the most customers?

---

## Dataset Files

| File | What it contains | Rows |
|------|-----------------|------|
| orders.csv | All orders with timestamps and status | 99,441 |
| customers.csv | Customer city and state | 99,441 |
| order_items.csv | Product and price per order | 112,650 |
| payments.csv | Payment type and amount | 103,886 |
| reviews.csv | Customer ratings and comments | 99,224 |
| products.csv | Product details and category | 32,951 |
| sellers.csv | Seller location info | 3,095 |
| category_translation.csv | Portuguese to English category names | 71 |

---

## Charts Made (10 Total)

| # | Chart | What it shows |
|---|-------|--------------|
| 1 | Monthly Orders Trend | How order volume changed over time |
| 2 | Order Status Distribution | Delivered vs cancelled vs others |
| 3 | Top 10 Product Categories | Most ordered categories |
| 4 | Payment Method Pie Chart | Credit card vs boleto vs others |
| 5 | Review Score Distribution | How customers rated their orders |
| 6 | Revenue by Payment Method | Which method earns most revenue |
| 7 | Delivery Time Histogram | How many days to deliver |
| 8 | Customers by State | Which states have most customers |
| 9 | Price Distribution Box Plot | Price range per top 5 categories |
| 10 | Orders by Day of Week | Which day customers order most |

---

## Key Findings

1. Orders grew steadily from 2017 to mid-2018 with a clear peak
2. Over 95% of orders are successfully delivered
3. Bed/Bath/Table, Sports, and Furniture are the top selling categories
4. Credit card is used in 73%+ of all payments
5. Most customers give 5-star ratings
6. Average delivery time is around 12 days
7. São Paulo (SP) has the most customers
8. Customers order more on weekdays than weekends

---

## Tools Used

- Python 3
- Pandas — data loading and cleaning
- Matplotlib — charts and graphs
- Seaborn — styling

---

## How to Run

1. Clone this repository
2. Install required libraries:
```
pip install pandas matplotlib seaborn
```
3. Open the notebook:
```
jupyter notebook ShopNest_EDA.ipynb
```
4. Run all cells from top to bottom

---

## Project Structure

```
shopnest-eda-project/
├── ShopNest_EDA.ipynb     ← Main notebook (open this)
├── README.md
├── requirements.txt
├── data/
│   ├── orders.csv
│   ├── customers.csv
│   ├── order_items.csv
│   ├── payments.csv
│   ├── reviews.csv
│   ├── products.csv
│   ├── sellers.csv
│   └── category_translation.csv
└── charts/
    ├── 01_monthly_orders_trend.png
    ├── 02_order_status.png
    ├── 03_top_categories.png
    ├── 04_payment_methods.png
    ├── 05_review_scores.png
    ├── 06_revenue_by_payment.png
    ├── 07_delivery_time.png
    ├── 08_customers_by_state.png
    ├── 09_price_distribution.png
    └── 10_orders_by_day.png
```

---

## Author

**Giridhar Namballa** | Civil Engineer (9+ yrs EPC) → Data Analyst

[LinkedIn](https://linkedin.com/in/giridharnamballa-a9333a7a) | [GitHub](https://github.com/ashkinzz1729)
