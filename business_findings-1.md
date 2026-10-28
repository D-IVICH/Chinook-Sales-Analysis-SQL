# Business Findings: Chinook Digital Music Store Sales Analysis

## 1. Overview

This report presents the main business findings from an SQL analysis of the Chinook Digital Music Store database. The analysis examines sales revenue, customer spending, geographic performance, genre and artist revenue, track performance, and monthly sales trends.

## 2. Overall Sales Performance

| Metric | Result |
|:---|---:|
| Total revenue from invoice line items | $2,328.60 |
| Number of invoices | 412 |
| Average invoice value | $5.65 |

**Business insight:** These metrics provide a high-level view of the store's recorded sales activity.

## 3. Revenue by Country

| Country | Revenue |
|:---|---:|
| USA | $523.06 |
| Canada | $303.96 |
| France | $195.10 |
| Brazil | $190.10 |
| Germany | $156.48 |

**Business insight:** The USA was the largest revenue contributor among the countries listed, followed by Canada.

## 4. Customer Spending

| Customer | Total Spent |
|:---|---:|
| Helena Holý | $49.62 |
| Richard Cunningham | $47.62 |
| Luis Rojas | $46.62 |
| Hugh O'Reilly | $45.62 |
| Ladislav Kovács | $45.62 |

**Business insight:** Helena Holý had the highest total spending among the customers listed.

## 5. Revenue by Genre

| Genre | Revenue |
|:---|---:|
| Rock | $826.65 |
| Latin | $382.14 |
| Metal | $261.36 |
| Alternative & Punk | $241.56 |
| TV Shows | $93.53 |

**Business insight:** Rock generated the highest revenue among the genres listed, followed by Latin and Metal.

## 6. Revenue by Artist

| Artist | Revenue |
|:---|---:|
| Iron Maiden | $138.60 |
| U2 | $105.93 |
| Metallica | $90.09 |
| Led Zeppelin | $86.13 |
| Lost | $81.59 |

**Business insight:** Iron Maiden generated the highest revenue among the artists listed.

## 7. Track Sales and Revenue

The analysis considered track performance by both quantity sold and revenue generated. The quantity analysis showed ties among the leading tracks, while the revenue analysis used SQL's `RANK()` window function to assign rankings. Tracks with equal revenue received the same rank.

**Business insight:** Looking at both units sold and revenue provides a broader view of product performance than relying on either measure alone.

## 8. Monthly Sales Performance

The monthly analysis covered 60 monthly records.

| Metric | Result |
|:---|:---|
| Highest-revenue month | January 2010 |
| Highest monthly revenue | $52.62 |
| Lowest-revenue month | November 2011 |
| Lowest monthly revenue | $23.76 |

**Business insight:** Revenue varied across the months analyzed. Monitoring monthly performance can help the business identify patterns and investigate changes in sales.

## 9. Business Recommendations

1. **Monitor key sales indicators:** Track revenue, invoice counts, and average invoice value over time.
2. **Study high-revenue markets:** Explore purchasing patterns in the USA and Canada.
3. **Understand customer behaviour:** Examine customer spending and purchase frequency.
4. **Evaluate products using multiple measures:** Compare quantity sold with revenue generated.
5. **Review genre and artist contributions:** Use revenue rankings to understand which categories and artists contribute most to sales.
6. **Track monthly changes:** Review sales trends over time to support planning and further business analysis.

## 10. Conclusion

The SQL analysis provides a structured view of the Chinook Digital Music Store's recorded sales performance. It identifies leading countries, customers, genres, and artists, and highlights variation in monthly revenue.

The project demonstrates how SQL joins, aggregate functions, date-based analysis, and window functions can be used to turn relational data into practical business findings.
