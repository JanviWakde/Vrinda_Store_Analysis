# Vrinda Store Data Analysis

### Objective
This repository contains an end-to-end analysis of Vrinda Store’s 2022 sales data. It consolidates raw transaction-level data across multiple channels (Amazon, Flipkart, Myntra, Ajio, Meesho, Nalli, Others) and derives insights into revenue, order volumes, customer segments, geography, product categories, and order outcomes. The deliverable is intended to support business stakeholders in performance tracking, channel optimization, merchandising, and campaign planning.

### Project Goals
- Build a single source of truth for 2022 sales performance.
- Quantify revenue and order trends over time.
- Identify top-performing customer segments (gender, age groups).
- Benchmark channels, categories, and geographies.
- Diagnose leakage via cancellations, returns, and refunds.
- Provide actionable recommendations for growth and efficiency.

### Data Dictionary (Vrinda Store sheet)
- Order ID: Marketplace order identifier 
- Cust ID: Customer identifier 
- Gender: Men/Women
- Age: Customer age
- Age Group: Teenager, Adult, Senior
- Date: Order date 
- Month: Month name 
- Status: Delivered, Cancelled, Returned, Refunded
- Channel: Amazon, Flipkart, Myntra, Ajio, Meesho, Nalli, Others
- SKU: Stock keeping unit 
- Category: Product category (e.g., Set, kurta, Saree, Top, Western Dress, etc.)
 -Size: Apparel size (S, M, L, XL, XXL, 3XL, Free, etc.)
- Qty: Quantity (integer)
- Currency: INR
- Amount: Order line amount in INR 
- ship-city/ship-state/ship-postal-code/ship-country: Shipping destination info
- B2B: True/False  

### Key Insights 
#### Annual Trend:
- Revenue and orders are relatively steady across months with some softening in Q4 (Oct–Dec) versus early-year peaks (Mar).
- Sales Vs Orders (Sum of Amount, Count of Orders) – highest in March; tapering toward November/December.

#### Customer Segments:
Women drive the majority of revenue versus men.
- Women: 13,562,773
- Men: 7,613,604

#### Age groups (share of orders):
- Women: strongest in Adult and Teenager segments (notable shares in Adult 0.346, Teen 0.211)
- Men: meaningful share also from Teens and Adults (Adult 0.155, Teen 0.092)

#### Order Outcomes:
- Delivered orders dominate: 28,641

#### Leakage:
- Cancelled: 844
- Returned: 1,045
- Refunded: 517

#### Geography:
Top revenue states:
- Maharashtra: 2,990,221
- Karnataka: 2,646,358
- Uttar Pradesh: 2,104,659
- Telangana: 1,712,439
- Tamil Nadu: 1,678,877

#### Channels:
- Order share indicates Amazon as the leading channel (~0.355), followed by Myntra (~0.234), Flipkart (~0.216), Ajio (~0.062), Nalli (~0.048), Meesho (~0.045), Others (~0.041).

#### Categories and Products:
- Categories include Set, kurta, Western Dress, Saree, Top, Blouse, Ethnic Dress, Bottom.
- Sets and kurtas feature heavily across channels; Sarees drive value in certain months and channels.

### Business Questions Answered
- Which months led the year in sales and orders?
- What is the revenue split by gender and how does it map to age groups?
- Which states and cities contribute most to revenue?
- Which channels deliver the most orders and best mix of categories?
- What proportion of orders are cancelled/returned/refunded?
- Which categories and sizes are most frequently purchased?





