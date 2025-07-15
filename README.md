# Customer-Churn-Analysis-Dashboard
## Technology used:
Power BI

DAX

SQL
## Important KPIs 
•	Total Customer

•	Active Customers

•	Inactive Customers

•	Credit Card Holders

•	Non Credit Card Holders

•	Exit Customers

•	Retain Customers

## Business Problem Addressed

The dashboard is designed to help the business understand and analyze the factors driving customer churn, enabling data-driven retention strategies by segmenting churn by different customer attributes and visualizing trends over time.

This analysis page helps stakeholders:

•	Identify which customer groups are most likely to leave.

•	Understand how economic and demographic factors (age, income, credit score, geography) correlate with churn.

•	Track the effectiveness of retention strategies over time.

## Key Elements and Visuals
1.	Exit Customers by Year and Age Group (Bar Chart)

Compares the number of exiting customers each year (2016-2019) across three age groups: Mid Age, Senior Citizen, Young People.

Shows trends such as higher churn among certain age groups in particular years.

2.	Exit Customers by Year and Credit Score Type (Ribbon Chart)

Breaks down exit customers by credit score categories (Excellent, Fair, Good, Poor, Very Good) for each year.

Helps see if creditworthiness relates to churn.

3.	Exit Customers by Month and Gender Category (Line Chart)
	
Plots monthly exit customer counts, split by gender (Female, Male).

Reveals seasonal or gender-specific churn patterns.

4.	Geography/Location vs. Exit Category (Decomposition Tree)

Shows customer distribution by country (France, Germany, Spain) and by exit/retain status.

For example: France has 5014 total customers, with 810 exits and 4204 retained.

## Insights Provided
•	Churn Rate: Out of 10K customers, 2037 have exited and 7963 have been retained.

•	Customer Segmentation: Churn is analysed by age, credit score, gender, country, and more.

•	Credit Card Impact: Fewer non-credit card holders than credit card holders.

•	Geographical Patterns: France has the largest customer base, followed by Germany and Spain.

5. Month-wise Exit Customer Counts (Scroller Chart)

•	Nov_2019: 97 exit customers

•	Sep_2019: 96 exit customers

•	Insight: Shows monthly churn counts, helping to identify recent spikes or trends. November and September 2019 is showing high churn.

6. Active vs Inactive Customers by Age Group (Tornado Chart is best for comparing two categories)

•	Young People: 3018 active vs 2969 inactive

•	Mid Age: Tooltip shows 1758 active members

•	Senior Citizen: 375 active vs 89 inactive

•	Insight: Young people segment has a nearly equal split between active and inactive members, indicating higher churn risk. Senior citizens have much fewer inactive members (lower churn), but their overall numbers are much smaller.

7. Country wise Percentage of Exit Customers by Credit Score (Stacked 100% Column Chart)

•	Insight: Across all countries, the majority of exit customers have “Poor” or “Fair” credit scores, suggesting a strong link between creditworthiness and churn. Spain has the highest proportion of exit customers with poor credit scores.

8. Percentage of Exit Customers by Salary Group (Donut Chart)
 
•	High Income: 305 (14.97%)

•	Low Income: 394 (19.34%)

•	Mid Income: 1338 (65.68%)

•	Insight: The majority of exit customers are in the mid-income group, but low-income customers are overrepresented relative to typical population distributions, suggesting income could be a risk factor.

Churn Percentage Year and Month Wise (Grid View, Matrix)

•	Rows: Years 2016–2019

•	Columns: Jan–Dec

•	Cells: Show churn % for each month

•	Insight:

Churn percentage fluctuates throughout the years and months.

Highest monthly churn appears to occur sporadically (e.g., May 2017: 26.71%, Jan 2017: 27.59%)

2019 has generally lower churn percentages compared to earlier years

## Overall Insights & Recommendations

•	Customer Segmentation: The dashboard allows deep dives into churn by age, income, country, and credit score, making it possible to target retention strategies more effectively.

•	At-Risk Groups: Young people and mid-income customers show higher churn, as do those with poor credit.

•	Temporal Trends: Churn rates have declined over time, but certain months consistently see higher churn, indicating possible seasonality or the impact of specific events.

•	Geographic Patterns: While Germany, France, and Spain show similar patterns, Spain stands out with the highest percentage of poor credit score churners.

## Demos/Screenshot, How the Dashboard looks like
!(https://github.com/s-barman/Customer-Churn-Analysis-using-Power-BI/blob/main/Customer_Churn_Image.jpg)







