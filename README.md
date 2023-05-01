# Overview 

- Below is a customer order segmentation analysis, where I analyzed confidential direct marketing dataset (226K records, 100K customers) to guide customer engagement strategies.

- The analysis is achieved through documenting channel buying patterns by leveraging RFM ranking, heatmap analysis, and trendline plotting, as shwon in Tableau dashboards.

- Throught my analysis shown in the following dashboards, I discover 2 main problems faced by category O: **small sales volume and lack of high RFM ranking customers**. Therefore, with the help of the 2 dashboards below, we explain what actionable insgihts we can extract from the metrics.

# Level 1 Dashboard

- Dashboard 1 is specifically for C-level executives who are interested in the long-term success of the business. By utilizing Dashboard 1, C-level executives should be able to gain a high-level understanding of the most important marketing and sales metrics related to the category of interest. 

![Level 1 Dashboard](https://user-images.githubusercontent.com/59977422/234101923-e15129f0-1d96-400b-84c5-da7712642a29.png)

## What these metrics are and why we present them

(1) Overall Category Revenue with Benchmark (Quarterly)

- See how the category is performing over time compared to benchmark categories, such as sales leader category T and E.

- Actionable insight: if sales patterns of category O do not follow benchmark patterns at some quarters, executives should diagnose potential causes of missed growth opportunities (e.g. 2006 Q2) to avoid future mistakes. 

(2) Sales by Division ID (Quarterly)

- Understand which of the 2 divisions is performing better in terms of sales.

- Actionable insight: if a division underperforms, executives should evaluate the long-term viability of that division.


(3) Top 5 Products with Highest Sales (Quarterly)

- Identify which product(s) drive the most sales in the category. 

Actionable insight: executives can allocate resources to these products within the category to boost growth.


(4) Customers by RFM Score (Yearly)

- Visualize the customer behaviors over the years.

- Actionable insight: executive can pinpoint years when higher RFM ranking customers were lost and identify causes (e.g. 2008).



(5) Sales Heat Map (Overall)

- Allows executives to see a visual of sales by geographic region

- Actionable insight: executives can target specific geographic regions: develop small / new markets and retain lucrative markets (e.g. 77304, Texas).


# Level 2 Dashboard

- Dashboard 2 is specifically for marketing managers who are interested in both the short-term and long-term success of the business. By utilizing Dashboard 2, marketing managers should be able to gain an in-depth understanding of how marketing and sales are acting across the category of interest.

![Level 2 Dashboard](https://user-images.githubusercontent.com/59977422/234101598-54a98585-9c95-4a87-9c8f-4ab45f1edc89.png)


# Quick Glimpse of the Summary
To understand more details of the project, please read the summary below:

# Why We Choose This Specific Category To Study
Following our analysis of the broader dataset, our group chose to conduct a more in-depth analysis of Category O. While Category O only represents approximately 1% of the total dataset, we believe it is important to fully analyze category O so that one can pinpoint sources of underperformance and areas of potential improvement. We believe this to be true for several reasons, including: 


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
Based on all these analyses, we have determined that the C-suites and management of Category O need to constantly monitor the metrics proposed above and address the problems associated with each metric. 
