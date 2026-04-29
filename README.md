## Business Problem
The company is investing in multiple marketing channels but lacks visibility into acquisition efficiency and customer profiability. High marketing spend combined with uneven performance across channels suggest potential inefficiences in budget allocation. The goal of this analysis is to evaluate key unit economics metrics(CAC, LTV, ROMI) to identify which channels drive profiability and optimize marketing investment.

## Data Overview
The dataset includes:
- User activity (sessions, visits).
- Orders and revenue
- Marketing spend by acquisition source
This allows analysis of customer behavior, conversion patterns and profiability across marketing channels.

## Analysis
This analysis was conducted using SQL and Python, focusing on:
 - User activity trends
 - Conversion Behavior
 - Revenue per user and LifeTime Value (LTV)
 - Customer Acquisiton Cost (CAC) by channel
 - Return of Marketing Investment (ROMI)

## Key Insights
- The platform shows strong growth, with daily users increasing from 450 to over 2000 sessions, indicating successful acquisition efforts.
- Average Revenue per user is approximately $5, with an estimated LTV of $6.90, confirming recurring value beyond initial pruchase.
- Marketing spend totals $329, with significant imbalance across channels.
- Source 3 represents the highest spend ($141) but shows poor efficiency, indicating value destruction.
- High performing channels include:
    - Source 1: Extremely high ROMI (x109) with low CAC ($1.09) 
    - Source 5: Strong Balance between CAC ($0.90) and ROMI (21.8).
    - Source 4: Low CAC and solid returns
- Some low.cost channels provide strong efficiency despite lower spend.

## Business Recomendations
- Relocate budget toward high-performing channels (Sources 1, 5, 4 and 9) to maximize return of investment
- Reduce or eliminate investment in inefficient channels like Source 3, which currently consumes a large portion of budget with poor retunrs.
- Mantain and optimize mid-perfomming channels like Source 2 and 10 to improve efficiency.
- Temporarily pause channels with insufficient data like Source 6 and 7 until performance can be validated.
- Focus on scale channels with strong LTV / CAC ratios rather than those driving only volume.

## Expected Impact 
- Potential reduction in wasted marketing spend by 20-30%
- Improved ROI through budget reallocation toward high-perfoming channels.
- Increased overall marketing efficiency and profiability.
- Better alignment between customer acquisition and long-term value (LTV)

## Dashboard & Visualizations
Key metrics were visualized to support decision-making:
- CAC by channel  
- LTV and revenue per user  
- ROMI by source  
- User activity trends
### CAC by Channel


### LTV vs CAC


### User Activity Trend


## Tools used
- SQL (Data extraction and aggregation)
- Python (Pandas, Matplotlib)
- Data Visualization (Power BI)
