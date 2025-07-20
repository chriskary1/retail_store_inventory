# 📈 Sales Forecasting with Prophet

This project focuses on forecasting daily sales using Facebook's Prophet library, based on historical sales data from multiple stores, products, and regions.

---

## 📊 Dataset

The dataset contains transactional and contextual information, including:
- **Date**: Sales date
- **Store ID**: Store identification
- **Product ID**: Product identification
- **Category**: Product category
- **Region**: Sales region
- **Inventory Level**: Stock available
- **Units Sold**: Actual sales quantity (target)
- **Units Ordered**: Ordered quantity
- **Demand Forecast**: Original forecast
- **Price**: Unit price
- **Discount**: Applied discount
- **Weather Condition**: Weather during sales
- **Holiday/Promotion**: Whether a holiday or promotion was active
- **Competitor Pricing**: Competitor’s pricing data
- **Seasonality**: Season indicator

---

## 🎯 Goal

Predict future **Units Sold** using:
- Prophet's built-in trend and seasonality modeling
- Optional use of external regressors (weather, promotions, etc.)

---

## 📉 Methods

Data filtering (select date and units sold)

Prophet modeling with daily/weekly/yearly seasonality

Forecast visualization

Export results to CSV

