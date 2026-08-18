# 01. Business Understanding

## 1. Project Overview
Fegen Sales Analytics is an end-to-end sales analytics project developed using operational data from Fegen.id, an e-commerce business operating on the Shopee marketplace.

The project covers the complete analytics workflow, beginning with raw transactional data extraction, followed by data cleaning, database design, SQL analysis, dashboard development, and business reporting.

The primary objective is to transform raw sales data into structured information that supports operational monitoring and data-driven business decision-making.

---

## 2. Business Overview

Fegen.id is an e-commerce retail business operating on the Shopee marketplace, specializing in computer and smartphone accessories. The business generates revenue through product sales and manages daily operations including product sourcing, inventory management, product listing, order fulfillment, shipment coordination, and sales monitoring. Operational data from Shopee Seller Center is transformed into a structured analytics workflow to improve reporting accuracy and support data-driven business decision-making.

---

## 3. Business Process

```text
Supplier
    ↓
Product Procurement
    ↓
Inventory Receiving
    ↓
Warehouse Inventory
    ↓
Product Listing
    ↓
Customer Order
    ↓
Order Processing
    ↓
Shipment
    ↓
Order Completed
    ↓
Payment Settlement
    ↓
Sales Report
    ↓
Business Analysis
    ↓
Business Decision
```
---

## 4. Business Objectives

The objectives of this project are to:

- Monitor sales performance
- Monitor inventory availability and stock movement
- Evaluate product performance
- Analyze customer purchasing behavior
- Support operational reporting and data driven business decision-making

---

## 5. Business Questions

### Sales

- What is the total revenue?
- Which products generate the highest revenue?
- Which products generate the lowest sales?
- How do monthly sales trends change over time?

### Inventory

- Which products need to be restocked?
- What is the current inventory level for each product?

### Customer

- Who are the repeat customers?
- Who are the highest-value customers?

### Financial

- What is the average order value?
- How much does each product contribute to total revenue?
---

## 6. Data Sources

The project uses operational data exported from Shopee Seller Center as the primary data source. Additional reference datasets are included to support database design and analytical requirements.

| Dataset | Source | Purpose |
|----------|--------|---------|
| Sales Data | Shopee Seller Center | Sales and revenue analysis |
| Product Master | Internal product records | Product information and performance analysis |
| Inventory Data | Internal inventory records | Inventory monitoring and stock movement |
| Supplier Data* | Sample reference dataset | Supplier relationship and inventory reference |

> *Supplier information is simplified and anonymized for portfolio purposes.

---

## 7. Expected Deliverables

The project is expected to deliver the following outputs:

- Cleaned datasets for analysis
- Relational database implemented in MySQL
- SQL queries for business analysis
- Interactive dashboard in Microsoft Excel
- Business insights and recommendations
- Technical documentation of the analytics workflow
---

## 8. Key Performance Indicators

- Total Revenue
- Monthly Revenue
- Total Orders
- Current Stock
- Repeat Customers
- Average Order Value (AOV)
- Best Selling Products
- Product Revenue Contribution

---

## 9. Project Scope

This project includes the following activities:

- Data cleaning and preparation
- Relational database design and implementation
- SQL-based data analysis
- Dashboard development using Microsoft Excel
- Business insight generation and documentation

This project does not include:

- Machine learning or predictive modeling
- Sales forecasting
- Customer segmentation
- Real-time data integration


