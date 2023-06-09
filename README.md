# Overview 

(1) Below is a customer order segmentation analysis, where I analyzed confidential direct marketing dataset (226K records, 100K customers) to guide customer engagement strategies.

(2) The analysis is achieved through documenting channel buying patterns by leveraging RFM ranking, heatmap analysis, and trendline plotting, as shwon in Tableau dashboards.

(3) Through my analysis, I discover 2 main problems faced by category O: **small sales volume and lack of high RFM ranking customers**. With the help of the 2 dashboards below, C-suites and management of category O can can monitor the metrics presented and extract actionable insgihts that will help tackle the 2 problems.


# Level 1 Dashboard

- Dashboard 1 is specifically for C-level executives who are interested in the long-term success of the business. By utilizing Dashboard 1, C-level executives should be able to gain a high-level understanding of the most important marketing and sales metrics related to the category of interest. 

![Level 1 Dashboard](https://user-images.githubusercontent.com/59977422/234101923-e15129f0-1d96-400b-84c5-da7712642a29.png)

## What These Metrics Are and Why We Present Them

(1) Overall Category Revenue with Benchmark (Quarterly)

- See how the category is performing over time compared to benchmark categories, such as sales leader category T and E.

- Actionable insight: if sales patterns of category O do not follow benchmark patterns at some quarters, executives should diagnose potential causes of missed growth opportunities (e.g. 2006 Q2) to avoid future mistakes. 

(2) Sales by Division ID (Quarterly)

- Understand which of the 2 divisions is performing better in terms of sales.

- Actionable insight: if a division underperforms, executives should evaluate the long-term viability of that division.

(3) Top 5 Products with Highest Sales (Quarterly)

- Identify which product(s) drive the most sales in the category. 

- Actionable insight: executives can allocate resources to these products within the category to boost growth.

(4) Customers by RFM Score (Yearly)

- Visualize the customer behaviors over the years.

- Actionable insight: executive can pinpoint years when higher RFM ranking customers were lost and identify causes (e.g. 2008).

(5) Sales Heat Map (Overall)

- Allows executives to see a visual of sales by geographic region

- Actionable insight: executives can target specific geographic regions: develop small / new markets and retain lucrative markets (e.g. 77304, Texas).

## How Often the Dashboard Should Be Updated

- Level 1 dashboard focuses on high-level KPIs that provide an overview of the category's performance, including comparisons to other categories. I suggest updating the dashboard's metrics monthly or quarterly, depending on the metric and data availability.


# Level 2 Dashboard

- Dashboard 2 is specifically for marketing managers who are interested in both the short-term and long-term success of the business. By utilizing Dashboard 2, marketing managers should be able to gain an in-depth understanding of how marketing and sales are acting across the category of interest.

![Level 2 Dashboard](https://user-images.githubusercontent.com/59977422/234101598-54a98585-9c95-4a87-9c8f-4ab45f1edc89.png)

## What These Metrics Are and Why We Present Them

(1) Overall Category Revenue (Weekly)

- See if sales for a particular week (or holidays) are better or worse than previous years.

- Actionable insight: marketing managers can utilize this short-term revenue information to infer seasonality associated with the product and create marketing campaigns and strategies accordingly.

(2) Revenue by Channel (Quarterly)

- Examine which channels account for the majority of sales revenue.

- Actionable insight: managers can differentiate advertising budget in different channels to maximize ROI. In this case, minimize mail campaigns becasue they are very ineffective.

(3) RFM Rank by Zip Code Heat Map

- Understand the pattern of customer behaviors in different geographic locations.

- Actionable insight: managers can then determine target customer personas and design marketing campaigns and sales strategy around these personas to develop low RFM ranking customers and retain high RFM ranking customers.

(4) Cancellation and Back Order Rates (Quarterly)

- Determine if there is a correlation between cancellations and back orders.

- Actionable insight: the back-order rate and cancellation rate follow extremely similar patterns. Thus, managers should better manage supply chain to minimize backorders and maximize sales, since back orders are likely to be cancelled.

(5) Offer Use as % of Total Revenue and Orders

- Find out if offers incentivize purchases. 

- Actionable insight: one can observe that regardless of offers are mailed or not, purchases associated with offers constitute more than 82% of total sales and 77% of total orders. Thus, (a) marketing managers should ensure as many customers have knowledge of / access to offers, because they can boost sales; (b) this shows mail campaigns are ineffective and should be minimized 

## How Often the Dashboard Should Be Updated

- Level 2 dashboard focuses on more granular metrics that provide insights into specific areas of the business. I suggest updating the dashboard weekly (as data permits), with the intent that marketing managers use the dashboard to drive business decisions such as marketing and product emphasis.

# Quick Glimpse of the Summary
To understand more details of the project, please read the summary below:

# Why We Choose this Specific Category to Study
Following my analysis of the broader dataset, I chose to conduct a more in-depth analysis of Category O. While Category O only represents approximately 1% of the total sales, we believe it is important to fully analyze category O so that one can pinpoint sources of underperformance and areas of potential improvement. We believe this to be true for several reasons, including: 

1. Category O has historically sold more to women than men. While we cannot know exactly why this is the case based purely on the data provided, we can utilize the data from Category O to potentially replicate this success in the female demographic across other categories. 

2. Category O has grown approximately at the same rate as Category E, the category with the largest number of sales in the dataset. Additionally, Category O had a very significant increase in growth in 2010, which can be examined further to determine what made that success a reality. 

3. Category O is relatively successful in terms of cross-selling products. With that being the case, we can look at those data points combined with RFM metrics to understand which customers are buying multiple products and see if that success can be amplified to grow Category O sales. This could potentially be replicated to help other category sales as well. 

# Analysis and Approaches
We undertook several analyses to dive deeper into Category O. 

- The first of these analyses was a growth analysis in which we compared the growth of Category O sales to the growth of other category sales in the dataset. What we found is that while Category O sales growth is not the best among the categories in the data set, it is middle-of-the road, showing that Category O is competitive among the categories in the dataset over the entire subject period and that the interest in the category has continually grown over time. 


- The second analysis we undertook was a closer look at trends by year and gender. Category O sold more in quantity to females compared to males across most of the period the dataset covers. The data also suggests seasonality of the category. Most of the units were sold between October and January suggesting it could be an essential product for Winter or the festive season. 


- The third analysis we undertook was an RFM analysis to understand which customers may be most valuable to Category O. This analysis also allowed us to understand which types of customers we may want to target based on who our current most profitable customers are. Also, we have leveraged a heatmap analysis to see where these customers are geographically located.


- The final analysis we undertook was a market basket analysis to understand which products customers buy, and to see which combination of items customers buy (if they purchase multiple products within Category O). 


# Conslusion
Based on the result of the analyses above, I have identified the 2 main problems afflicting category O: **small sales volume and lack of high RFM ranking customers**. Thus, the C-suites and management of Category O need to constantly monitor the metrics proposed in the dashboards above to understand underperformance issues and address the 2 problems.
