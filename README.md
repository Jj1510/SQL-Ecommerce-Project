# 🛒 SQL E-Commerce Project

A simple SQL project simulating an e-commerce database. It includes schema creation, sample data, advanced queries, views, and triggers. Useful for learning relational database design and SQL analytics.

---

## 📌 Project Features

- Product and category management
- Order tracking and payment details
- Customer information and behavior
- Views for best sellers and high-value customers
- Triggers for automatic status updates

---

## 🗃️ Database Schema

**Tables:**
- `Users`: Customer information
- `Products`: Items for sale
- `Categories`: Product categories
- `Orders`: Order info
- `Order_Items`: Order-specific items
- `Payments`: Payment status and method

> See `schema.sql` for full table creation.

---

## 📎 Sample Data

Located in `sample_data.sql`. Includes:
- 5 users
- 5 products
- 2 categories
- 3 orders with multiple items
- Payments

---

## 🔍 Sample Queries

See `queries.sql` for:
- Top-selling products
- Revenue per month
- Most valuable customers
- Product stock levels

---

## 🔍 Views

See `views.sql`:
- `view_top_customers`
- `view_best_selling_products`

---

## ⚙️ Triggers

See `triggers.sql`:
- Update `order_status` to 'Completed' when payment is successful

---

## 🚀 How to Run

1. Load the schema:
   ```sql
   source schema.sql;
