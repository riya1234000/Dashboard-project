## 📊 Excel Dashboard Project: Dynamic Business Insights
Welcome to my Excel Dashboard project — a fully interactive, filter-driven analytics tool built to transform raw Call Centre data into clear, actionable insights. This project demonstrates my ability to automate reporting, apply formulas, and design clean, user-friendly dashboards using Excel.

## Project Overview
This dashboard allows users to analyze Call Centre performance across multiple dimensions in Table 1:-  such as Call number, Customer_ID, Duration, Representation, Date_of_call, Purchase Amount, FY, Day_of_week, Duration Busket, Rating Rounded. In Table 2:- Customer_ID, Gender, Age, City. It uses dropdown filters, dynamic summary tables, and responsive charts to deliver real-time insights in 2023.

## Dataset used
[Dataset](https://github.com/riya1234000/Dashboard-project/blob/main/call%20centre.xlsx)
## Questions (KPI'S)
1. Which month had the highest and lowest call volume, and what business factors might explain this?
- Highest: March (155 calls) — possibly due to fiscal year-end or campaign activity.
- Lowest: August (50 calls) — likely impacted by holiday season or reduced customer engagement.
2. What is the average monthly call volume, and how many months fall below this benchmark?
- Months below average: Jan, Feb, May, Jun, Jul, Aug, Sep, Nov, Dec → 9 months\
3. Which day has the highest and lowest call volume, and what might explain this?
- Highest: Saturday (161 calls)
- Lowest: Thursday (128 calls)
- Insight: Saturday’s peak may reflect weekend customer availability. Thursday’s dip could be mid-week fatigue or fewer service requests.
4. What is the average daily call volume, and which days exceed it?
- by calculating Average
- Days above average: Saturday (161), Wednesday (153), Sunday (146)
- Days below average: Monday (133), Tuesday (138), Thursday (128), Friday (141)
5. Which day might benefit from additional support or campaign targeting?
Thursday (128 calls) is the lowest — consider promotions, reminders, or service boosts to lift engagement.
6. Which representative handled the most calls, and did that translate into the highest revenue?
- Most Calls: R02 (218 calls)
- Highest Revenue: R03 (₹20.9K)
- Insight: R02 is busiest, but R03 is most revenue-efficient — a great point for performance optimization.
7. How can we use this data to optimize team performance or incentives?
- Strategy:
- Reward reps like R03 for high revenue efficiency
- Provide coaching to R04 to improve conversion
- Balance workload between R02 and others to avoid burnout
8. Which city has the highest number of calls, and what does that imply for resource allocation?
- Highest: Cleveland (389 calls)
- Insight: Cleveland may require more representatives or targeted campaigns due to higher engagement.
9. Which city has the most balanced gender distribution, and how might that affect service strategy?
- Most balanced: Cincinnati (144 Female, 132 Male)
- Insight: Balanced demographics allow for neutral messaging and equal service design.
10. Which city has the highest female-to-male ratio, and what could be the reason?
- Cleveland: 326 Female vs. 63 Male → Ratio ≈ 5.2:1
- Insight: May reflect product preference, marketing bias, or demographic concentration.
11. Does gender distribution vary significantly across cities, and how should campaigns adapt?
  - Yes.
- Cleveland: Female-dominant
- Columbus: Male-dominant
- Cincinnati: Balanced
- Action: Tailor messaging and offers based on city-specific gender trends.
12. What is the overall gender split across all cities, and does it align with satisfaction or purchase trends?
Total: 599 Female, 401 Male
- Insight: Females dominate call volume. Further analysis needed to see if they also drive higher satisfaction or revenue.
13. Which city has the highest total sales across all customers?
- Cleveland
- Customers like C0007, C0013, and C0009 contribute significantly
- Insight: Cleveland is a revenue hotspot — ideal for focused campaigns and resource allocation.
14. Which customer has the highest Grand Total sales?
- C0005 (Columbus): ₹7,747
- Insight: Premium customer — prioritize retention, loyalty programs, and upselling.
15. Which region (R01–R05) consistently performs best across cities?
- R02
- High contributions from multiple customers across all cities
- Example: C0005 (₹2,280), C0007 (₹1,982), C0013 (₹1,877)
- Insight: R02 is a strategic region — consider expanding services or incentives here.
16. Which customer has the most balanced sales across all regions?
- C0013 (Cleveland)
- Sales range from ₹1,255 to ₹1,874 across R01–R05
- Insight: Consistent engagement — ideal for cross-region promotions.
17. Are there customers with strong regional bias in their purchases?
- Yes.
- C0001 (Columbus): Heavy in R01 and R02, lower in R03–R05
- C0004 (Cincinnati): Strong in R01 and R02, weaker in R04 and R05
- Insight: Tailor regional offers based on customer preferences.
[view Dashboard](https://github.com/riya1234000/Dashboard-project/blob/main/Screenshot%202025-11-06%20001203.png)
## Process
verify data for any missing value and anomalies sort out the same.
Made sure data is consistent and clean with respect to data type, data format and values used.
Created pivot tables according to the questions asked.
Merge all pivot tables into one dashboard and apply slicer to make dynamic.
Dashboard Screenshot

## Project Insights
The West region leads with ₹5,835,615.62 in net sales and a 21.00% profit share, indicating peak performance. In contrast, the South region trails with ₹5,333,577.25 and 19.14%, highlighting room for strategic improvement.
Raipur and Pune lead with net sales over ₹20.5 lakh and profit shares of 7.45% and 7.30%, respectively — signaling high-performing urban markets. In contrast, Hydrabad, sales (₹17.32 lakh), shows a lower profit share of 6.16%, suggesting margin challenges.
Offline purchases slightly lead, with 50.16% of transactions — indicating a continued trust in physical retail despite digital growth.
Online sales are nearly equal at 49.84%, showing strong digital adoption and potential for e-commerce expansion.
UPI is the most preferred payment method, used in 25.38% of transactions — reflecting customer comfort with digital payments.
Card (25.17%), COD (25.18%), and Wallet (24.27%) are nearly evenly distributed, suggesting a diverse payment landscape with no dominant method.
Home Decor and Beauty lead with net sales over ₹70 lakh and 24% profit margins, making them the most lucrative categories.
Lamp (8.59% sales, 8.39% quantity) and Laptop (8.33% sales, 8.94% quantity) show strong alignment between revenue and demand — ideal for scaling. Meanwhile, Mobile lags slightly in sales share (7.74%) despite decent quantity (8.11%), suggesting pricing or margin challenges.
In-Transit orders account for the highest net sales at ₹7,043,927.72 (25.26%), indicating strong ongoing fulfillment. Meanwhile, Cancelled orders still represent a significant ₹6,875,131.49 (24.65%), suggesting a need to investigate drop-off reasons and improve conversion.
January (13.66%), March (13.46%), and February (13.03%) are peak months for sales, indicating strong Q1 performance. The remaining months average around 6–7%, suggesting seasonal dips and opportunities for targeted campaigns.
Digital Marketing Strategy: Driving Growth from Insights
Based on the dashboard findings, here’s how digital marketing can amplify results:

Target High-Performing Segments Promote top categories (Home Decor, Beauty) with influencer campaigns and seasonal bundles.
Focus ads on high-converting cities like Raipur and Pune using geo-targeted promotions.

Boost Online Engagement Run retargeting ads for cart abandoners to reduce cancellations.
Offer exclusive online discounts and loyalty rewards to shift preference from offline to online.

Leverage Payment Preferences Highlight UPI and Wallet offers in digital ads to match customer behavior.
Use COD as a trust-building tool in new markets.

Seasonal Campaign Planning Launch major campaigns in Q1 (Jan–Mar) when sales are highest.
Use email and social media to build anticipation for peak months.

Content Strategy Share insights from the dashboard as blog posts, infographics, or LinkedIn updates to build brand authority.
Create product-focused reels or carousel posts showing top-selling items and customer reviews.
