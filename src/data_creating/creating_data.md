# Synthetic Data Creation

Here will have a explanation of synthetic data files, where explain the important things about these.This project uses multiple datasets to simulate the operations of a bakery/cafeteria. Below are the details of each dataset used in the analysis:

## 1. **Sales Data (CSV)**

The sales data contains transactional information for each purchase made at the bakery/cafeteria.

- **Transaction ID**: Unique ID for each transaction
- **Customer ID**: ID of the customer making the purchase
- **Product ID**: ID of the product purchased
- **Quantity**: Quantity of the product purchased
- **Price**: Price per product
- **Discount Applied**: Discount applied on the transaction
- **Total Amount**: Total transaction amount
- **Transaction Date**: Date and time of purchase
- **Payment Method**: E.g., cash, card, mobile payment

---

## 2. **Customer Data (CSV)**

The customer data includes demographic details such as age, gender, and loyalty status.

- **Customer ID**: Unique ID for each customer
- **Name**: Customer's name
- **Age**: Customer's age
- **Gender**: Gender of the customer
- **Location**: Location of the customer (e.g., district)
- **Loyalty Status**: First-time customer, Regular, or VIP

---

## 3. **Inventory Data (JSON)**

The inventory data tracks the stock levels and reorder points for each product in the bakery.

- **Product ID**: Unique ID for each product
- **Product Name**: Name of the product
- **Stock Level**: Number of items currently in stock
- **Reorder Level**: Threshold for restocking
- **Supplier**: Supplier name (if needed)

---

## 4. **External Data (Weather/Event Data - CSV)**

This dataset includes external factors, such as weather conditions and events, that may influence sales.

- **Date**: Date of the event or weather data
- **Weather Condition**: Sunny, rainy, etc.
- **Temperature**: Temperature in Celsius
- **Event Type**: Type of event (e.g., concert, festival)