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

## Dashboard Screenshot

[view Dashboard](https://github.com/riya1234000/Dashboard-project/blob/326952f4c0d99b16db59433f51ad0c37acd64f17/Screenshot%202026-02-14%20022223.png)



<img src="https://github.com/riya1234000/Dashboard-project/blob/326952f4c0d99b16db59433f51ad0c37acd64f17/Screenshot%202026-02-14%20022223.png" alt= "Image Description" width= "600">



## Process
verify data for any missing value and anomalies sort out the same.
Made sure data is consistent and clean with respect to data type, data format and values used.
Created pivot tables according to the questions asked.
Merge all pivot tables into one dashboard and apply slicer to make dynamic.

## Project Insights
- Call Center Dashboard – Project Insights

##  Overall Performance
- Total Calls: 1,000
- Total Duration: 89,850 minutes
- Total Purchase Amount: ₹96,623
- Average Satisfaction Rating: 3.89 / 5
- 5★ Ratings: 307 (≈30.7% of all calls)

##  Monthly Trends
- Peak Month: March (155 calls) — likely driven by fiscal year-end activity
- Lowest Month: August (50 calls) — possible holiday impact
- Insight: Call volumes show seasonal fluctuations; staffing and campaigns should align with high-demand months.

##  Weekday Patterns
- Highest Volume: Saturday (161 calls)
- Lowest Volume: Thursday (128 calls)
- Insight: Weekend demand is strong — optimize staffing and support coverage accordingly.

## Representative Efficiency
- Most Calls: R02 (218 calls)
- Highest Revenue: R03 (₹20.9K)
- Best Revenue per Call: R03 (₹101.0)
- Insight: R03 is the most revenue-efficient — ideal for performance incentives and best practice    modeling.

##  City & Demographics
- Top City by Calls: Cleveland (389 calls)
- Gender Split: 599 Female vs. 401 Male
- Highest Female-to-Male Ratio: Cleveland (≈5.2:1)
- Insight: Strong female engagement in Cleveland — tailor messaging and service strategies    accordingly.

##  Customer-Level Sales
- Top Customer: C0005 (Columbus) — ₹7,747 total sales
- Balanced Engagement: C0013 (Cleveland) — consistent sales across all regions
- Insight: Identify and nurture high-value customers for loyalty and upselling opportunities.

## Satisfaction Distribution
- Rating 4 Dominates: 428 calls
- 5★ Ratings: 307 calls
- Low Ratings (0–2): 68 calls
- Insight: Majority of calls are rated 4–5, but converting 4s to 5s can significantly boost customer experience metrics.

## Strategic Recommendations
- Forecast call volumes using historical monthly and weekday trends
- Prioritize R03 for training replication and incentive modeling
- Launch targeted campaigns in Cleveland, especially for female customers
- Investigate low-rating calls to improve service quality and resolution
- Use low-volume months (Aug, Dec) for training, system upgrades, or outbound engagement

