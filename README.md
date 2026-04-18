# Kikilicious FoodHub — Data Analysis

Exploratory data analysis of a food delivery platform covering customer behaviour, restaurant performance, delivery efficiency, and revenue.

-----

## Dataset

|Field                  |Description                    |
|-----------------------|-------------------------------|
|`order_id`             |Unique order identifier        |
|`customer_id`          |Unique customer identifier     |
|`restaurant_name`      |Name of the restaurant         |
|`cuisine_type`         |Type of cuisine ordered        |
|`cost_of_the_order`    |Order cost in USD              |
|`day_of_the_week`      |Weekday or Weekend             |
|`rating`               |Customer rating out of 5       |
|`food_preparation_time`|Minutes to prepare food        |
|`delivery_time`        |Minutes from pickup to delivery|

**1,898 rows · 9 columns · No missing values**

-----

## Key Findings

- **63%** of orders are placed on weekends
- **American cuisine** leads with 584 orders (30.8%), followed by Japanese and Italian
- Average delivery time is **~24 minutes**, but 10.5% of orders exceed 60 minutes total
- Only **29.2%** of orders cost more than $20
- **736 orders (~38.8%)** were never rated
- Net revenue of **$6,166.30** via a tiered commission model (15–25%)
- Cost, prep time, and delivery time show **no significant linear correlation**

-----

## Project Structure

```
kikilicious/
├── Kikilicious_Analysis.ipynb   # Full EDA notebook
├── kikilicious_orders.csv       # Raw dataset
├── kikilicious_infographic_black.jpg  # Summary infographic (dark)
└── README.md
```

-----

## Tools Used

- **Python** — pandas, numpy, matplotlib, seaborn
- **Power BI** — interactive dashboard

-----

## Recommendations

1. **Incentivise ratings** — loyalty points or discounts to reduce the 38.8% unrated order gap
1. **Reduce delivery delays** — route optimisation targeting orders exceeding 60 minutes
1. **Cuisine-based marketing** — amplify American and Japanese promotions on weekends
1. **Support low-rated restaurants** — share operational insights to improve quality scores
