# Day 1 - Hotel Customer Retention Analysis

## Business Problem

A hotel booking platform wants to identify high-value repeat customers for loyalty and retention campaigns.

The marketing team wants to analyze:

- Customers with repeated bookings
- Revenue contribution by each customer
- Cancellation behavior
- Average booking frequency

The goal is to help the business target loyal customers with personalized offers.

---

## Tables Used

### customers

| Column Name | Data Type |
|------------|------------|
| customer_id | INT |
| customer_name | VARCHAR |
| city | VARCHAR |
| signup_date | DATE |

---

### bookings

| Column Name | Data Type |
|------------|------------|
| booking_id | INT |
| customer_id | INT |
| hotel_id | INT |
| booking_date | DATE |
| checkin_date | DATE |
| checkout_date | DATE |
| booking_amount | DECIMAL |
| booking_status | VARCHAR |

---

## Requirements

Write a SQL query to find:

- Customers with more than 2 completed bookings
- Total revenue generated
- Cancellation rate
- Average days between bookings
- Revenue rank within each city

---

## SQL Concepts Used

- CTEs
- JOINs
- Aggregate Functions
- CASE WHEN
- Window Functions
- LAG()
- DENSE_RANK()
- DATEDIFF()

---

## Files Included

| File | Description |
|------|-------------|
| solution.sql | Final SQL solution |
| dataset.csv | Sample dataset |
| output.png | Query output screenshot |

---

## Business Insights

- Identified high-value repeat customers
- Measured cancellation trends
- Analyzed customer booking frequency
- Ranked customers based on city-wise revenue contribution

---

## Status

✅ Completed
