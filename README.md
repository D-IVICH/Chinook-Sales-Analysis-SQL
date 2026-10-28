# Chinook-Sales-Analysis-SQL
 SQL-based analysis of sales performance using the Chinook database and PostgreSQL

# 📌 Project Overview

This project analyzes sales data from the Chinook Digital Music Store database using PostgreSQL. The objective is to extract meaningful business insights from sales transactions, customer purchases, product performance, and revenue trends.

SQL queries were used to explore sales performance, identify high-revenue markets and products, analyze monthly revenue, and rank tracks based on their revenue contribution.

# 🎯 Project Objectives

- What is the overall sales revenue and average invoice value?
- Which countries generate the highest revenue?
- Which customers spend the most?
- Which tracks sell the highest number of units?
- Which tracks generate the most revenue?
- Which music genres contribute the most revenue?
- Which artists generate the highest revenue?
- How does revenue vary from month to month?
- How can SQL window functions rank tracks by revenue?

# 🛠️ Tools and Technologies

- Database: Chinook Digital Music Store
- Query Language: SQL
- Database Management System: PostgreSQL
- SQL Environment: pgAdmin
- Results and Reporting: CSV exports and Markdown documentation

# 📊 Key Findings

1. Overall Sales Performance

- Total revenue from invoice line items: $2,328.60
- Number of invoices: 412
- Average invoice value: $5.65

2. Revenue by Country

Country| Revenue
USA| $523.06
Canada| $303.96
France| $195.10
Brazil| $190.10
Germany| $156.48

The USA generated the highest revenue, followed by Canada.

3. Customer Spending

Customer| Total Spent
Helena Holý| $49.62
Richard Cunningham| $47.62
Luis Rojas| $46.62
Hugh O'Reilly| $45.62
Ladislav Kovács| $45.62

Helena Holý ranked first, with total spending of $49.62.

4. Revenue by Genre

Genre| Revenue
Rock| $826.65
Latin| $382.14
Metal| $261.36
Alternative & Punk| $241.56
TV Shows| $93.53

Rock generated the highest revenue among the genres shown.

5. Revenue by Artist

Artist| Revenue
Iron Maiden| $138.60
U2| $105.93
Metallica| $90.09
Led Zeppelin| $86.13
Lost| $81.59

Iron Maiden ranked first in artist revenue.

6. Monthly Sales Performance

- Highest-revenue month: January 2010 — $52.62
- Lowest-revenue month: November 2011 — $23.76
- Monthly records analyzed: 60

7. Track Sales and Revenue Ranking

The project analyzed tracks by quantity sold and revenue generated.

The "RANK()" window function was used to rank tracks by revenue. Tracks with equal revenue received the same rank.

# 💡 Business Recommendations

1. Monitor sales performance: Track revenue, invoice counts, and average invoice value over time.
2. Evaluate geographic markets: Investigate purchasing patterns in high-revenue countries, particularly the USA and Canada.
3. Understand customer behaviour: Examine customer spending and purchase frequency.
4. Compare product performance: Analyze units sold alongside revenue.
5. Review genre and artist performance: Investigate products contributing the most revenue.
6. Monitor monthly trends: Examine revenue changes over time to support sales planning.

# 🧠 SQL Skills Demonstrated

- "SELECT" statements
- "INNER JOIN"
- Aggregate functions: "SUM()", "COUNT()", and "AVG()"
- "GROUP BY"
- "ORDER BY"
- "LIMIT"
- Date-based aggregation using "DATE_TRUNC()"
- Window functions using "RANK()"
- Analysis across multiple related tables

# 📝 Conclusion

This project demonstrates how SQL can be used to analyze sales transactions and derive business insights from a relational database.

By examining revenue, customer spending, geographic performance, product sales, genre and artist contributions, and monthly trends, the analysis provides a structured view of the Chinook Digital Music Store's sales performance.

The project demonstrates practical skills in SQL joins, aggregation, date-based analysis, and window functions.

---

## Project Category: Data Analytics | SQL | Sales Analysis
