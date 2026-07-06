# DAX Measures & Calculated Columns

## 1. Total Sales (Measure)
Aggregates total sales by Order Date using SUMMARIZE for time-series forecasting.

```DAX
Salesforecast = SUMMARIZE(
    'SuperStore_Sales_Dataset',
    'SuperStore_Sales_Dataset'[Order Date],
    "Total Sales", SUM('SuperStore_Sales_Dataset'[Sales])
)
```

## 2. Average Delivery Days (Calculated Column)
Calculates the number of days between Order Date and Ship Date for each order.

```DAX
AvgDelivery = DATEDIFF(
    'SuperStore_Sales_Dataset'[Order Date],
    'SuperStore_Sales_Dataset'[Ship Date],
    DAY
)
```
