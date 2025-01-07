# SQL Project

### Executive Summary
This report provides insights derived from analyzing the rental database schema. The analysis
covers the following aspects:
- Popular films and categories.
- Customer rental trends, including seasonality and high-performing customers.
- Store revenue performance.
- Late returns and overdue rentals.
Key recommendations are presented to improve decision-making in film inventory, customer engagement, and operational efficiency.

### Methodology
#### Database Schema Analysis
##### Primary Keys: Unique identifiers for tables such as film_id, customer_id,rental_id, and store_id.
##### Foreign Keys: Relationships between tables:
- film_id links the films table with rentals.
- customer_id links the customers table with rentals.
- store_id connects the stores table with rentals.
##### Relationships:
- films and categories: Determines which category each film belongs to.
- customers and rentals: Tracks customer rental activities.
- stores and rentals: Links rental transactions to specific stores.
#### Data Retrieval
SQL queries were written to retrieve and transform data:
- Aggregate functions were used to calculate totals and averages.
- Joins linked relevant tables to gather information.
- Subqueries enabled detailed breakdowns of data.

### Key Insights
a. Popular Films and Categories
- Most Rented Films: Films in the categories of "Sports", "Animation", and “Action” showed the highest rentals, indicating their popularity among customers.
- Number of Films per Category: Categories such as "Action", “Drama”, and "Sci-Fi" have fewer films but still rank high in rentals, suggesting demand for these genres.

b. Customer and Rental Trends
- Top 5 Customers: The top-performing customers rented significantly more films, contributing to a large portion of revenue. These customers can be targeted for loyalty programs.
- Seasonality Trends: Rentals peaked during holiday seasons (summer months), while weekdays showed lower rentals compared to weekends.

c. Revenue by Store
- Stores 2 generated higher revenues due to higher rental volumes.

d. Late Returns and Overdue Rentals
- Patterns in Late Returns: Customers renting popular films were more likely to return films late.
- Overdue Rentals: 10% of all rentals exceeded the allowed rental duration without a return.

### Recommendations
#### Inventory Management
- Increase Stock of Popular Categories: Focus on increasing inventory for Sport, Animation, Action, Sci-Fi, and Family genres.
- Seasonal Inventory Adjustments: Stock more films ahead of peak rental seasons (festive periods, summer holidays).
#### Customer Engagement
- Loyalty Program for Top Customers: Reward high-performing customers with discounts or free rentals to encourage repeat business.
- Targeted Marketing: Use insights to tailor promotional offers to specific customer segments (e.g., families, couples).
#### Operational Improvements
1. Improve Late Return Management:
- Introduce SMS/email reminders for due dates.
- Implement penalties for overdue rentals.
2. Agent Performance: Provide incentives for agents contributing significantly to rentals and revenue.

### Data-Driven Decision Making
1. Monitor Monthly Trends: Use dashboards to track rental patterns and adjust operations accordingly.
2. Enhance Reporting: Regularly update metrics such as rentals per month, customer segments, and revenue per store.

![Screenshot 2025-01-07 184949](https://github.com/user-attachments/assets/4ce7d9a5-e8c8-4b22-bc6f-f5cb13306f01)
![Screenshot 2025-01-07 185019](https://github.com/user-attachments/assets/a3d5e3e3-fcf5-44ff-839b-6d9d56823de3)
