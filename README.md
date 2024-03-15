# Retro Arcade E-Commerce Order Analysis Tool

This GitHub repository contains a Jupyter Notebook developed for analyzing and managing e-commerce order data for a small business specializing in retro home arcade game machine parts. The Python-based tool is designed for businesses that feature a limited product catalog and operate in specific geographical regions with varying tax rates. 

## Features

- **Product and Order Classes:** Object-oriented approach to represent products and orders, encapsulating attributes like part details, manufacturer, price, order number, tax rate, and discount rate.
- **Data-Driven:** Utilizes real-world data such as product catalogs, state tax rates, promo codes, and past order data to simulate an e-commerce environment.
- **Order Creation and Management:** Functionality to create orders from data, manage order details, and calculate financial aspects like subtotal, taxes, and discounts.
- **Analytical Summary Tables:** Dynamic generation of summary tables for individual orders and monthly revenue, using the `tabulate` package for clear, formatted output.
- **Data-Driven Insights:** Analysis of total orders, total revenue, total products sold, average order size, and average revenue per order.

## Usage

1. **Initialization**: Run the initial code cell to load necessary data - product catalog, state tax rates, promo codes, and last month's order data.
2. **Class Definitions**: Utilize the `Product` and `Order` classes to represent and manage e-commerce entities.
3. **Order Processing**: Use the `createOrder` function to convert raw data into structured order objects.
4. **Load Orders**: Dynamically load orders from the given data and append them to a list for further processing.
5. **Order Summary**: Generate a detailed order summary table including size, sub-total, tax, discount, and total for each order.
6. **Monthly Revenue Summary**: Analyze the monthly performance with a summary table showing total orders, products sold, total revenue, average order size, and average revenue per order.

## Data Structure

- **Product Catalog**: A dictionary containing product details such as the manufacturer, name, category, and price.
- **State Tax Rates**: A dictionary mapping state abbreviations to their respective tax rates.
- **Promo Codes**: A dictionary mapping promo codes to discount rates.
- **Last Month's Order Data**: A tuple of order records, each containing order number, state, parts, and quantities.

## Requirements

- Python 3.x
- Jupyter Notebook
- `tabulate` Python package for table generation

---
