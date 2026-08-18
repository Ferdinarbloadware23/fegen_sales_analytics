# 02. Data Dictionary

## 1. Master Product

**Grain:** 1 row = 1 SKU / product variant

| Column | Data Type | Description |
|---|---|---|
| product_id | VARCHAR | Unique identifier for each product |
| sku | VARCHAR | Product SKU or reference code |
| product_name | VARCHAR | Product name |
| variant | VARCHAR | Product variation |
| category | VARCHAR | Product category |
| brand | VARCHAR | Product brand |
| cost_price | DECIMAL | Cost per unit |
| selling_price | DECIMAL | Selling price per unit |
| reorder_level | INT | Minimum stock level for restocking |
| is_active | BOOLEAN | Indicates whether the product is active |

---

## 2. Sales Header

**Grain:** 1 row = 1 order

| Column | Data Type | Description |
|---|---|---|
| order_id | VARCHAR | Unique order identifier |
| customer_id | VARCHAR | Customer identifier |
| order_date | DATETIME | Order creation date |
| payment_date | DATETIME | Payment date |
| status | VARCHAR | Order status |
| platform | VARCHAR | Sales platform |

---

## 3. Sales Detail

**Grain:** 1 row = 1 product/SKU within an order

| Column | Data Type | Description |
|---|---|---|
| detail_id | INT | Internal unique identifier |
| order_id | VARCHAR | Reference to the related order |
| product_id | VARCHAR | Reference to the product |
| quantity | INT | Quantity sold |
| price_unit | DECIMAL | Selling price per unit |
| price_total | DECIMAL | Total value of the product line |

---

## 4. Stock Movement

**Grain:** 1 row = 1 inventory movement

| Column | Data Type | Description |
|---|---|---|
| movement_id | INT | Internal unique identifier |
| product_id | VARCHAR | Reference to the product |
| movement_date | DATE | Inventory movement date |
| movement_type | VARCHAR | Type of inventory movement |
| quantity | INT | Quantity moved |
| unit_cost | DECIMAL | Cost per unit |
| source | VARCHAR | Source of the inventory movement |
